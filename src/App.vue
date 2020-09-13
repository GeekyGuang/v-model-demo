<template>
  <div>
    <label>
      <input type="checkbox" v-model="checked">{{checked}}
    </label>
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      message:'',
      checked: false
    }
  }
}
</script>

<style>

</style>
