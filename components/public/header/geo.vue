<!-- 组件说明 -->
<template>
  <div class='m-geo'>
    <i class="el-icon-location"></i>
    北京市
    <nuxt-link to="changeCity" class="changeCity">切换城市</nuxt-link>
    [香河,廊坊,天津]
  </div>
</template>

<script>
  //import x from ''
  export default {
    components: {

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
  @import "@/assets/css/public/layout.scss"
</style>