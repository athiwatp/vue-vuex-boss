<template lang="html">
  <div class="columns vvb-margin">
    <div class="column is-4 is-offset-4">
      <nav class="panel">
  <p class="panel-heading">
    {{ vHtml }}
  </p>
</nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'VHtml',
  data () {
    return {
      vHtml: '<p class="panel-heading"></p>'
    }
  }
}
</script>

<style lang="css" scoped >

.vvb-margin{
  margin-top: 30px;
}
</style>
