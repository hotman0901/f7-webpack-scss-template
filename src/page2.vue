<template lang="pug">
<f7-page hide-bars-on-scroll="">
  <f7-navbar back-link="Back" title="Page 2" sliding=""></f7-navbar>
  <f7-block>This is page 2.<br/>Data-binding {{mydata}}!</f7-block>
</f7-page>
</template>

<script>
export default {
  name: 'page2',
  data() {
    return {
      mydata: 'is okili-dokili'
    }
  }
}
</script>

<style lang="scss">

</style>
