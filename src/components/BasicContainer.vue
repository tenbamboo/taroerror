<template>
  <view class="basicContainer">
    <view>我是基本容器</view>
    <Comp1 />
    <slot />
  </view>
</template>

<script>
import Comp1 from './Comp1.vue'




export default {
  components: {
      Comp1
  },
  data() {
    return {
      
    };
  },
  computed: {},
  methods: {
  },
};
</script>

<style lang="scss" >
.basicContainer{
  text-align:center;
  color:red;
}
</style>
