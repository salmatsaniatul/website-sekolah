<template>
  <div class="container-fluid">
    <h2 class="text-center mt-5">Identitas Kepala Sekolah</h2>
    <div class="row mt-5 justify-content-center">
      <div class="col-md-3 bg-secondary">
        <img
          src="~/assets/kepalasekolah.png"
          alt="kepsek"
          class="rounded"
        />
      </div>
    </div>
    <div class="card shadow mt-5 m-5">
      <table class="table">
        <tbody>
          <tr>
            <td>Nama</td>
            <td>:</td>
            <td>Kurniawan, S.Pd, M.Pd.</td>
          </tr>
          <tr>
            <td>NIP</td>
            <td>:</td>
            <td>19720809 199702 1 002</td>
          </tr>
          <tr>
            <td>Pangkat/Golongan</td>
            <td>:</td>
            <td>Pembina IV/b</td>
          </tr>
          <tr>
            <td>No SK Pengangkatan</td>
            <td>:</td>
            <td>821.2/Kep.373-BKD/2020</td>
          </tr>

          <tr>
            <td>Tanggal Pengangkatan</td>
            <td>:</td>
            <td>10 Juli 2020</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'Kepala Sekolah',
  meta: [
    {
      name: 'description',
      content: 'halaman Kepala Sekolah',
    },
  ],
});
</script>

<style scoped>
.container-fluid {
  margin-top: 120px;
}

img {
  width: 300px;
  margin-left: 20px;
  border-radius: 5px;
}
</style>
