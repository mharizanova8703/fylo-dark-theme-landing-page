<template>
  <div>
    <q-layout class="q-pa-lg section">
      <div class="row q-col-gutter-md items-center justify-center">
        <div class="col-12 col-md-6 col-lg-4">
          <div class="q-mx-auto">
            <q-img
              class="main-img"
              src="/public/monitor-dektop.png"
              fit="contain"
            />
          </div>
          <div class="">
            <h3 class="text-white text-h5 vertical-middle text-center raleway-bold q-mb-sm">
              Access your files, anywhere
            </h3>
            <p class="text-white text-center text-body1">
              The ability to use a smartphone, tablet, or computer to access
              your account means your files follow you everywhere.
            </p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="q-mx-auto">
            <q-img
              class="main-img"
              src="/public/check-mark.png"
              fit="contain"
            />
          </div>
          <div>
            <h3 class="text-white text-h5 vertical-middle text-center raleway-bold q-mb-sm">
              Security you can trust.
            </h3>
            <p class="text-white text-center text-body1">
              Fylo stores all your most important files in one secure location.
              Access them wherever you need, share and collaborate with friends
              family, and co-workers.
            </p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-5">
          <div class="q-mx-auto">
            <q-img
              class="main-img"
              src="/public/clock.png"
              fit="contain"
            />
          </div>
          <div>
            <h3 class="text-white text-h5 vertical-middle text-center raleway-bold q-mb-sm">
              Real-time collaboration
            </h3>
            <p class="text-white text-center text-body1">
              Securely share files and folders with friends, family and
              colleagues for live collaboration. No email attachments required.
            </p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="q-mx-auto">
            <q-img
              class="main-img"
              src="/public/files.png"
              fit="contain"
            />
          </div>
          <div>
            <h3 class="text-white text-h5 raleway-bold vertical-middle text-center q-mb-sm">
              Store any type of file
            </h3>
            <p class="text-white text-center text-body1">
              Whether you're sharing holidays photos or work documents, Fylo has
              you covered allowing for all file types to be securely stored and
              shared.
            </p>
          </div>
        </div>
      </div>
    </q-layout>
  </div>
</template>

<style scoped>
div {
  text-align: center;
  background-color: var(--q-primary);
}
.main-img {
  width: 110px;
}
.get-started {
  border-radius: 1.3rem;
  width: 200px;
}
.section{
  min-height: 100%!important;
}
</style>
