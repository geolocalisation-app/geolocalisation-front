<template>
    <div class="container">
  <section>
    <header>
      <div class="wrapper">
        <nav>
          <Navbar />
        </nav>
      </div>
    </header>
    <div class="container-center">
    <RouterView />
    </div>
  </section>
  </div>
</template>


<script setup>
import { RouterLink, RouterView } from "vue-router";
import Navbar from "@/components/Navbar.vue";
</script>

<style>
@import "@/assets/base.css";
</style>
