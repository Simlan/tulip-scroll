<template>
  <div>
    <tulip-scroll >
     <van-nav-bar
      title="无参数示例"
      left-text="返回"
      left-arrow
      @click-left="$router.go('-1')"
    />
     <h1>惊喜！！！！</h1>
    </tulip-scroll>
  </div>
</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods: {

  }
}
</script>

<style lang="less" scoped>

</style>
