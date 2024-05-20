<script setup>
import {ref} from 'vue'
</script>
<template>

<nav class="navbar navbar-expand-lg navbar-dark border-bottom border-body">
  <div class="container-fluid">
    <router-Link class="navbar-brand" to="/"><h1 class="logo">VIMA<span>STORE</span></h1></router-Link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-Link class="nav-link" aria-current="page" to="/">Inicio</router-Link>
        </li>
        <li class="nav-item">
          <router-Link class="nav-link" aria-current="page" to="/about">Sobre</router-Link>
        </li>
        <li class="nav-item">
          <router-Link class="nav-link" aria-current="page" to="/contact">Contato</router-Link>
        </li>
      </ul>
    </div>
  </div>
</nav>

</template>
<style>


.navbar {
  background-color: #00474F;
}

.logo {
    display: flex;
    align-items: center;
    color: var(--tex-color);
    font-size: 2rem;
    font-weight: bold;
}

.logo i {
    color: var(--main-color);
    font-size: 1rem;
}

.logo {
    color: #34e7f8;
}

.logo span {
    color: #fff;
}

</style>