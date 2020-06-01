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
          <div class="hn6">路径</div>
          <div class="hn6">训练营</div>
          <div class="hn6">楼+</div>
          <div class="hn6">会员</div>
          <div class="img2">
            <img
              src="https://static.shiyanlou.com/frontend/dist/img/02a4001.svg"
              class="tag"
              data-v-ac00dc36=""
            />
          </div>
          <div class="box3">
            <div class="b3-1">
              <div class="hn8">社区</div>
            </div>
            <div class="box2">
              <div class="hn7">讨论</div>
              <div class="hn7">教程库</div>
              <div class="hn7">直播</div>
              <div class="hn7">比赛</div>
            </div>
          </div>
          <div class="img1">
            <input type="" placeholder=" 搜索 课程/问答" class="ipt1" />
            <i class="i1 iconfont icon-sousuo item3"></i>
          </div>
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
  cursor: pointer;
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
.hn6 {
  font-size: 22px;
  margin-left: 26px;
}
.hn6:hover {
  color: rgb(5, 118, 156);
  cursor: pointer;
}
.img1 {
  position: absolute;
  right: 30px;
}
.ipt1 {
  width: 200px;
  height: 30px;
  border-radius: 6px;
  border: 1px solid;
}
.ipt1:hover {
  border: 1px solid rgb(8, 191, 145);
}
.ipt1:focus {
  outline: none;
  border: 1px solid rgb(8, 191, 145);
}
.hn8 {
  font-size: 22px;
  height: 80px;
  cursor: pointer;
  display: flex;
  align-items: center;
  width: 130px;
}
.hn8:hover {
  color: rgb(8, 191, 145);
}


.hn8:hover ~ none-.box2{
    display: block;
}
.box2 {
  width: 130px;
  height: 200px;
  background: white;
  position: absolute;
  left: 47%;
  display: none;
}

.hn7 {
  width: 130px;
  height: 50px;
  background: white;
  display: flex;
  align-items: center;
  font-size: 14px;
}
.hn7:hover {
  color: rgb(8, 191, 145);
  background: rgb(247, 247, 247);
}

.img2 {
  margin-bottom: 30px;
  margin-left: 5px;
}
.i1 {
  position: absolute;
  right: 10px;
  top: 6px;
  cursor: pointer;
}
</style>
