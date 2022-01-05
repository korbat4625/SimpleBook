<template>
  <div class="default-main-content">出錯了 <br>{{ error.message }}</div>
</template>

<script>
export default {
  layout: 'alayout',
  props: {
    error: {
      type: Object,
      default: () => {}
    }
  }
}
</script>

<style>

</style>
