<template>
  <div>
    <h1>Posts {{ id }}</h1>
    <button @click="router.go(-1)">GO BACK</button>
  </div>
</template>

<script setup>
const {id} = useRoute().params
const router = useRouter();
</script>

<style lang="scss">
</style>