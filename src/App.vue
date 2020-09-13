<template>
  <div>
    <label>姓名：
      <input type="text" v-model="message" placeholder="姓名">
    </label>
    <p>你的名字是：{{message}}</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      message:''
    }
  }
}
</script>

<style>

</style>
