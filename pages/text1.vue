<template>
    <v-app style="background:#f7f9fa;">
        <br>
        <center><h2 style="color:#000;">Welcome!</h2>
        <p style="color:#a8adaf;padding-left:80px;padding-right:80px;">Listen to your favorite artists and 
            albums whenever and online and.</p></center>
<br>
<div>
    <center><img src="../img/01.jpg" width="350" height="300" style="margin-bottom:-100px;margin-top:50px;margin-left:10px;margin-right:10px;"></center>
    <center><img src="../img/01.jpg" height="350" width="250" style="margin-top:-225px;"></center>
</div>
<br>
<br>
            <div class="container">
                <nuxt-link to="/text2">
                 <v-btn block style="background:#2196f3;">Sign in</v-btn>
                 </nuxt-link>
            </div>
    </v-app>
</template>
<script>
export default {
    layout:'them1',
}
</script>