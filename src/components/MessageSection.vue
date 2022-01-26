<template>
  <v-container >
    <v-row class="text-center">
      <v-col class="" cols="12">
        <h1 class="display-3 font-weight-bold mb-3">
          Contact Us
        </h1>
      </v-col>
    </v-row>
    <v-row class="text-center">
      <v-col class="" cols="6">
        <v-form
            ref="form"
            v-model="valid"
            lazy-validation
        >
            <v-text-field
            v-model="name"
            :counter="10"
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
            clearable
            label="Your Message"
            :rules="messageRules"
            :value="message"
            ></v-textarea>

            <v-btn
            :disabled="!valid"
            color="success"
            class="mr-4"
            @click="validate"
            >
            Send Message
            </v-btn>

            <v-btn
            color="error"
            class="mr-4"
            @click="reset"
            >
            Reset Form
            </v-btn>

            <v-btn
            color="warning"
            @click="resetValidation"
            >
            Reset Validation
            </v-btn>
        </v-form>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'MessageSection',
    data: () => ({
      valid: true,
      name: '',
      nameRules: [
        v => !!v || 'Name is required',
        v => (v && v.length <= 10) || 'Name must be less than 10 characters',
      ],
      email: '',
      emailRules: [
        v => !!v || 'E-mail is required',
        v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
      ],
      messageRules: [v => v.length <= 25 || 'Max 25 characters'],
      message: 'Hello!',
    }),

    methods: {
      validate () {
        this.$refs.form.validate()
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

</style>