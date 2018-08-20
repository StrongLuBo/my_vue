<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <input type="button" value="go_UserLogin" v-on:click="goUserLogin" />
    <h2>Ecosystem</h2>
 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods:{
  	goUserLogin:function(){
  		this.$router.push({path:'/UserLogin'})
  	}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
