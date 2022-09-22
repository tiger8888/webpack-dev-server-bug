<template>
  <div>
    <span>hello</span>
    <base-name></base-name>
  </div>
  
</template>

<script>
import baseName from './Sub.vue';
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
    console.log("111")
  },
  methods: {}
}
</script>

<style lang="less" scoped></style>
