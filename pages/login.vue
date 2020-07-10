<template>
 <v-app>
   <v-card>
     <v-card-title>
       <h1>Login</h1>
     </v-card-title>
     <v-card-text>
       <v-form>
         <v-text-field  prepend-icon="mdi-account-circle" label="Username" />
         <v-text-field prepend-icon="https" append-icon="visibility_off" label="Password" />
       </v-form>
         <v-card-actions>
        <nuxt-link to="/register"> 
        <v-btn large color="success">REGISTER</v-btn>
        </nuxt-link>
         <v-spacer></v-spacer>
        <v-btn large color="primary">LOGIN</v-btn>
        </v-card-actions>
     </v-card-text>
   </v-card>
 </v-app>
</template>