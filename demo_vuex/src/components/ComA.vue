<template>
  <div id="ComA"><h2>{{$store.state.count}}</h2></div>
</template>

<script>
export default {
name:"ComA",
  mounted() {
    setInterval(() => {
      this.$store.state.count--;
      100;
    });
  },
}
</script>

<style>

</style>