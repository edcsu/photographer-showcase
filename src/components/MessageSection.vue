<template>
  <div class="message-color py-16">
    <v-container>
      <v-row class="text-center">
        <v-col class="" cols="12">
          <h1 class="display-3 font-weight-bold mb-3 white--text">
            Contact Me
          </h1>
        </v-col>
      </v-row>
    </v-container>
    <v-card max-width="600" class="mx-auto mb-10" flat color="">
        <v-form
            ref="form"
            v-model="valid"
            lazy-validation
        >
          <v-card-text>
            <v-text-field
            v-model="name"
            :counter="60"
            :rules="nameRules"
            label="Your Name"
            required
            ></v-text-field>

            <v-text-field
            v-model="email"
            :rules="emailRules"
            label="E-mail"
            required
            ></v-text-field>

            <v-textarea
            :counter="255"
            clearable
            label="Your Message"
            :rules="messageRules"
            v-model="message"
            ></v-textarea>
          </v-card-text>

          <v-card-actions>
            <v-spacer></v-spacer>
            
            <v-btn
              color="warning"
              @click="resetValidation"
            >
            Reset Validation
            </v-btn>
            <v-btn
            :disabled="!valid"
            color="success"
            class="mr-4"
            @click="validate"
            >
            Send Message
            </v-btn>
          </v-card-actions>
        </v-form>
    </v-card>
  </div>
</template>

<script>
export default {
    name: 'MessageSection',
    data: () => ({
      valid: true,
      name: '',
      nameRules: [
        v => !!v || 'Name is required',
        v => (v && v.length <= 60) || 'Name must be less than 60 characters',
      ],
      email: '',
      emailRules: [
        v => !!v || 'E-mail is required',
        v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
      ],
      messageRules: [
        v => !!v || 'Message is required',
        v => v.length <= 255 || 'Max 255 characters'
      ],
      message: '',
    }),

    methods: {
      validate () {
        this.$refs.form.validate()
        this.reset()
      },
      reset () {
        this.$refs.form.reset()
      },
      resetValidation () {
        this.$refs.form.resetValidation()
      },
    },
}
</script>

<style>
  .message-color{
    background-color: #153243;
  }
</style>