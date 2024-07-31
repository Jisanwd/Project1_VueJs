<template>
  <HeaderView/>
  <router-view :key="$route.fullPath"/>
  <FooterView/>
</template>

<script>
  import HeaderView from "@/components/home/HeaderView";
  import FooterView from "@/components/home/FooterView";
  export default {
    name: "App",
    components:{HeaderView,FooterView}
  }
</script>
<style>
</style>
