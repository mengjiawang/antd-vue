<template>
  <div class="about">
    <h1>This is an about page</h1>
    <a-button type="primary" @click="getNum"> Primary </a-button>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  created() {},
  mounted() {},
  methods: {
    getNum() {
      const a = 10;
      console.log("🚀 ~ file: AboutView.vue ~ line 18 ~ getNum ~ a", a)
    }
  }
}
</script>
