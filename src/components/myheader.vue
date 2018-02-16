<template>
<el-menu :default-active="activeIndex" mode="horizontal" class="el-menu-demo">
<el-menu-item index="1">Center</el-menu-item>
<el-menu-item index="2">Second</el-menu-item>
</el-menu>
</template>

<script type="text/javascript">
export default {
  data () {
    return {
      activeIndex: '1'
    }
  }
}
</script>
