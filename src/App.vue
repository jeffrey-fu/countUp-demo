<template>
<div id="app">
  <vue-count-up :end="20000" :duration='10'></vue-count-up>
</div>
</template>

<script>
import vuecountup from './vuecountup.vue'
export default {
  components: {
    'vueCountUp': vuecountup
  }
}
</script>