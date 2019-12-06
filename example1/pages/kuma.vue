<template>
  <div class="test">
   <HomeButton /><HomeButton /><HomeButton /><HomeButton /><HomeButton />
  </div>
</template>

<style scoped>
.test {
  background-color: #fff;
}
</style>

<script>
import HomeButton from '~/components/HomeButton.vue'

export default {
  components: {
    HomeButton
  }
}
</script>