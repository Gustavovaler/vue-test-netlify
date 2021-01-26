<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark-blue">
  <a class="navbar-brand" href="#">Tienda Tik</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        
        <router-link to="/" class="nav-link">Home</router-link> 
      </li>
      <li class="nav-item active">
        <router-link to="/about" class="nav-link">About</router-link>
      </li>
      <li class="nav-item active">
       <router-link to="/about" class="nav-link">About</router-link>
      </li>
      <li class="nav-item active">
       <router-link to="/about" class="nav-link">About</router-link>
      </li>
    </ul> 
    <router-view/>
  </div>
</nav>
 
</template>

<style>
.bg-dark-blue{
  background-color: rgb(22, 3, 66);
}
</style>
