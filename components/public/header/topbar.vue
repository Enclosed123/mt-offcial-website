<!-- 组件说明 -->
<template>
    <el-row :gutter="0" class="m-header">
  <el-col :span="5">
    <geo/>
  </el-col>
  <el-col :span="5">
    <user/>
  </el-col>
  <el-col :span="14">
    <nav-bar></nav-bar>
  </el-col>
</el-row>
    
</template>

<script>
   import Geo from './geo'
   import User from './user'
   import NavBar from './nav'
  //import x from ''
  export default {
    components: {
      Geo,
      User,
      NavBar,
    },
    data () {
      return {

      };
    },
    computed: {

    },
    methods: {

    },
  }
</script>

<style lang="scss">
@import "@/assets/css/public/layout.scss";

</style>