<template>
  <div>
    <q-layout class="q-pa-lg">
      <div class="row q-col-gutter-md items-center justify-center">
        <div class="col-12 col-md-3 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <p>
                Fylo has improved our team productivity by an order of magnitude. Since
                making the switch our team has become a well-oiled collaboration machine.
              </p>
              <div class="section-card">
                <img src="/public/img-3.svg" />
                <div class="q-ml-md">
                  <p class="q-mb-none">Satish Patel</p>
                  <p>Founder & CEO, Huddle</p>
                </div>
              </div>
            </q-card-section>
          </q-card>
        </div>
        <div class="col-12 col-md-3 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <p>
                Fylo has improved our team productivity by an order of magnitude. Since
                making the switch our team has become a well-oiled collaboration machine.
              </p>
              <div class="section-card">
                <img src="/public/img-2.svg" />
                <div class="q-ml-md">
                  <p class="q-mb-none">Bruce McKenzie</p>
                  <p>Founder & CEO, Huddle</p>
                </div>
              </div>
            </q-card-section>
          </q-card>
        </div>
        <div class="col-12 col-md-3 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <p>
                Fylo has improved our team productivity by an order of magnitude. Since
                making the switch our team has become a well-oiled collaboration machine.
              </p>
              <div class="section-card">
                <img src="/public/img-1.svg" />
                <div class="q-ml-md">
                  <p class="q-mb-none">Iva Boyd</p>
                  <p>Founder & CEO, Huddle</p>
                </div>
              </div>
            </q-card-section>
          </q-card>
        </div>
      </div>
       <div class="row q-col-gutter-md items-center q-mt-lg justify-center">
        <div class="col-12 col-md-8 col-lg-8">
          <q-card class="my-card">
            <q-card-section>
              <h3 class="">
              Get early access today
              </h3>
             <p>It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you.</p>
             <div class="col-lg8">
                    <q-input rounded outlined v-model="text" label="Rounded outlined" />
                     <q-btn class="glossy" rounded color="info" label="Glossy Rounded" />
             </div>
            </q-card-section>
          </q-card>
        </div>
      </div>

    </q-layout>
  </div>
</template>

<style scoped>
div {
  text-align: center;
}
img{
    width: 40px;
}
.get-started {
  border-radius: 1.3rem;
  width: 200px;
}
.section-card{
    display: flex;
}
.my-card{
    background-color: 
    #202A3C;
}
p {
  color: white;
  text-align: start;
}
</style>
