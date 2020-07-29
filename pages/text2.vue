<template>
 <v-app>
   <v-card class="grey lighten-1 black--text">
     <v-card-text>
       <v-form class="black--text" >
           <center><v-list-item-avatar width="90" height="90">
            <img src="images/5.jpg" />
          </v-list-item-avatar></center>
           <br>
            <v-text-field label="Username"filled outlined dense></v-text-field>
            <v-text-field label="Password"filled outlined dense></v-text-field>
           <div class="d-flex">
      <v-checkbox
        v-model="readonly"
        label="Readonly"
      ></v-checkbox>
      <v-spacer></v-spacer>
      <p class="grey lighten-1">Forgot Password</p>
    </div><br>
      <div class="container">
                <nuxt-link to="/text3">
                 <v-btn block style="background:#2196f3;">Sign in</v-btn>
                 </nuxt-link>
            </div>
       </v-form>
     </v-card-text>
   </v-card>
 </v-app>
</template>
<script>
export default {
    layout:"them2",
}
</script>