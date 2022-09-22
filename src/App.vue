<template>
  <div>
    <span>hello Vu1e</span>
    <base-name></base-name>
  </div>
  
</template>

<script>
import baseName from './base.vue';
export default {
  name: 'App',
  components: {baseName},
  data() {
    return {}
  },
  computed: {},
  watch: {},
  created() {},
  mounted() {
    console.log("🚀 ~ file: App.vue ~ line 21 ~ mountcccessssd sssssss~ ssssssmossssuntedddd")
    let arrayLike = {
      0: 'a',
      1: 'b',
      2: 'c',
      length: 3
    }


    // ES5的写法
    var arr1 = [].slice.call(arrayLike) // ['a', 'b', 'c']
    console.log("🚀 ~ file: App.vue ~ line 29 ~ mounted ~ arr1", arr1)

    // ES6的写法
    let arr2 = Array.from(arrayLike) // ['a', 'b', 'c']
    console.log("🚀 ~ file: App.vue ~ line 33 ~ mounted ~ arr2", arr2)
  },
  methods: {}
}
</script>

<style lang="less" scoped></style>
