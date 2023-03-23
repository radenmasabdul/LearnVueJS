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
  <!-- <div class="flex justify-center">
    <button class="btn btn-info btn-sm text-white rounded">
      <a :href="url">Go To My Website</a>
    </button>
  </div> -->

  <!-- two ways data binding -->
  <!-- <div class="flex justify-center">
    <input
      v-model="nama"
      type="text"
      placeholder="Type here"
      className="input input-bordered input-info w-full max-w-xs"
    />
    <div class="flex items-center mx-2">
      <p class="text-lg text-red-700">
        {{ nama }}
      </p>
    </div>
  </div> -->

  <!--loops -->
  <!-- <div className="overflow-x-auto">
    <table className="table table-zebra w-full">
      <thead>
        <tr>
          <th>No</th>
          <th>Product</th>
          <th>Prices</th>
        </tr>
      </thead>
      <tbody v-for="item in products" key="item.id">
        <tr>
          <th>{{ item.id }}</th>
          <td>{{ item.title }}</td>
          <td>{{ item.prices }}</td>
        </tr>
      </tbody>
    </table>
  </div> -->

  <!-- conditional -->
  <!-- <div v-if="products.length">
    <div className="overflow-x-auto">
      <table className="table table-zebra w-full">
        <thead>
          <tr>
            <th>No</th>
            <th>Product</th>
            <th>Prices</th>
          </tr>
        </thead>
        <tbody v-for="item in products" key="item.id">
          <tr>
            <th>{{ item.id }}</th>
            <td>{{ item.title }}</td>
            <td>{{ item.prices }}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
  <div v-else class="alert alert-error shadow-lg">
    <p class="text-white">No Data Found</p>
  </div> -->

  <!-- lifecycle hooks -->
  <!-- <div className="overflow-x-auto">
    <table className="table table-zebra w-full">
      <thead>
        <tr>
          <th>No</th>
          <th>Product</th>
          <th>Prices</th>
        </tr>
      </thead>
      <tbody v-for="item in products" key="item.id">
        <tr>
          <th>{{ item.id }}</th>
          <td>{{ item.title }}</td>
          <td>{{ item.prices }}</td>
        </tr>
      </tbody>
    </table>
  </div> -->
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
<!-- <script>
export default {
  name: "App",
  data() {
    return {
      url: "https://radenmasabdul.my.id",
    };
  },
};
</script> -->

<!-- two ways data binding -->
<!-- <script>
export default {
  name: "App",
  data() {
    return {
      nama: "",
    };
  },
};
</script> -->

<!--loops -->
<!-- <script>
export default {
  name: "App",
  data() {
    return {
      products: [
        { id: 1, title: "Product 1", prices: 10000 },
        { id: 2, title: "Product 2", prices: 15000 },
        { id: 3, title: "Product 3", prices: 20000 },
        { id: 4, title: "Product 4", prices: 25000 },
        { id: 5, title: "Product 5", prices: 30000 },
      ],
    };
  },
};
</script> -->

<!-- conditonal -->
<!-- <script>
export default {
  name: "App",
  data() {
    return {
      products: [],
    };
  },
};
</script> -->

<!--lifecycle hooks -->
<!-- <script>
export default {
  name: "App",
  data() {
    return {
      products: [],
    };
  },
  beforeCreate() {
    console.log("Before Create");
  },
  created() {
    this.products = [
      { id: 1, title: "Product 1", prices: 10000 },
      { id: 2, title: "Product 2", prices: 15000 },
      { id: 3, title: "Product 3", prices: 20000 },
      { id: 4, title: "Product 4", prices: 25000 },
      { id: 5, title: "Product 5", prices: 30000 },
    ];
  },
  beforeMount() {
    console.log("Before Mount");
  },
  mounted() {
    console.log("Mounted");
  },
};
</script> -->
