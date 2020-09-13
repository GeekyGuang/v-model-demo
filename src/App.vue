<template>
  <div>
    <p>{{hobby}}</p>
    <select name="hobby" v-model="hobby">
      <option disabled value="">--</option>
      <option>抽烟</option>
      <option>喝酒</option>
      <option>烫头</option>
    </select>
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      message:'',
      checked: false,
      hobby:''
    }
  }
}
</script>

<style>

</style>
