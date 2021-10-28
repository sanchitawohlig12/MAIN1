<template>
  <div class="Home">
    <!-- <div v-if="!$vuetify.breakpoint.smAndDown">
      <v-carousel cycle height="auto" hide-delimiters :show-arrows="false">
        <v-carousel-item transition="scroll-x-reverse-transition">
         
          <img class="home1" src="/home/desk1.jpg" />
        </v-carousel-item>
        <v-carousel-item transition="scroll-x-reverse-transition">
          <img class="home1" src="/home/desk2.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item transition="scroll-x-reverse-transition">
          <img class="home1" src="/home/desk3.jpg" alt=""
        /></v-carousel-item>
      </v-carousel>
    </div>
    <div v-if="$vuetify.breakpoint.smAndDown">
      <v-carousel height="auto" hide-delimiters cycle :show-arrows="false">
        <v-carousel-item>
          <img class="home1" src="/home/mob1.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item>
          <img class="home1" src="/home/mob2.jpg" alt=""
        /></v-carousel-item>
        <v-carousel-item>
          <img class="home1" src="/home/mob3.jpg" alt=""
        /></v-carousel-item>
      </v-carousel>
    </div> -->

    <div class="homecontent" align="center">
      <h1 class="homeheading">HOME</h1>

      <p class="homepara">
        We are experienced and highly professional building and construction
        specialists.
      </p>
    </div>
    <div>
      <v-card>
        <!-- <v-toolbar flat color="primary" dark>
          <v-toolbar-title>About Us</v-toolbar-title>
        </v-toolbar> -->
        <div class="pt-5" align="center">
          <h3>ABOUT US</h3>
        </div>
        <v-tabs class="pt-2" vertical>
          <v-tab>
            <!-- <v-icon left> mdi-account </v-icon> -->
            HONESTY & INTEGRITY
          </v-tab>
          <v-tab>
            <!-- <v-icon left> mdi-lock </v-icon> -->
            BUILDING CLIENT CONFIDENCE
          </v-tab>

          <v-tab-item>
            <v-card flat>
              <v-card-text>
                <p>
                  At Atlantic Trading Solutions Limited we believe in providing
                  the highest standard of work for our clients with a friendly
                  and reliable approach. Honesty, integrity and putting
                  customers first are at the heart of our service. We are a
                  fully qualified team of tradesmen who have built up a solid
                  reputation for successfully carrying out all types of building
                  and construction projects, ranging from new builds,
                  refurbishments and extensions to plastering, electrical work
                  and block maintenance. Whatever the size of your building
                  plans, whether it’s maximising space in your home, or a large
                  commercial development we have the experience to make it
                  happen.
                </p>
              </v-card-text>
            </v-card>
          </v-tab-item>
          <v-tab-item>
            <v-card flat>
              <v-card-text>
                <p>
                  It is of the utmost importance that our clients have
                  confidence in our team and the work we do which is why we
                  invest heavily in accreditations and associations. We offer
                  additional reassurance by guaranteeing all our services and
                  work are all fully insured.
                </p>
              </v-card-text>
            </v-card>
          </v-tab-item>
        </v-tabs>
      </v-card>
    </div>

    <div class="homeservices">
      <!-- <v-toolbar flat color="primary" dark>
            <v-toolbar-title>Our Services</v-toolbar-title>
          </v-toolbar> -->
      <div class="container pt-5" align="center">
        <h3>SOME OF OUR SERVICES</h3>
        <p>
          We are happy to work for residential, commercial or industrial clients
          and have experience in all types of projects. Please call us to take
          the first step to getting your building project started.
        </p>
      </div>
      <v-row class="pt-3 align-item-center justify-content-around">
        <v-col cols="12" md="3" sm="12">
          <v-card :loading="loading" class="mx-auto my-12" max-width="374">
            <template slot="progress">
              <v-progress-linear
                color="deep-purple"
                height="10"
                indeterminate
              ></v-progress-linear>
            </template>

            <v-img
              height="250"
              src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
            ></v-img>

            <v-card-title>Cafe Badilico</v-card-title>
          </v-card>
        </v-col>
        <v-col cols="12" md="3" sm="12">
          <v-card :loading="loading" class="mx-auto my-12" max-width="374">
            <template slot="progress">
              <v-progress-linear
                color="deep-purple"
                height="10"
                indeterminate
              ></v-progress-linear>
            </template>

            <v-img
              height="250"
              src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
            ></v-img>

            <v-card-title>Cafe Badilico</v-card-title>
          </v-card>
        </v-col>
        <v-col cols="12" md="3" sm="12">
          <v-card :loading="loading" class="mx-auto my-12" max-width="374">
            <template slot="progress">
              <v-progress-linear
                color="deep-purple"
                height="10"
                indeterminate
              ></v-progress-linear>
            </template>

            <v-img
              height="250"
              src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
            ></v-img>

            <v-card-title>Cafe Badilico</v-card-title>
          </v-card>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.Home {
}
.home1 {
  /* height: 100%; */
  /*width: 100%; */
  width: 100%;
}
.homeheading {
  color: white;
  /* text-align: center; */
}
.homepara {
  color: black;
  /* border: 2px solid red; */
  width: 100%;
  text-align: center;
  padding-top: 1%;
}
.homecontent {
  /* margin-left: 10%;
  height: 100%; */
  padding: 2%;
  width: 100%;
  background-color: rgb(241, 138, 156);
  margin-top: -1%;
}

@media only screen and (max-width: 768px) {
}

@media (max-width: 991px) {
  .homecontent {
    /* margin-top: -70.5%; */
  }
}
@media only screen and (min-device-width: 768px) and (max-device-width: 1024px) {
  .homecontent {
    /* margin-top: 0%; */
  }
  .ca {
    /* height: 500px; */
  }
}
@media (max-width: 320px) {
  .homecontent {
    /* margin-top: -8%; */
  }
}
@media only screen and (min-device-width: 1024px) and (max-device-width: 1366px) {
  .homecontent {
    /* padding-top: 3%; */
  }
}
</style>