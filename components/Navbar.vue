<template>
  <nav class="navbar navbar-expand-lg bg-primary p-2 fixed-top">
    <div class="container-fluid">
      <img
        src="../assets/logosmk.png"
        alt="logo"
      />
      <h1>SMKN 4 TASIKMALAYA</h1>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse"
        id="navbarNav"
      >
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <nuxt-link
              to="/"
              class="nav-link"
              aria-current="page"
              >Beranda</nuxt-link
            >
          </li>
          <li class="nav-item dropdown">
            <nuxtlink
              to="/profil"
              class="nav-link dropdown-toggle"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Profil
            </nuxtlink>
            <ul class="dropdown-menu">
              <li>
                <nuxt-link
                  to="/profil/sejarah"
                  class="dropdown-item"
                  >Sejarah</nuxt-link
                >
              </li>
              <li>
                <nuxt-link
                  to="/profil/visiMisi"
                  class="dropdown-item"
                  >Visi Misi</nuxt-link
                >
              </li>
              <li>
                <nuxt-link
                  to="/profil/identitas"
                  class="dropdown-item"
                  >Identitas Sekolah</nuxt-link
                >
              </li>
              <li>
                <nuxt-link
                  to="/profil/kepsek"
                  class="dropdown-item"
                  >Kepala Sekolah</nuxt-link
                >
              </li>
            </ul>
          </li>

          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Kesiswaan
            </a>
            <ul class="dropdown-menu">
              <li>
                <nuxt-link
                  to="/kesiswaan/organisasi"
                  class="dropdown-item"
                  >Organisasi</nuxt-link
                >
              </li>
              <li>
                <nuxt-link
                  to="/kesiswaan/eskul"
                  class="dropdown-item"
                  >Ekstrakurikuler</nuxt-link
                >
              </li>
            </ul>
          </li>

          <li class="nav-item">
            <nuxt-link
              to="/galeri"
              class="nav-link"
              >Galeri</nuxt-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.navbar-nav {
  margin-right: 100px;
}

.nav-item {
  margin-right: 30px;
  font-size: 20px;
}

.nav-link,
h1 {
  color: white;
}

img {
  width: 70px;
  margin-left: 50px;
}

h1 {
  margin-left: 15px;
  font-size: 30px;
}
</style>
