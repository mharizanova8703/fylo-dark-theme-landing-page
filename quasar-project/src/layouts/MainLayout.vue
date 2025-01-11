<template>
  <div class="">
    <NavbarMain />
    <div class="q-pa-lg">
      <div class="col-lg-5 col-12 justify-center items-center q-pa-lg">
        <q-img class="main-img" src="/public/main-assets-landing.png" />
        <h3 class="text-white text-h4 vertical-middle raleway-bold">
          All your files in one secure location,<br />
          accessible anywhere.
        </h3>
        <p class="text-white text-body1 q-mb-none">
          Fylo stores all your most important files in one secure location.
        </p>
        <p class="text-white text-body1">
          Access them wherever you need, share and collaborate with friends
          family, and co-workers.
        </p>
        <q-btn
          class="get-started text-capitalize q-pa-sm"
          color=""
          label="Get Started"
        />
      </div>
    </div>
    <IconMain />
    <CardMain />
    <CardsSection />
  </div>
</template>

<script setup>
import { ref } from "vue";
import NavbarMain from "src/components/NavbarMain.vue";
import IconMain from "src/components/IconMain.vue";
import CardMain from "src/components/CardMain.vue";
import CardsSection from "src/components/CardsSection.vue";

defineOptions({
  name: "NavbarMain",
  name: "IconMain",
  name: "CardMain",
    name: "CardsSection",
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
  width: 40%;
}
.get-started {
  border-radius: 1.3rem;
  width: 200px;
  background: linear-gradient(90deg, #63e1d9 0%, #34a0cd 100%);
}
</style>
