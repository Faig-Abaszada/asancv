<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light bg-light w-100">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="@/assets/logo.png" alt="" width="100">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
          <ul class="navbar-nav text-right">
            <router-link class="btn create-btn" to="/createcv">CV yarat</router-link>
            <li class="nav-item">
              <router-link to="/" class="nav-link active" aria-current="page">Ana Səhifə</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/about" class="nav-link active" aria-current="page">Haqqımızda</router-link>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link active dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Xidmətlər
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Layilərimiz</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Əlaqə</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>

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

</style>
