<template>
  <div>
    <!-- <input type="search" name="" id="" @keyup="checkEnter($event)" v-model="searchText" /> -->
    <input type="search" name="" id="" @keyup.enter="doSearch" v-model="searchText" />
    <button @click="doSearch">조회</button>
  </div>
</template>
<script>
// .stop - event.sstopPropagation();
// .prevent - event.preventDefault();
export default {
  tcomponents: {},
  data() {
    return {
      searchText: ''
    }
  },
  setup() {},
  created() {},
  mountec() {},
  unmounted() {},
  methods: {
    doSearch() {
      console.log(this.searchText)
    },
    checkEnter(event) {
      //   console.log(event.keyCode)
      if (event.keyCode === 13) {
        this.doSearch()
      }
    }
  }
}
</script>
