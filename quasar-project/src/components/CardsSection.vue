<template>
  <div>
    <q-layout class="q-pa-lg">
      <div class="row q-col-gutter-md items-center justify-center">
        <div class="col-12 col-md-3 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <p>
                Fylo has improved our team productivity by an order of
                magnitude. Since making the switch our team has become a
                well-oiled collaboration machine.
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
                Fylo has improved our team productivity by an order of
                magnitude. Since making the switch our team has become a
                well-oiled collaboration machine.
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
                Fylo has improved our team productivity by an order of
                magnitude. Since making the switch our team has become a
                well-oiled collaboration machine.
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
        <div class="col-12 col-md-8 col-lg-8 q-mx-auto items-center">
          <q-card class="my-card text-white ">
            <q-card-section>
              <h3 class="text-h4 text-bold raleway-bold">
                Get early access today
              </h3>
              <p class="text-body2 raleway-regular items-center">
                It only takes a minute to sign up and our free starter tier is
                extremely generous. If you have any questions, our support team
                would be happy to help you.
              </p>
              <div class="row q-mt-lg">
                <div class="col-lg-7 col-12">
                  <q-input
                    class="custom-input "
                    outlined
                    rounded
                    v-model="email"
                    placeholder="Enter your email"
                    :error="emailError"
                    :error-message="errorMessage"
                  />
                </div>
                <div class="col-lg-4 col-12">
                  <q-btn
                    class="q-ml-sm text-h6 text-body1 text-capitalize raleway-bold"
                    rounded
                    color="info"
                    label="Get Started For Free"
                    @click="validateEmail"
                  />
                </div>
              </div>
              <p v-if="errorMessage" class="text-negative text-body2 q-mt-sm">
                {{ errorMessage }}
              </p>
            </q-card-section>
          </q-card>
        </div>
      </div>
    </q-layout>
  </div>
</template>
<script>
export default {
  data() {
    return {
      email: "",
      emailError: false,
      errorMessage: "",
    };
  },
  methods: {
    validateEmail() {
      const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
      if (!emailPattern.test(this.email)) {
        this.emailError = true;
        this.errorMessage = "Error, please check your email";
      } else {
        this.emailError = false;
        this.errorMessage = "";
        console.log("Email submitted:", this.email);
      }
    },
  },
};
</script>
<style scoped>
div {
  text-align: center;
}
img {
  width: 40px;
}
h3 {
  color: white;
}
.get-started {
  border-radius: 1.3rem;
  width: 200px;
}
.section-card {
  display: flex;
}
.my-card {
  background-color: #202a3c;
}
p {
  color: white;
  text-align: start;
}
.my-card {
  background-color: #1c2331;
  color: #fff;
  padding: 20px;
  border-radius: 8px;
}
.custom-input .q-field {
  background-color: white !important; /* Set the input background color */
  border: 1px solid #ccc !important; /* Add a border for visibility */
  border-radius: 8px; /* Make it rounded */
  color: black; /* Ensure text color is readable */
}

/* Target the control area where text is entered */
.custom-input .q-field__control {
  background-color: transparent !important; /* Prevent nested backgrounds */
  color: black !important; /* Ensure text is black */
}

/* Target the placeholder for styling */
.custom-input .q-placeholder {
  color: #888 !important; /* Light gray placeholder color */
}

/* Handle focus state for input */
.custom-input .q-field--focused {
  border-color: #007bff !important; /* Blue border on focus */
  box-shadow: 0 0 5px rgba(0, 123, 255, 0.5); /* Subtle glow */
}

</style>
