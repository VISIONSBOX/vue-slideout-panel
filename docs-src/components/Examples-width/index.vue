<template src="./template.html"> </template>

<script>
export default {
  name: 'examples-width',
  data() {
    return {
      width: 600,
      height: 600
    };
  },
  methods: {
    showVerticalPanel() {
      this.$showPanel({
        component: 'panel-1',
        width: this.width,
        openOn: 'left'
      });
    },
    showHorizontalPanel() {
      this.$showPanel({
        component: 'panel-1',
        height: this.height,
        openOn: 'top'
      });
    }
  }
};
</script>

<style lang="less"></style>
