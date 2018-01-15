<template>
  <div class="bg">
    <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light header-bar" style="background-color:white !important;">
      <img src="../static/FITMlogo-01-01.png" style="width:8%"alt="">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="/">หน้าหลัก <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/Detail">รายละเอียดโครงการ</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/">กำหนดการและแบบฟอร์มการสมัคร</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/map">แผนที่สถานที่อบรม</a>
          </li>
        </ul>
        <span class="navbar-text">

        </span>
      </div>
    </nav>
    <div class="container" style="background-color:white; margin-top:5%;">
      <nuxt/>
    </div>
</div>

  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Kanit');
html {

  background-color: #F7F8F8;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
.header-bar {
  box-shadow: 1px 1px 4px 1px rgba(0,0,0,0.1);
}
.bg {
    background-image: url("../static/BG-01-02.jpg");
    background-repeat:repeat;
}
body {
  font-family: 'Kanit', sans-serif;
}
</style>
