<template>
  <div id="app">
    <!-- 3. 使用AppHeader -->
    <app-header></app-header>
    <div class="container-fluid">
      <div class="row">
        <!-- AppSidebar -->
        <app-sidebar></app-sidebar>
       
        <!-- 主内容区域 -->
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>
<script>
//导入组件
import AppHeader from './components/APPHead'
import AppHexport from './components/APPHead'
 
 export default{
   name: 'app',
   //注册组件
   component:{
     AppHeader,
     AppSiddebar,
   }
 }
</script>
<style>

</style>
