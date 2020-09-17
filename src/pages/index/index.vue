<template>
  <div>
    <button type="primary" @click="dianji">按钮</button>
    <div class="zhaojunkai">11111</div>
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  },

  components: {
  },

  methods: {
    dianji () {
      wx.showToast({
        title: '成功',
        icon: 'success',
        duration: 2000
      })
    }
  },

  created () {
  }
}
</script>
<style lang="scss" scoped>
  .zhaojunkai {
    color: #362c96;
  }
</style>