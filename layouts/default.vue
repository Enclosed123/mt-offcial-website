<template>
  <el-container>
    <el-header>
      <my-header></my-header>
    </el-header>
    <el-main>
        <nuxt />     
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script>
import myHeader from '../components/public/header/index'
export default {
  components:{
    myHeader,
  }
}
</script>

<style>

</style>
