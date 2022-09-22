<template>
  <div>2222hello2221112xxkkkx000222111</div>
</template>

<script>
export default {
  name: 'App',
  components: {},
  data() {
    return {}
  },
  computed: {},
  watch: {},
  created() {},
  mounted() {
    let arrayLike = {
      0: 'a',
      1: 'b',
      2: 'c',
      length: 3
    }


    // ES5的写法
    var arr1 = [].slice.call(arrayLike) // ['a', 'b', 'c']
    console.log("🚀 ~ file: App.vue ~ line 29 ~ mounted ~ arr1", arr1);

    // ES6的写法
    let arr2 = Array.from(arrayLike) // ['a', 'b', 'c']
    console.log("🚀 ~ file: App.vue ~ line 33 ~ mounted ~ arr2", arr2);
  },
  methods: {}
}
</script>

<style lang="less" scoped></style>
