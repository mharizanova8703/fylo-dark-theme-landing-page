<template>
  <div>
    <q-layout class="q-pa-lg section">
      <div class="row q-col-gutter-md items-center justify-center">
        <div class="col-12 col-md-6 col-lg-6">
          <div class="q-mx-auto">
            <q-img class="main-img" src="/public/main-landing.png" fit="contain" />
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 flex  items-start justify-start">
          <div>
            <h3 class="text-white text-h5 raleway-bold vertical-start text-start q-mb-sm">
              Stay productive, wherever you are
            </h3>
            <p class="text-white text-start text-body1">
              Never let location be an issue when accessing your files. Fylo has you
              covered for all of your file storage needs.
            </p>
            <p class="text-white text-start text-body1">
              Securely share files and folders with friends, family and colleagues for
              live collaboration. No email attachments required.
            </p>
            <div class="d-flex">
              <a href="" class="text-info text-body1">
                See how Fylo works
              </a>
               <img class="q-ml-sm" src="/public/btn.svg" />
            </div>
          </div>
        </div>
      </div>
    </q-layout>
  </div>
</template>

<style scoped>
div {
  background-color: var(--q-primary);
}
.main-img {
  width: 100%;
}
.section{
  min-height: 100%!important;
}
.get-started {
  border-radius: 1.3rem;
  width: 200px;
}
.row {
  text-align: start;
}
</style>
