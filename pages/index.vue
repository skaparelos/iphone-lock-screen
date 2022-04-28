<template>
  <!-- <Tutorial/> -->
  <div>
    <h1>Hello staging  </h1>
    <iphone />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  mounted() {
    console.log(process.env.NUXT_ENV_HELLO);
  }
}
</script>
