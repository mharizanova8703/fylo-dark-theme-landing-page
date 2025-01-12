<template>
  <div>
    <q-layout view="lHh lpr lFf" container style="height: 100px"  class="q-pa-lg">
      <q-header elevated>
        <q-toolbar>
          <img class="q-pa-md logo" src="/public/logo.png" />
          <q-toolbar-title></q-toolbar-title>
          <q-btn flat  label="Features" />
          <q-btn flat label="Team" />
          <q-btn flat label="SIgn In" />
        </q-toolbar>
      </q-header>
    </q-layout>
  </div>
</template>

<script setup>
defineOptions({
  name: "EssentialLink",
});

const props = defineProps({
  title: {
    type: String,
    required: true,
  },

  caption: {
    type: String,
    default: "",
  },

  link: {
    type: String,
    default: "#",
  },

  icon: {
    type: String,
    default: "",
  },
});
</script>
<style scoped>
.logo{
  width: 150px;
}
@media (max-width: 768px) {
  .logo{
    width: 100px;
  }
}
</style>