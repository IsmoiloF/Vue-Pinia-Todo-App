<template>
<Header />
  <main class="flex">


    <div class="main bg-indigo-100 min-w-full h-screen mt-[70px] p-8">
      <RouterView />
    </div>
  </main>
</template>

<Footer />
<script>
import Header from "./components/Header/Header.vue";


export default {
  name: "App",
  components: {
    Header,

  },

  data() {
    return {
      toggled: true,
    };
  },

  methods: {
    toogleMenu() {
      this.toggled = !this.toggled;
    },
  },
};
</script>

<style scoped>


</style>
