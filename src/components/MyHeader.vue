<script setup lang="ts"></script>

<template>
  <header class="navbar bg-white text-black">
    <div class="flex-none">
      <img
        class="w-1/2"
        src="../assets/c.png"
        alt=""
        srcset=""
      />
    </div>
    <div class="flex-none">
      <ul class="menu menu-horizontal p-0">
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/about">About</router-link>
        </li>
        <li>
          <router-link to="/pricing">Pricing</router-link>
        </li>
      </ul>
    </div>
    <div class="flex-1">
      <slot></slot>
    </div>
  </header>
</template>
