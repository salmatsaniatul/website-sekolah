<template>
  <div class="container-fluid">
    <!--Sejarah-->
    <div class="row cover">
      <div class="col">
        <h2 class="text-center">Sejarah Sekolah</h2>
      </div>
    </div>
    <div class="card m-3">
      <div class="row m-3">
        <div class="col">
          <p class="mt-3">
            Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan pada saat itu yakni pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya SMK Negeri di daerah Kecamatan Purbaratu
            Kota Tasikmalaya, terutama untuk menampung tamatan dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota
            Tasikmalaya dan Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
          </p>
          <p>
            Setelah melalui perjuangan yang sangat panjang dari berbagai pihak khususnya Disdik Kota Tasikmalaya dan pihak-pihak terkait lainnya sesuai prosedur dan ketentuan yang berlaku pada waktu itu dengan mengucapkan syukur
            Alhamdulillah akhirnya pada tahun pelajaran 2010/2011 SMK Negeri 4 Tasikmalaya mulai berdiri, pada awalnya membuka Kompetensi Keahlian Teknik Komputer dan Jaringan dengan pendaftar peserta Didik Baru pada waktu itu berjumlah 44
            orang. Pada awalnya tempat belajar menumpang di SMP Negeri 17 Kota Tasikmalaya, dan sekolah induknya adalah SMK Negeri 2 Kota Tasikmalaya, Untuk Tenaga pendidik dan Tenaga Kependidikan masih dibantu sepenuhnya oleh kedua sekolah
            tersebut.
          </p>
          <p>Pada tahun 2012 keluarlah surat Izin Pendirian berdasarkan keputusan kepala Badan Pelayanan Perizinan Terpadu Kota Tasikmalaya No. 420/9/SK-BPPT/2012 Tanggal 06 Februari 2012.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'Sejarah',
  meta: [
    {
      name: 'description',
      content: 'halaman sejarah',
    },
  ],
});
</script>

<style scoped>
.container-fluid {
  margin-top: 95px;
}

h2 {
  color: white;
  margin-top: 140px;
}

p {
  font-size: 20px;
}

.cover {
  background-image: url('~/assets/img-guru.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 350px;
}
</style>
