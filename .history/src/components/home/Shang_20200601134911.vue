<template>
  <div>
    <div class="lbw">
      <div class="box">
        <div class="box-1">
          <img
            src="https://static.shiyanlou.com/frontend/dist/img/9f43b00.svg"
            alt="实验楼"
            class="logo"
            data-v-7629dae3=""
            width="160px"
            height="110px"
          />
          <div class="hn1">做实验，学编程</div>
          <div class="b11-1">
            <div class="hn3">企业版</div>
            <div class="hn2"></div>
            <div class="hn3">学校版</div>
            <div class="hn4">登录</div>
            <div class="hn5">注册</div>
          </div>
        </div>
        <div class="box-2">
          <div><img src="./11.png" alt="" height="80px" /></div>
          <div>路径</div>
          <div>训练营</div>
          <div>楼+</div>
          <div>会员</div>
          <div>社区</div>
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

<style scoped>
* {
  padding: 0;
  margin: 0;
}
.lbw {
  width: 100%;
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
  height: 120px;
  background: transparent;
  display: flex;
  width: 100%;
  align-items: center;
  position: relative;
}
.hn1 {
  font-size: 20px;
}
.b11-1 {
  display: flex;
  align-items: center;
  position: absolute;
  right: 0;
}
.hn2 {
  width: 1px;
  height: 16px;
  background: rgb(153, 153, 153);
  margin: 10px;
}
.hn3 {
  color: rgb(153, 153, 153);
  font-size: 14px;
}
.hn3:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
.hn4 {
  font-size: 16px;
  color: rgb(8, 191, 145);
  margin-left: 16px;
}
.hn4:hover {
  color: rgb(5, 118, 156);
}
.hn5 {
  width: 70px;
  height: 40px;
  background: rgb(8, 191, 145);
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  margin-left: 12px;
  font-size: 16px;
  cursor: pointer;
}
.box-2 {
  width: 100%;
  height: 80px;
  background: white;
  display: flex;
  position: relative;
  align-items: center;
}
</style>
