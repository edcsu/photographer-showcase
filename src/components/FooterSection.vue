<template>
  <div class="mt-n4">
  <v-footer
    color=""
    padless
  >
    <v-container>
      <v-row
        justify="center"
      >
        <v-col
          class=""
          cols="4"
        >
          <h1> About Us</h1>
          <v-list color="#F5F5F5">
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Our Company</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Blog</v-list-item-title>
              </v-list-item-content>
            </v-list-item><v-list-item>
              <v-list-item-content>
                <v-list-item-title>Sucess Stories</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Reviews</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Careers</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-col>
        <v-col
          class=""
          cols="4"
        >
          <h1> Support</h1>
          <v-list color="#F5F5F5">
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Live Chat</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>+256 800 000 000</v-list-item-title>
              </v-list-item-content>
            </v-list-item><v-list-item>
              <v-list-item-content>
                <v-list-item-title>Sucess Stories</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Send Us Mail</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>FAQs</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-col>
        <v-col
          class=""
          cols="4"
        >
          <h1> Products</h1>
          <v-list color="#F5F5F5">
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Company</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Personal</v-list-item-title>
              </v-list-item-content>
            </v-list-item><v-list-item>
              <v-list-item-content>
                <v-list-item-title>Studio</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Celebrations</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>Events</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-col>
      </v-row>
    </v-container>
  </v-footer>
  <v-container fluid>
      <v-row
        justify="center"
        no-gutters
      >
        <v-col
          class="white lighten-2 py-4 text-center black--text"
          cols="12"
        >
          <v-card-text>
          <v-btn
            v-for="icon in icons"
            :key="icon"
            class="mx-4 black--text"
            icon
          >
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-text>
        </v-col>
        <v-col
          class="white lighten-2 py-4 text-center black--text"
          cols="12"
        >
          Copyright @Keith. All rights reserved {{ new Date().getFullYear() }}
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
  export default {
    name: 'FooterSection',

    data: () => ({
      links: [
        'About Us',
        'Services',
        'Support',
        'Resources',
        'Products',
      ],
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
  }
</script>