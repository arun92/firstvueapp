<template>
  <div class="hello">
    
   <h1>{{title}}</h1>
      <h4>{{descrption}}</h4>
      <button type="button" @click="showLoader">Show Loader</button>
      <h2 v-show="loading">Loading...</h2>
  </div>
</template>

<script>
export default {
  name: 'This is test component',
  props: {
    title: String,
    descrption:String,
    loading:Boolean
  },
  data(){
this.loading=false
  },
  methods:{
    showLoader(){
this.loading=true;
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
