<template>
  <div>
    <p>{{hobby}}</p>
    <label>
      抽烟<input type="radio" v-model="hobby" value="抽烟">
    </label>
    <label>
      喝酒<input type="radio" v-model="hobby" value="喝酒">
    </label>
    <label>
      烫头<input type="radio" v-model="hobby" value="烫头">
    </label>
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
