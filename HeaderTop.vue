<template>
  <header>
    <div class="left">
      <div class="menu">
        <Icon name="el:lines" size="48"/>
        <span class="coupon"></span>
      </div>

      <div class="logo"></div>
      <div class="search"></div>
    </div>

    <div class="right">
      <div href="#" class="login"></div>
      <div href="#" class="like"></div>
      <div href="#" class="cart"></div>
    </div>
  </header>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped>
header {
  display: flex;
  justify-content: space-between;
}

.left {
  display: flex;
}

.right {
  display: flex;
}

.menu {
  width: 100px;
  height: 100px;
  margin-left: 42px;
  background-color: aqua;
}

.coupon {
  position: absolute;
  top: 3px;
  left: calc(100px - 8px);
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background-color: #c71047;

  
  @media screen and (max-width: 600px) {
    top: 1px;
    left: calc(100px - 11px);
  }
}
.logo {
  width: 200px;
  height: 100px;
  margin-left: 12px;
  background-color: pink;
}
.search {
  width: 400px;
  height: 100px;
  margin-left: 42px;
  background-color: skyblue;
}
.login {
  width: 100px;
  height: 100px;

  background-color: beige;
}
.like {
  width: 100px;
  height: 100px;
  background-color: darkcyan;
}

.cart {
  width: 100px;
  height: 100px;
  background-color: darkgray;
}
</style>
