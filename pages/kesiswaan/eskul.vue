<template>
  <div class="container-fluid">
    <!-- Organisasi -->

    <h2 class="text-center mt-4">Ekstrakurikuler</h2>
    <div class="row mt-3 m-3 justify-content-center">
      <div
        v-for="(eskul, i) in foto"
        :key="i"
        class="col-3 mt-5"
      >
        <div :to="`foto/${eskul.id}`">
          <div class="card">
            <div class="card-body">
              <img
                :src="eskul.foto"
                class="mt-5 m-3"
                alt="foto"
              />
              <h5 class="text-center">{{ eskul?.nama || 'Nama tidak tersedia' }}</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- <h2 class="text-center mt-5">Ekstrakurikuler</h2>
  <div class="row mt-3 m-3 justify-content-center">
    <div
      v-for="(organisasi, i) in foto"
      :key="i"
      class="col-3 mt-5"
    >
      <div :to="`foto/${organisasi.id}`">
        <div class="card">
          <div class="card-body">
            <img
              :src="organisasi.foto"
              alt="foto"
              class="mt-5 m-3"
            />
            <div class="card-body">
              <h5 class="text-center">{{ organisasi?.nama || 'nama tidak tersedia' }}</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div> -->
</template>

<script setup>
useHead({
  title: 'Ekstrakurikuler',
  meta: [
    {
      name: 'description',
      content: 'Halaman Eskul',
    },
  ],
});

const supabase = useSupabaseClient();
const foto = ref([]);

const getData = async () => {
  const { data, error } = await supabase.from('eskul').select('*');
  if (error) {
    console.error('Terjadi kesalahan saat mengambil data:', error);
  } else {
    console.log(data); // Debug: Memastikan data yang diterima
    foto.value = data; // Menyimpan data yang diterima ke dalam foto
  }
};

onMounted(() => {
  getData();
});
</script>

<style scoped>
.container-fluid {
  margin-top: 115px;
}

img {
  width: 185px;
}

.card-body {
  margin: auto;
}
</style>
