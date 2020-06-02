<template>
  <div class="avatar">
    <img :src="src" alt="头像" />
  </div>
</template>

<script>
export default {
  name: 'avatar',
  props:{
    src: {
      type: String,
      default: ''
    }
  }
}
</script>

<style lang="scss">
.avatar {
  width: 40px;
  height: 40px;
  border-radius: 100%;
  background-color: #ccc;
}
</style>