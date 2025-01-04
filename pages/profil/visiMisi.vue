<template>
  <div class="container-fluid">
    <div class="mt-5">
      <div class="row cover">
        <div class="col">
          <h2 class="text-center">Visi & Misi</h2>
        </div>
      </div>
      <div class="card mt-4 mb-5">
        <div class="row m-3">
          <div class="col-md-5">
            <div class="m-3">
              <h2>Visi</h2>
              <p class="fw-semibold">
                "TERWUJUDNYA LULUSAN YANG CERDAS, AKTIF, KOMPETITIF, ADAPTIF, DAN PRODUKTIF BERLANDASKAN IMAN DAN TAKWA" <br />
                "(CAKAP BERIMTAK)"
              </p>
            </div>
          </div>
          <div class="col-md-7">
            <div class="m-3">
              <h2>Misi</h2>
              <p>
                1.Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill. <br />
                2.Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif. <br />
                3.Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima. <br />
                4.Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non akademik. <br />
                5.Menyelenggarakan berbagai program kegiatan dalam upaya meningkatkan Sumber Daya Manusia yang mampu menyesuaikan dengan perkembangan. <br />
                6.Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah menumbuhkembangkan daya kreasi dan inovasi untuk menghasilkan produk teknologi tepat guna. <br />
                7.Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri. <br />8.Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.
                <br />
                9.Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'Visi Misi',
  meta: [
    {
      name: 'description',
      content: 'halaman Visi Misi',
    },
  ],
});
</script>

<style scoped>
.container-fluid {
  margin-top: 95px;
}

.cover h2 {
  color: white;
  margin-top: 140px;
}

.cover {
  background-image: url('~/assets/img-guru.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 350px;
}

p {
  font-size: 20px;
}
</style>
