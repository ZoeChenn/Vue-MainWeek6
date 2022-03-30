<template>
  <h1 class="nav justify-content-center">後台</h1>
  <ul class="nav justify-content-center">
    <li class="nav-item">
      <router-link class="nav-link active" to="/">首頁</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/admin/products">產品列表</router-link>
    </li>
  </ul>
  <router-view></router-view>
</template>
