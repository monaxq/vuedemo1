<template>
    <el-aside width="200px" style="background-color: rgb(238, 241, 246)">
      <el-menu :default-openeds="['1']">
        <el-submenu index="1">
          <template slot="title"><i class="el-icon-message"></i>我的资料</template>
          <el-menu-item-group>
            <el-menu-item index="1-1">账户总览</el-menu-item>
            <el-menu-item index="1-2">用户资料</el-menu-item>
            <el-menu-item index="1-2">账户资料</el-menu-item>
          </el-menu-item-group>
        </el-submenu>
        <el-submenu index="2">
          <template slot="title"><i class="el-icon-menu"></i>推广中心</template>
          <el-menu-item-group>
            <el-menu-item index="1-1">我的直客</el-menu-item>
            <el-menu-item index="1-2">下级代理</el-menu-item>
            <el-menu-item index="1-2">佣金明细</el-menu-item>
          </el-menu-item-group>
        </el-submenu>
        <el-submenu index="3">
          <template slot="title"><i class="el-icon-setting"></i>账户管理</template>
          <el-menu-item-group>
            <el-menu-item index="3-1">开立账户</el-menu-item>
          </el-menu-item-group>
        </el-submenu>
        <el-submenu index="4">
          <template slot="title"><i class="el-icon-setting"></i>其他管理</template>
          <el-menu-item-group>
            <el-menu-item index="3-1">相关链接</el-menu-item>
          </el-menu-item-group>
        </el-submenu>

      </el-menu>
    </el-aside>
</template>

<script>
    export default {
        name: "Menu"
    }
</script>

<style scoped>

</style>
