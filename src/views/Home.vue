<template>
<v-container fluid>  

 <Hello />
 <AboutMe/>
</v-container>
 
</template>

<script>
import Hello from '../components/Hello.vue'
import AboutMe from '../components/AboutMe.vue'


  export default {
    name: 'Home',

    components: {
    Hello,
    AboutMe,
    
},
  }
</script>
