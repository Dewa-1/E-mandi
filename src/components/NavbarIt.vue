<template>
  <v-app-bar app color="white" flat>
    <v-badge color="#D5FODB" dot>
        <v-img src="1.png" contain width="30"></v-img>
    </v-badge>
    <v-toolbar-title class="ml-4">
        <span class="green-text">e-</span><strong>Mandi</strong>
    </v-toolbar-title>
    <v-spacer></v-spacer>
      <v-btn
                      color="green"
                      dark
                      x-large
                      class="py-7 d-none d-sm-none d-md-flex"
                    >
                      Login
                    </v-btn>
    <v-badge color="#FF6D59" overlap content="2" class="mr-2 mt-1">
      <v-avatar color="#FFF0EE" size="40">
        <v-icon x-small color="#FF6D59">far fa-heart</v-icon>
      </v-avatar>
    </v-badge>
    <v-badge color="#41AB55" overlap content="3" class="mr-2 mt-1">
        <v-avatar color="#ECF7EE" size="40">
            <v-icon x-small color="#41AB55">fas fa-shopping-cart</v-icon>
        </v-avatar>
    </v-badge>
    <span class="grey--text d-none d-sm-flex">Hello,<strong></strong>Tony</span>
    <v-avatar size="30" class="ml-2">
        <v-img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"></v-img>
    </v-avatar>
    <v-btn icon dark>
        <v-icon x-small color="#878A94">fas fa-chevron-down</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
name:'NavbarIt',
}
</script>

<style>
.v-toolbar_title{
    font-size: 1rem !important;
}
ul{
    display: flex;
    list-style: none;
    
}
ul, li{
    margin: 73px;
    
}
</style>