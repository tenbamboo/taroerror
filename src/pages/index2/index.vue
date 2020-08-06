<template>
  <view class="index">
    <BasicContainer>
      <view>我是首页2</view>
      <NumberDisplay />
      <NumberSubmit />
    </BasicContainer>
  </view>
</template>

<script>
import NumberDisplay from '../../components/NumberDisplay.vue'
import NumberSubmit from '../../components/NumberSubmit.vue'
import BasicContainer from '../../components/BasicContainer.vue'


export default {
  name: 'Index2',
  components: {
    NumberDisplay,
    NumberSubmit,
    BasicContainer
  }
}
</script>

<style>
.index {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
