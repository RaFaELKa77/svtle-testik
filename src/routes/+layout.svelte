<nav>
  <div class="nav-container">
    <a href="/" class="nav-logo" title="back to homePage">Ksenia Kuzminova</a>
    <div class="nav-links">
      <a href="/about" class="link">Обо мне</a>
      <a href="/blog" class="link">Блог</a>
      <a href="/projects" class="link">Проекты</a>
      <a href="/contact" class="link">Контакты</a>
    </div>
  </div>
</nav>
<div class="conteiner">
  <!--Страницы будут вводиться нииже-->
  <slot />
</div>

<style>
  .conteiner {
    max-width: 1400px;
    margin: 50px auto;
  }
</style>
