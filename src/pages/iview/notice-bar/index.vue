<template>
  <div>
    <i-panel title="通告栏">
      <i-notice-bar>
        2018年世界杯,将于6月14日至7月15日举行
      </i-notice-bar>
    </i-panel>
    <i-panel title="icon 通告栏">
      <i-notice-bar icon="systemprompt">
        2018年世界杯,将于6月14日至7月15日举行
      </i-notice-bar>
    </i-panel>
    <i-panel title="关闭 通告栏">
      <i-notice-bar icon="systemprompt" closable>
        2018年世界杯,将于6月14日至7月15日举行
      </i-notice-bar>
    </i-panel>
    <i-panel title="滚动 通告栏">
      <i-notice-bar icon="systemprompt" loop>
        2018年世界杯,将于6月14日至7月15日举行;2018年世界杯,将于6月14日至7月15日举行;
      </i-notice-bar>
    </i-panel>
  </div>
</template>

<script>
  export default {
    data () {
      return {}
    },
    methods: {}
  }
</script>

<style lang="less">
</style>
