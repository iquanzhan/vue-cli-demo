# vue-cli-demo

### 安装

```
npm install -g vue-cli
```

### 快速搭建一个webpack的项目

```
vue init webpack
```

### .vue组件结构

```
<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "App" //导出的默认名称
};
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
```

