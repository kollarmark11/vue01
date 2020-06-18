<template>
  <div id="app">
    <div id="nav">
      <router-link to="/" id="navs">Home</router-link>
      <router-link to="/about" id="navs">About</router-link>
      <router-link to="/contact" id="navs">Contact</router-link> 
    </div>
    <router-view />
  </div>
</template>

<style>
  *{
    margin:10px;
  }
  #app{
    text-align: center;
    width:100%;
    margin:0;
  }
  #nav{
    padding: 10px;
    text-align: right;
  }
  #navs{
    padding:10px 70px 10px 70px;
    text-decoration: none;
    color:#000;
  }
</style>
