<template>
  <div class="row">
    <div class="col-4">
      <h3>選單</h3>
      <div class="list-group">
        <router-link to="/newpage/a" class="list-group-item list-group-item-action">元件A</router-link>
        <router-link to="/newpage/b" class="list-group-item list-group-item-action">元件B</router-link>
        <router-link to="/newpage/dynamic" class="list-group-item list-group-item-action">動態路由</router-link>
      </div>
    </div>
    <div class="col-8">
      <h1>新增頁面</h1>
      <router-view></router-view>
    </div>
  </div>
</template>
