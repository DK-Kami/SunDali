<template>
  <div class="main-header__wrapper">
    <header class="main-header">
      <div class="logo">LIVE</div>
      <nav class="nav">
        <ul class="nav__list">
          <li class="nav__item">
            <a class="nav__link" href="#">news</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#">sports</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#">life</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#">money</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#">tech</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#">travel</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#">opinion</a>
          </li>
          <li class="navigation__item weather">
            <img src="img/weather.png" alt="weather">
            <b>17</b>
          </li>
        </ul>
      </nav>
      <ul class="user-nav">
        <li>
          <button>search</button>
        </li>
        <li>
          <a class="user-nav__subscribe" href="#">Subscribe</a>
        </li>
        <li>
          <a href="#">Sing In</a>
        </li>
      </ul>
    </header>
  </div>
</template>

<script>
export default {
  name: "TheHeaderApp"
};
</script>

<style>
</style>
