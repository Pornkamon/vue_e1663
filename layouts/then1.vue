<template>
    <!-- App.vue -->

<v-app>
   <v-system-bar dark color="red lighten-2">
      <v-spacer></v-spacer>
      <v-icon>mdi-wifi-strength-4</v-icon>
      <v-icon>mdi-signal-cellular-outline</v-icon>
      <v-icon>mdi-battery</v-icon>
      <span>12:30</span>
    </v-system-bar>
    
  <v-navigation-drawer app>
    <!-- -->
  </v-navigation-drawer>

<div>
<v-app-bar>
    <v-tabs
      dark
      background-color="primary"
      grow
    >
      <v-tab>
        <v-badge
          color="pink"
          dot
        >
          หน้าหลัก
        </v-badge>
      </v-tab>

      <v-tab>
        <v-badge
          color="green"
          content="6"
        >
          ประวัติ
        </v-badge>
      </v-tab>

      <v-tab>
        <v-badge
          color="deep-purple accent-4"
          icon="mdi-vuetify"
        >
          Login
        </v-badge>
      </v-tab>
    </v-tabs>
    </v-app-bar> 
</div>

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-content>
      <nuxt/>
    </v-content>
  </v-main>

  <v-footer>
    <v-btn>
      <span>Recents</span>
      <v-icon>mdi-history</v-icon>
    </v-btn>

    <v-btn>
      <span>Favorites</span>
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn>
      <span>Nearby</span>
      <v-icon>mdi-map-marker</v-icon>
    </v-btn>

  </v-footer>

</v-app>
</template>
