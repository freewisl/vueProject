<template>
  <div>
    <input type="text" v-bind:value="userId" readonly />
    <input type="text" :value="userId" readonly />
    <br />
    <img :src="imgSrc" alt="" style="width: 100px; height: auto" />
    <br />
    <input type="search" v-model="txt1" name="" id="" />
    <button :disabled="txt1 === ''">조회</button>
  </div>
</template>
<script>
export default {
  tcomponents: {},
  data() {
    return {
      userId: 'seunghun',
      imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/2367px-Vue.js_Logo_2.svg.png',
      txt1: ''
    }
  },
  setup() {},
  created() {},
  mountec() {},
  unmounted() {},
  methods: {}
}
</script>
