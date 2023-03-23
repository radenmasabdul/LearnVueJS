<template>
  <h1 class="text-red-700 text-4xl text-center">Hello Vue JS</h1>

  <!-- data -->
  <h2 class="text-center text-xl">Nama : {{ nama }}</h2>

  <!-- method -->
  <div class="flex justify-center">
    <button @click="changeName" class="btn btn-info btn-sm text-white rounded">
      Change Name
    </button>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      nama: "Abdul Rahman Alhafizh",
    };
  },
  methods: {
    changeName() {
      this.nama = "Raden Mas Abdul";
    },
  },
};
</script>
