<template>
  <div>
    <h2 class="demo">学校名称：{{ name }}</h2>
    <h2>学校地址：{{ address }}</h2>
    <button @click="showName">弹窗</button>
  </div>
</template>

<script>
  export default {
    name: 'School',
    data() {
      return {
        name: '江西科技学院',
        address: '江西',
      }
    },
    methods: {
      showName() {
        alert(this.name)
      },
    },
  }
</script>

<style>
  .demo {
    background-color: pink;
  }
</style>
