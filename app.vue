<template>
  <div>
    <header class="side">
      <img class="logo" src="~/assets/img/logo.png">
      <div class="item">
        <img class="item__img" src="~/assets/img/home.png" alt="">
        <p class="item__txt">
          <NuxtLink id="index" to="/">
            ホーム
          </NuxtLink>
        </p>
      </div>
      <div class="item">
        <img class="item__img" src="~/assets/img/logout.png" alt="">
        <button class="item__logout">
          ログアウト
        </button>
      </div>
    </header>
    <section class="content">
      <div class="text__box">
        <p class="text__ttl">
          シェア
        </p>
        <textarea class="text__input" name="message"></textarea>
        <button type="button" class="text__btn">
          シェアする
        </button>
      </div>
      <NuxtPage />
    </section>
  </div>
</template>

<style>
body {
  background-color: #14202B;
}

header {
  background-color: transparent;
}

.content {
  display: flex;
  height: 100%;
}

.item__logout {
  background-color: transparent;
  border: none;
  font-size: 14px;
  color: #fff;
}

#index {
  text-decoration: none;
  color: #fff;
}

.side {
  margin-left: 10px;
  width: 250px;
}

.logo {
  width: 100px;
}

.item {
  display: flex;
  margin-bottom: 10px;
}

.item__img {
  width: 20px;
  height: 20px;
}

.item__txt {
  margin: 0;
  color: #fff;
  font-size: 14px;
  margin-left: 10px;
  line-height: 25px;
}

.text__ttl {
  color: #fff;
}

.text__box {
  width: 100%;
  max-width: 250px;
}

.text__input {
  width: 100%;
  height: 100px;
  background-color: transparent;
  border: 1px solid #fff;
  border-radius: 6px;
  resize: none;
  color: #fff;
  padding: 5px 10px;
}

.text__btn {
  display: block;
  margin-left: auto;
  color: #fff;
  background-color: #5419DA;
  height: 35px;
  width: 90px;
  border-radius: 999px;
  font-size: 12px;
}
</style>
