<template>
 <div>
  <navbar-vue/>
   <router-view />
 </div>
</template>

<script>
import { defineComponent } from 'vue';
import NavbarVue from './components/Navbar.vue';

export default defineComponent({
   components:{
    NavbarVue
   }
})
</script>
<style lang="scss">

</style>
