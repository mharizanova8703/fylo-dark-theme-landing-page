<template>
  <div class="">
    <NavbarMain />
    <div class="column">
      <div class="col-lg-6 col-12 justify-center items-center q-pa-md">
        <q-img
          class="main-img"
          src="/public/main-assets-landing.png"
          fit="contain"
        />
        <h1 class="text-white text-h3 vertical-middle">
          All your files in one secure location,<br />
          accessible anywhere.
        </h1>
        <p class="text-white">
          Fylo stores all your most important files in one secure location.
          Access them wherever you need, share and collaborate with friends
          family, and co-workers.
        </p>
        <q-btn class="get-started text-uppercase" color="info" label="Get Started" />
      </div>
    </div>
     <IconMain />
  </div>
</template>

<script setup>
import { ref } from "vue";
import NavbarMain from "src/components/NavbarMain.vue";
import IconMain from "src/components/IconMain.vue";

defineOptions({
  name: "NavbarMain",
  name: "IconMain",
});

const leftDrawerOpen = ref(false);

function toggleLeftDrawer() {
  leftDrawerOpen.value = !leftDrawerOpen.value;
}
</script>
<style scoped>
div {
  text-align: center;
  background-color: var(--q-primary);
}
.main-img {
  width: 400px;
}
.get-started {
  border-radius: 1.3rem;
  width: 200px;
}
</style>
