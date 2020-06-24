<template>
  <div></div>
</template>

<script>
export default {
  data() {
    return {
      sDate: new Date(),
      eDate: new Date(),

      arr: [1, 2, 3],
      num: 4
    };
  },

  mounted() {
    this.sDate.setMonth(this.eDate.getMonth() - 3);

    // console.log(this.sDate);
    // console.log(this.eDate);

    console.log(this.arr.every(this.checkVal));
  },

  methods: {
    checkVal(val) {
      return val !== this.num;
    }
  }
};
</script>

<style>
</style>

