<template>
  <nav class="py-4 navbar navbar-expand-md bg-body-tertiary">
    <div class="container-fluid">
      <div>
        <a class="navbar-brand" href="/">Algorythms&Programming</a>
      </div>
      <div>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0 d-flex flex-fill justify-content-end">
          <li class="nav-item">
            <span class="nav-link"><router-link to="/">Home</router-link></span>
          </li>
          <li class="nav-item">
            <span class="nav-link"><router-link to="/lessons">Lessons</router-link></span>
          </li>
          <li class="nav-item">
            <span class="nav-link"><router-link to="/practice">Practice</router-link></span>
          </li>
          <li class="nav-item">
            <span class="nav-link"><router-link to="/about">About</router-link></span>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Verde: #00FF00 (0 de vermelho, 255 de verde e 0 de azul)
Âmbar: #FFBF00 (255 de vermelho, 191 de verde e 0 de azul)
Branco: #FFFFFF (255 de vermelho, 255 de verde e 255 de azul)
Azul: #0000FF (0 de vermelho, 0 de verde e 255 de azul) -->
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #424eb9;
    }
  }

  
}
</style>
