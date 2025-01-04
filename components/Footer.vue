<template>
  <div class="container-fluid bg-secondary">
    <div class="row p-5">
      <div class="col-md-4">
        <h3>Hubungi Kami</h3>
        <h4 class="mt-5">SMKN 4 Tasikmalaya</h4>
        <address>
          Jl Depok Kel. Sukamenak Kec. Purbaratu <br />
          Kota Tasikmalaya 46196.
        </address>
        <div class="d-flex">
          <i class="bi bi-telephone-fill fs-3"></i>
          <h5 class="mt-2">+62265312059</h5>
        </div>
        <div class="d-flex">
          <i class="bi bi-envelope-fill fs-3"></i>
          <h5 class="mt-2"><NuxtLink to="mailto:info@smkn4-tsm.sch.id">info@smkn4-tsm.sch.id</NuxtLink></h5>
        </div>
      </div>
      <!-- <a
        href="https://www.facebook.com/4smkn/"
        target="_blank"
        ><i class="bi bi-facebook"></i
      ></a>
      <a
        href="https://www.instagram.com/smkn4tsmofficial?igsh=N3k1MTlyeXo4cW9q"
        target="_blank"
        ><i class="bi bi-instagram"></i
      ></a>
      <a
        href="https://www.tiktok.com/@smkn4tasikmalaya?is_from_webapp=1&sender_device=pc"
        target="_blank"
        ><i class="bi bi-tiktok"></i
      ></a>
      <a
        href="https://www.youtube.com/@smkn4tasikmalayamediaoffic704"
        target="_blank"
        ><i class="bi bi-youtube"></i
      ></a> -->
      <!-- <div class="d-flex sosmed">
        <a
          href="https://www.facebook.com/4smkn/"
          target="_blank"
          ><i class="bi bi-facebook"></i
        ></a>
        <a
          href="https://www.instagram.com/smkn4tsmofficial?igsh=N3k1MTlyeXo4cW9q"
          target="_blank"
          ><i class="bi bi-instagram"></i
        ></a>
        <a
          href="https://www.tiktok.com/@smkn4tasikmalaya?is_from_webapp=1&sender_device=pc"
          target="_blank"
          ><i class="bi bi-tiktok"></i
        ></a>
        <a
          href="https://www.youtube.com/@smkn4tasikmalayamediaoffic704"
          target="_blank"
          ><i class="bi bi-youtube"></i
        ></a>
      </div> -->
      <div class="col-md-4">
        <h3>Media Sosial</h3>
        <div class="sosial-media">
          <div class="sosial-item mt-5">
            <i class="bi bi-facebook fs-3"></i>
            <NuxtLink to="https://www.facebook.com/4smkn/"><h5 class="mt-2">Facebook</h5></NuxtLink>
          </div>
          <div class="d-flex">
            <i class="bi bi-instagram fs-3"></i>
            <NuxtLink to="https://www.instagram.com/smkn4tasikmalaya/">
              <h5 class="mt-2">Instagram</h5>
            </NuxtLink>
          </div>
          <div class="d-flex">
            <i class="bi bi-youtube fs-3"></i>
            <NuxtLink to="https://youtube.com/">
              <h5 class="mt-2">Youtube</h5>
            </NuxtLink>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <h3>Link lainnya</h3>
        <ul class="list-group mt-5">
          <li class="list-group-item">
            <NuxtLink to="https://kemdikbud.go.id">Kemdikbud</NuxtLink>
          </li>
          <li class="list-group-item">
            <NuxtLink to="https://jabarprov.go.id">Jabar Prov.</NuxtLink>
          </li>
          <li class="list-group-item">
            <NuxtLink to="https://disdik.jabarprov.go.id">Disdik Jabar</NuxtLink>
          </li>
          <li class="list-group-item">
            <NuxtLink to="https://guru.kemdikbud.go.id">PMM</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
    <div class="row copyright">
      <div class="col">
        <p class="text-center mt-2">SMKN 4 Tasikmalaya, All right reserved</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
a {
  text-decoration: none;
  color: #fff;
}

h3,
h4,
address,
i,
h5,
.list-group-item,
p {
  color: white;
}

h5 {
  margin-left: 10px;
}

.list-group-item {
  border: none;
  background-color: transparent;
  font-size: 20px;
}

.copyright {
  background-color: black;
}

.sosial-media {
  display: flex;
  flex-direction: column;
}

.sosial-item {
  display: flex;
  align-items: center;
}
</style>
