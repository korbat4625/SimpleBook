<template>
  <div class="default-main-content justify-start mt-72">
    <div class="holy-song">
      <BigText :title="$route.params.name" :fontSize="28" class="text-6xl" />
      <br>
      <div class="text-4xl ml-2">
        <div class="pb-16" v-html="getSong($route.params.name)"></div>
      </div>
    </div>
  </div>
</template>

<script>
import { findSong } from './songdata'
export default {
  created () {
    console.log(this.$route)
  },
  methods: {
    getSong (name) {
      console.log(findSong(name))
      return findSong(name)
    }
  }
}
</script>

<style>

</style>
