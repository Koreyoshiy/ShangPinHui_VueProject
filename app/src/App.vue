<template>
  <div>
    <Header></Header>
   我是根组件
   <!--路由组件出口-->
   <router-view></router-view>
   <Footer></Footer>
  </div>
</template>

<script>
//引入
import Header from './components/Header'
import Footer from './components/Footer'
export default {
  name: '',
  components:{
      Header,
      Footer
  }
}

</script>

<style scoped>


</style>
