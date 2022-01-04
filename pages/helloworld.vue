<template>
  <NuxtLayout name="custom">
    <template>
      <div>
        <h1>helloworld page</h1>
      </div>
    </template>
    <template>
      <div>content....</div>
    </template>
  </NuxtLayout>
</template>
<script>
// 使用自定義布局頁
// export default {
//   layout: 'custom'
// }

// 使用完全控制布局頁
export default {
  layout: false,
};
</script>
