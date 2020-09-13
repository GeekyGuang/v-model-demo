<template>
  <div>
    <p>{{user}}</p>
    <form @submit.prevent>
      <label >
        name: <input v-model="user.name">
      </label>
      <label >
        password: <input type="password" v-model="user.password">
      </label>
      <button type="submit">确定</button>
      </form>

    
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      name: 'rose',
      user:{
        name:'',
        password:''
      }
      
    }
  },
  methods:{
    sayName(){
      alert(this.name)
    }
  }
}
</script>

<style>

</style>
