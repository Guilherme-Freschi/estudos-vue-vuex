<template>
  <div id="app">
    <img class="logo" alt="logo" width="100px" src="./assets/logo.png"> 
    <componente1 titulo="Nome:"/>
    <componente1 titulo="Profissão:"/>
    <componente1 titulo="Idade:" />
  </div>
</template>

<script>
import componente1 from '../../formulario/src/components/componente1.vue'
//oque usar? novo do arquivo novo.vue
 
export default {
  name: 'App',
  components: {
    componente1
  }
}
</script>

<style>
*{
  text-align: center;
}
.logo{
  margin-top: 10px;

}

</style>
