<template>
<h1 class="nav justify-content-center">這裡是前台</h1>
  <ul class="nav justify-content-center">
    <li class="nav-item">
      <router-link class="nav-link active" to="/">首頁</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/products">產品列表</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/cart">購物車</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link active" to="/admin">後台</router-link>
    </li>
  </ul>
  <router-view></router-view>
</template>
