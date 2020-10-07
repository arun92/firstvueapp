<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <test-component title="Welcome to the test component" descrption="this component built to test component">
      
      </test-component>

      <br/> -->
 <h1>Routing Example</h1>
         <nav>
           <!-- <router-link to='/'>Home</router-link> &nbsp; &nbsp; &nbsp; -->
            <router-link to ='/Route1'>Router Link 1</router-link> &nbsp; &nbsp; &nbsp;
            <router-link to ='/Route2'>Router Link 2</router-link>
         </nav>
       <router-view/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import TestComponent from './components/TestComponent.vue'
 export default {
  // name: 'App',
  // components: {
  //   HelloWorld,
  //   TestComponent
  // }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
