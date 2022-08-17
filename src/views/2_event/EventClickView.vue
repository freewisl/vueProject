<template>
  <div>
    <button @click="increaseCounter">Add1</button>
    <p>{{ counter }}</p>
  </div>
</template>
<script>
export default {
  tcomponents: {},
  data() {
    return {
      counter: 0
    }
  },
  setup() {},
  created() {},
  mountec() {},
  unmounted() {},
  methods: {
    increaseCounter() {
      this.counter += 1
    }
  }
}
</script>
