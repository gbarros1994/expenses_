<template>
  <div id="app">
    <base-spinner></base-spinner>
    <h3>Conteudo da aplicação</h3>
    <router-link to="/">Home</router-link> |
    <router-link to="login">Login</router-link>
    <router-view/>
  </div>
</template>