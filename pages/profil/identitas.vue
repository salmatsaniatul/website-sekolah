<template>
  <div class="container-fluid">
    <div class="row cover">
      <div class="col">
        <h2 class="text-center">Identitas Sekolah</h2>
      </div>
    </div>

    <!-- <div class="card mt-4 mb-5">
      <div class="row m-3">
        <div class="col-md-6">
          <div class="m-3">
            <h5>Nama Sekolah</h5>
            <p>SMK Negeri 4 Tasikmalaya</p>
          </div>
        </div>
        <div class="col-md-6">
          <div class="m-3">
            <h5>NPSN</h5>
            <p>20276063</p>
          </div>
        </div>
      </div>
      <div class="row m-3">
        <div class="col-md-6">
          <div class="m-3">
            <h5>Nomor Statistik Sekolah</h5>
            <p>401327810004</p>
          </div>
        </div>
        <div class="col-md-6">
          <div class="m-3">
            <h5>Alamat</h5>
            <p>Jalan Depok RT 02 RW 05</p>
          </div>
        </div>
      </div>
      <div class="row m-3">
        <div class="col-md-6">
          <div class="m-3">
            <h5>Telepon</h5>
            <p>08765353525</p>
          </div>
        </div>
        <div class="col-md-6">
          <div class="m-3">
            <h5>Email</h5>
            <p>info@smkn4tsm.sch.id</p>
          </div>
        </div>
      </div>
    </div> -->

    <div class="card shadow mt-5 m-5">
      <table class="table">
        <tbody>
          <tr>
            <td class="fw-semibold">a. Nama Sekolah</td>
            <td>:</td>
            <td>SMK Negeri 4 Tasikmalaya</td>
          </tr>
          <tr>
            <td class="fw-semibold">b. NPSN</td>
            <td>:</td>
            <td>20276063</td>
          </tr>
          <tr>
            <td class="fw-semibold">c. Nomor Statistik Sekolah</td>
            <td>:</td>
            <td>401327810004</td>
          </tr>
          <tr>
            <td class="fw-semibold">d. Alamat</td>
            <td>:</td>
            <td>Jl.Depok RT 02 RW 05, Kel.Sukamenak, Kec.Purbaratu, Kota Tasikmalaya, Provinsi Jawa Barat</td>
          </tr>
          <tr>
            <td class="fw-semibold">e. Tahun Pendirian</td>
            <td>:</td>
          </tr>
          <tr>
            <td class="ms-3">Nomor SK Pendirian</td>
            <td>:</td>
            <td>420/9/SK-BPPT/2012</td>
          </tr>
          <tr>
            <td>Tanggal</td>
            <td>:</td>
            <td>06 Februari 2012</td>
          </tr>
          <tr>
            <td class="fw-semibold">f. Lahan/Bangunan</td>
            <td>:</td>
          </tr>
          <tr>
            <td>Kepemilikan</td>
            <td>:</td>
            <td>Tahun 2010</td>
          </tr>
          <tr>
            <td>Status Tanah</td>
            <td>:</td>
            <td>Sertifikat Hak Milik</td>
          </tr>
          <tr>
            <td>Luas Tanah</td>
            <td>:</td>
            <td>13.229 m2</td>
          </tr>
          <tr>
            <td>Status Bangunan</td>
            <td>:</td>
            <td>Milik Pemerintah</td>
          </tr>
          <tr>
            <td>Luas Bangunan</td>
            <td>:</td>
            <td>2400 m2</td>
          </tr>
          <tr>
            <td>Nomor Rekening</td>
            <td>:</td>
            <td>010001001048306</td>
          </tr>
          <tr>
            <td>Nama Bank</td>
            <td>:</td>
            <td>BRI Cabang Tasikmalaya</td>
          </tr>
        </tbody>
      </table>
      <!-- </div> -->
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'Identitas',
  meta: [
    {
      name: 'description',
      content: 'halaman identitas',
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

.cover {
  background-image: url('~/assets/img-guru.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 350px;
}
</style>
