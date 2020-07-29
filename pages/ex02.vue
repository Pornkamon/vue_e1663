<template>
  <div>
    <h1>HELLO {{ first }}age:{{age}} </h1>
    <v-text-field
        v-model="first01"
        label="กรุณากรอกชื่อ"
        placeholder="กรุณากรอกชื่อของท่าน"
        outlined
        shaped   
          ></v-text-field>

    <v-text-field
        placeholder="กรุณากรอกชื่อของท่าน"
        rounded
        solo
    ></v-text-field>

    <v-text-field
        placeholder="กรุณากรอกชื่อของท่าน"
        solo
        dense
        loading
    ></v-text-field>

    <v-text-field
        label="กรุณากรอกชื่อ"
        placeholder="กรุณากรอกชื่อของท่าน"
        rounded
        filled
    ></v-text-field>
    

  </div>
</template>
<script>
export default {
  data:function(){
    return{
     name:"Pornkamon",
     age:19,
     dep:"information  technology",
     first:"Chaiyaphum",

    }
  }
}
</script>