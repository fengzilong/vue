<template lang="pug">
zi-slider(v-model="value" :step="20" :show-stops="true")
</template>

<script>
export default {
  name: 'ex-slider-step',

  data: () => ({
    value: 0,
  }),

  watch: {
    value(val) {
      console.log(val)
    },
  },
}
</script>
