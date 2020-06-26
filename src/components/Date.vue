<template>
  <div></div>
</template>

<script>
export default {
  data() {
    return {
      sDate: new Date(),
      eDate: new Date()
    };
  },

  mounted() {
    this.sDate.setMonth(this.eDate.getMonth() - 3);
  },

  methods: {}
};
</script>

<style>
</style>
