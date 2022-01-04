<template>
  <div>
    <h1>Index page</h1>
    <NuxtLink to="/detail">Detail Page</NuxtLink> |
    <!-- 動態路由 -->
    <NuxtLink to="/user-admin/2">/user-admin/0</NuxtLink> |
    <!-- 嵌套路由 -->
    <NuxtLink to="/parent">/parent/child</NuxtLink> |
    <NuxtLink to="/helloworld">/helloworld</NuxtLink> |
  </div>
</template>
