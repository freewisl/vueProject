<template>
  <div>
    <div>
      <select name="" id="">
        <option :value="city.code" :key="city.code" v-for="city in cities">{{ city.title }}</option>
      </select>
    </div>
  </div>
</template>
<script>
export default {
  tcomponents: {},
  data() {
    return {
      cities: [
        { title: '서울', code: '02' },
        { title: '부산', code: '051' },
        { title: '제주', code: '064' }
      ]
    }
  },
  setup() {},
  created() {},
  mountec() {},
  unmounted() {},
  methods: {}
}
</script>
