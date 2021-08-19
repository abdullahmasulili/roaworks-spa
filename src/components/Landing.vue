<template>
  <div class="fill-height mt-5">
    <section id="landing">
      <v-container>
        <v-row class="d-flex align-center">
          <v-col cols="12" md="6" lg="6" xl="6">
            <h1 class="font-weight-black pr-16 text-1">
              Bayangkan, Bisnis Kamu Diakses Secara Online?
            </h1>
            <br />
            <p class="font-weight-medium pr-16 text-2">
              Kami Bisa Membuatkan Kamu Sebuah Website Sesuai Kebutuhan Yang
              Kamu Mau!
            </p>
            <br />
            <v-btn
              rounded
              x-large
              color="light-blue accent-3"
              style="box-shadow: 2px 2px 20px #0277bd"
              class="white--text"
            >
              <span class="text-capitalize mr-3">Discover Our Work</span>
              <v-icon right large>mdi-arrow-right-bold-circle</v-icon>
            </v-btn>
          </v-col>
          <v-col
            cols="12"
            md="6"
            lg="6"
            xl="6"
            class="d-flex justify-center align-center"
          >
            <v-img
              src="@/assets/landing-pict.png"
              class="pict-1"
              max-width="608"
            ></v-img>
          </v-col>
        </v-row>
      </v-container>
    </section>
    <section id="our-clients" style="height: 358px">
      <v-container>
        <v-row class="fill-height">
          <v-col cols="12" md="4" lg="4" xl="4" class="d-flex align-center">
            <v-row class="flex-column">
              <h1 class="text-3 font-weight-black mx-16">Our Clients</h1>
              <br />
              <p class="mx-16 text-2">
                Roaworks telah dipercayai oleh beberapa perusahaan dalam
                mengembangkan aplikasi
              </p>
            </v-row>
          </v-col>
          <v-col
            cols="12"
            md="8"
            lg="8"
            xl="8"
            class="d-flex align-center justify-center"
          >
            <v-img max-width="705" src="@/assets/clients.png"></v-img>
          </v-col>
        </v-row>
      </v-container>
    </section>
    <section id="our-service" class="mb-16">
      <v-container>
        <v-row>
          <v-col>
            <v-row no-gutters class="d-flex justify-center">
              <h1
                class="font-weight-black"
                style="font-size: 50px; color: #3b434d"
              >
                Our Services
              </h1>
            </v-row>
            <v-row no-gutters class="d-flex justify-center">
              <div
                class=""
                style="
                  height: 8px;
                  width: 96px;
                  background-color: #3fbdf1;
                  border-radius: 15px;
                "
              ></div>
            </v-row>
          </v-col>
        </v-row>
        <v-row class="mt-16">
          <v-col cols="12" md="12" lg="4" xl="4" class="d-flex justify-center">
            <v-card elevation="0">
              <v-img
                class="mx-auto"
                max-width="344"
                src="@/assets/build-web-app.png"
              ></v-img>
              <v-card-text>
                <h1
                  style="font-size: 33px"
                  class="font-weight-bold text-center mb-3"
                >
                  Build Web App
                </h1>
                <br />
                <h2 style="font-size: 18px" class="mx-16 mt-3 text-center">
                  Mengembangkan website premium yang unik dengan tampilan user
                  friendly dan sesuai kebutuhan yang kamu mau.
                </h2>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="12" lg="4" xl="4" class="d-flex justify-center">
            <v-card elevation="0">
              <v-img
                class="mx-auto"
                max-width="344"
                src="@/assets/design.png"
              ></v-img>
              <v-card-text>
                <h1
                  style="font-size: 33px"
                  class="font-weight-bold text-center mb-3"
                >
                  Design
                </h1>
                <br />
                <h2 style="font-size: 18px" class="mx-16 mt-3 text-center">
                  Kami menyediakan jasa design dari design user interface,
                  design logo, design banner design feed instagram, dan masih
                  banyak lagi.
                </h2>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="12" lg="4" xl="4" class="d-flex justify-center">
            <v-card elevation="0">
              <v-img
                class="mx-auto"
                max-width="344"
                src="@/assets/hosting-service.png"
              ></v-img>
              <v-card-text>
                <h1
                  style="font-size: 33px"
                  class="font-weight-bold text-center mb-3"
                >
                  Hosting Service
                </h1>
                <br />
                <h2 style="font-size: 18px" class="mx-16 mt-3 text-center">
                  Kami menyediakan hosting service dari hosting hingga domain,
                  kami bekerja sama dengan niagahoster untuk kenyamanan
                  pelanggan kami.
                </h2>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </section>
    <br />
    <section id="highlight" class="my-4">
      <v-container class="fill-height">
        <v-row class="d-flex align-center">
          <v-col cols="12" md="12" xl="6" lg="6">
            <v-row no-gutters class="d-flex align-center">
              <h1
                class="font-weight-black"
                style="font-size: 50px; color: #3b434c"
              >
                Jadi Akrab
              </h1>
            </v-row>
            <v-row no-gutters class="d-flex align-center">
              <h2 class="pr-16" style="font-size: 25px; color: #707d8e">
                Sebuah website yang menyediakan tools follow up untuk para
                pelaku UMKM maupun organisasi.
              </h2>
            </v-row>
          </v-col>
          <v-col cols="12" md="12" xl="6" lg="6">
            <v-carousel hide-delimiter-background height="650">
              <v-carousel-item>
                <v-row no-gutters class="d-flex align-center fill-height">
                  <v-img src="@/assets/highlight.png"></v-img>
                </v-row>
              </v-carousel-item>
            </v-carousel>
          </v-col>
        </v-row>
      </v-container>
    </section>
    <br />
    <section id="our-works" class="my-10">
      <v-container class="fill-height">
        <v-row>
          <v-col>
            <v-row no-gutters class="d-flex justify-center">
              <h1
                class="font-weight-black"
                style="font-size: 50px; color: #3b434d"
              >
                Our Works
              </h1>
            </v-row>
            <v-row no-gutters class="d-flex justify-center">
              <div
                class=""
                style="
                  height: 8px;
                  width: 96px;
                  background-color: #3fbdf1;
                  border-radius: 15px;
                "
              ></div>
            </v-row>
          </v-col>
        </v-row>
        <v-row class="mt-10">
          <v-col cols="6" md="6" lg="4" xl="4">
            <v-img src="@/assets/highlight.png"></v-img>
          </v-col>
          <v-col cols="6" md="6" lg="4" xl="4">
            <v-img src="@/assets/highlight.png"></v-img>
          </v-col>
          <v-col cols="6" md="6" lg="4" xl="4">
            <v-img src="@/assets/highlight.png"></v-img>
          </v-col>
          <v-col cols="6" md="6" lg="4" xl="4">
            <v-img src="@/assets/highlight.png"></v-img>
          </v-col>
          <v-col cols="6" md="6" lg="4" xl="4">
            <v-img src="@/assets/highlight.png"></v-img>
          </v-col>
          <v-col cols="6" md="6" lg="4" xl="4">
            <v-img src="@/assets/highlight.png"></v-img>
          </v-col>
        </v-row>
        <v-row class="flex-column justify-center">
          <v-btn text x-large color="light-blue">
            <span class="font-weight-black text-capitalize"
              >lihat lebih banyak</span
            >
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-row>
      </v-container>
    </section>
    <section id="partner" class="my-10">
      <v-container class="fill-height">
        <v-row class="d-flex align-center">
          <v-col cols="12" md="6" lg="6" xl="6" class="d-flex justify-center">
            <v-img max-width="365" src="@/assets/niagahoster-logo.png"></v-img>
          </v-col>
          <v-col cols="12" md="6" lg="6" xl="6">
            <v-row no-gutters class="d-flex align-center">
              <h1
                style="font-size: 33px; color: #3b434c"
                class="font-weight-black"
              >
                Bekerja Sama dengan Niagahoster
              </h1>
            </v-row>
            <br />
            <v-row no-gutters class="d-flex align-center">
              <h2>
                Niagahoster dipercaya sebagai penyedia layanan hosting
                terpercaya di indonesia, oleh itu kami bekerja sama dengan
                niagahoster untuk menciptakan kenyamanan terhadap client kami
              </h2>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </section>
    <br />
    <section id="start-project" class="my-10">
      <v-container>
        <v-row>
          <v-col>
            <v-row no-gutters class="d-flex justify-center">
              <h1
                class="font-weight-black"
                style="font-size: 50px; color: #3b434d"
              >
                Start a Project
              </h1>
            </v-row>
            <v-row no-gutters class="d-flex justify-center">
              <div
                class=""
                style="
                  height: 8px;
                  width: 96px;
                  background-color: #3fbdf1;
                  border-radius: 15px;
                "
              ></div>
            </v-row>
            <br />
            <v-row class="mt-10">
              <v-col>
                <h2 class="text-center">
                  Hubungi kami, kami akan balas secepatnya, jadi selalu cek
                  email kamu yah!
                </h2>
                <br />
                <v-row class="mt-10">
                  <v-col cols="4" md="4" lg="4" xl="4" class="mx-auto">
                    <v-text-field rounded outlined label="Nama"></v-text-field>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col cols="4" md="4" lg="4" xl="4" class="mx-auto">
                    <v-text-field rounded outlined label="Email"></v-text-field>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col cols="4" md="4" lg="4" xl="4" class="mx-auto">
                    <v-text-field rounded outlined label="Subject"></v-text-field>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col cols="4" md="4" lg="4" xl="4" class="mx-auto">
                    <v-textarea rounded outlined label="Pesan"></v-textarea>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col cols="4" md="4" lg="4" xl="4" class="mx-auto">
                    <v-btn
                      rounded
                      block
                      x-large
                      color="light-blue accent-3"
                      style="box-shadow: 2px 2px 20px #0277bd"
                      class="white--text"
                    >
                      <span>submit</span>
                    </v-btn>
                  </v-col>
                </v-row>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
        <v-row></v-row>
      </v-container>
    </section>
  </div>
</template>
<script>
export default {
  name: "Landing",
  data() {
    return {};
  },
};
</script>
<style scoped>
#landing {
  background-image: url("../assets/section-1-bg.png");
  height: 909px;
}
#highlight {
  background-image: url("../assets/section-1-bg.png");
  height: 900px;
  background-color: #f5fcfe;
  background-position-y: 125px;
}
#partner {
  background-image: url("../assets/partner-section-bg.png");
  height: 546px;
  background-color: #f5fcfe;
  background-position-y: 45px;
  background-position-x: 1810px;
}
.text-1 {
  font-size: clamp(40px, 3.5vw, 68px);
  color: #3b434d;
}
.text-2 {
  font-size: clamp(20px, 1.5vw, 25px);
  color: #707d8e;
}
.text-3 {
  font-size: clamp(30px, 3.5vw, 50px);
  color: #3b434d;
}

.pict-1 {
  width: clamp(408px, 5vw, 608px);
}
</style>