<script setup lang="ts"></script>
<template>
  <div class="main-header">
    <b-nav class="navbar navbar-expand-lg">
      <div>
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >고객센터</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">관심상품</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">마이페이지</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#">로그인</a>
            </li>
          </ul>
        </div>
      </div>
    </b-nav>
    <hr />
    <b-nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <span>KREAM</span>
        </a>
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Style</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Shop</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">검색아이콘</a>
            </li>
          </ul>
        </div>
      </div>
    </b-nav>
    <div class="main-header">
      <div class="header-contents"></div>
    </div>
  </div>
</template>
<style scoped>
.main-header {
  /* position: fixed; */
  top: 0;
  left: 0;
  right: 0;
  z-index: 0;
  background-color: #fff;
}
.navbar-nav {
  float: left;
}
</style>
