<template>
  <div class="main">
    <input type="text" v-model="name">
    <p>{{titulo}} {{name}}</p>
    <div>
      <button @click="limpar">Limpar</button>
    </div>
  </div>
</template>
<script>
export default {
  props: ["titulo"],
  data: function(){
    return{
    name: ""
    }
  },
  methods: {
    limpar: function(){
      this.name = ""
    }
  }
}
</script>
<style>
  .main{
    background-color: #753bbd;
    margin-bottom: 10px;
    padding: 10px;
    margin-top: 1%;
    margin-left: 30%;
    margin-right: 30%;
    color: white;
    font-size: 20px;
    font-family: sans-serif;
  }
</style>