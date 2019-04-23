<!-- 主文件 -->
<template>
  <div class="__viewName__"></div>
</template>

<script>
import ComponentA from "@/components/componentA";
import ComponentB from "@/components/componentB";

export default {
  components: {
    ComponentA,
    ComponentB
  }
};
</script>

<style lang="scss" scoped>
.__viewName__ {
  width: 100%;
  text-align: center;
  margin-top: 20px;
  .chart-wrapper {
    background: #fff;
    padding: 16px 16px 0;
    margin-bottom: 32px;
  }
}
</style>
