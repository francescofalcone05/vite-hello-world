<script>
import HelloWorld from './components/HelloWorld.vue' ; 

export default {
  components: {
    HelloWorld
  },
  data (){
    return {
      welcomeMsg: 'Benvenuti',
    }
  }
}

</script>

<template>
<h1>{{ welcomeMsg }}</h1>
<HelloWorld />
</template>


