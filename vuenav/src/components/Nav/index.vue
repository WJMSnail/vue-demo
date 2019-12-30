<template>
    <div class="nav">
        <ul>
            <router-link to="/home">
                <i class="iconfont icon-shouye"></i>
                <span class="title">首页</span>
            </router-link>
            <router-link to="/order">
                <i class="iconfont icon-wodedingdan"></i>
                <span class="title">订单</span>
            </router-link>
            <router-link to="/shopcar">
                <i class="iconfont icon-gouwuche"></i>
                <span class="title">购入车</span>
            </router-link>
            <router-link to="/mine">
                <i class="iconfont icon-wodejuhuasuan"></i>
                <span class="title">我的</span>
            </router-link>
        </ul>
    </div>
</template>

<script>
import "../../assets/iconfont.css"

export default {
    name:"mynav",
    data(){
        return{
            
        }
    }
}
</script>

<style scoped>


.nav{
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  height: 40px;
  padding: 10px;
  background: #fff;
}

.nav ul{
  height: 40px;
  width: 100%;
  display: flex;

}

.nav ul a{
  text-align: center;
  flex: 1;
}

.nav ul a i{
  font-size: 20px;
} 

.title{
  display: block;
  margin-top: 8px;
  font-size: 12px;
}

.active{
  color: #39ac69;
}


</style>