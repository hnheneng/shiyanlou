<template>
  <div>
    <div class="lbw w-1">
      <div class="box ">
        <div class="box-1 dis-1 w-1">
            <div><img src="./123.png" alt=""></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
  props: {},
  components: {},
  data() {
    return {};
  },
  methods: {},
  mounted() {},
  watch: {},
  computed: {},
};
</script>

<style scoped lang="scss">
.lbw {
  height: 200px;
  background: rgb(249, 249, 249);
  display: flex;
  align-items: center;
  justify-content: center;
}
.box {
  width: 1400px;
  height: 200px;
  background: transparent;
}
.box-1 {
    height: 130px;
    background: transparent;
}
</style>
