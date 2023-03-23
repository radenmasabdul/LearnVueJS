<template>
  <h1 class="text-red-700 text-4xl text-center">Hello Vue JS</h1>

  <!-- data -->
  <!-- <h2 class="text-center text-xl">Nama : {{ nama }}</h2> -->

  <!-- method -->
  <!-- <div class="flex justify-center">
    <button @click="changeName" class="btn btn-info btn-sm text-white rounded">
      Change Name
    </button>
  </div> -->

  <!-- data binding -->
  <div class="flex justify-center">
    <button class="btn btn-info btn-sm text-white rounded">
      <a :href="url">Go To My Website</a>
    </button>
  </div>
</template>

<!-- data & method -->
<!-- <script>
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
</script> -->

<!-- data binding -->
<script>
export default {
  name: "App",
  data() {
    return {
      url: "https://radenmasabdul.my.id",
    };
  },
};
</script>
