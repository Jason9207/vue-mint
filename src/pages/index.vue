<template>
  <mt-tabbar>
    <mt-tab-item id="外卖">
      <img slot="icon" src="../../static/images/feedback.png">
      外卖
    </mt-tab-item>
    <mt-tab-item id="订单">
      <img slot="icon" src="../../static/images/feedback.png">
      订单
    </mt-tab-item>
    <mt-tab-item id="发现">
      <img slot="icon" src="../../static/images/feedback.png">
      发现
    </mt-tab-item>
    <mt-tab-item id="我的">
      <img slot="icon" src="../../static/images/feedback.png">
      我的
    </mt-tab-item>
  </mt-tabbar>
</template>

<script>
import Vue from 'vue'
import { Tabbar, TabItem } from 'mint-ui'
Vue.component(Tabbar.name, Tabbar)
Vue.component(TabItem.name, TabItem)
</script>
