<template>
 <!-- ส่วนบนสุด vuetifyjs -->
     <v-app>
         <v-card height="720px">
            <v-card-title class="Light purple white--text">
              <v-app-bar-nav-icon></v-app-bar-nav-icon>
                <v-toolbar-title>Page title</v-toolbar-title>
                <v-spacer></v-spacer>
                  <v-btn icon>
                   <nuxt-link to="/"> <v-icon>mdi-heart</v-icon></nuxt-link>
                  </v-btn>
                  <v-btn icon>
                    <v-icon>mdi-magnify</v-icon>
                  </v-btn>
                <v-icon>mdi-dots-vertical</v-icon>
            </v-card-title>
            <v-content>
              <nuxt/>
            </v-content>
         </v-card>
         <!-- ส่วนเนื้อหา -->
     </v-app>
 </template><template>
  <v-app>
       <v-system-bar dark color="indigo">
      <v-spacer></v-spacer>
      <v-icon>mdi-wifi-strength-4</v-icon>
      <v-icon>mdi-signal-cellular-outline</v-icon>
      <v-icon>mdi-battery</v-icon>
      <span>12:30</span>
  </v-system-bar>
    <v-navigation-drawer v-model="drawer" app clipped>
      <lang-selector />
      <v-divider></v-divider>
      <v-list dense>
        <v-list-item v-for="item in items" :key="item.title" @click>
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <div>
      <v-app-bar color="blue " dense white>
       <v-app-bar-nav-icon></v-app-bar-nav-icon>
        <v-toolbar-title>Destinations</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>

        
      </v-app-bar>
    </div>
    <v-content>
        <nuxt/>
    </v-content>
    <!-- Sizes your content based upon application components -->
    <v-main>
      <!-- Provides the application the proper gutter -->
    </v-main>
    <v-footer app>
      <!-- -->
    </v-footer>
  </v-app>
</template>