<template>
  <div>
    <div class="aboutcontent" align="center">
      <h1 class="aboutheading">About Us</h1>

      <p class="aboutpara">
        We are experienced and highly professional building and construction
        specialists.
      </p>
    </div>
    <div>
      <v-tabs class="pt-2" vertical>
        <v-tab>
          <!-- <v-icon left> mdi-account </v-icon> -->
          HONESTY & INTEGRITY
        </v-tab>
        <v-tab>
          <!-- <v-icon left> mdi-lock </v-icon> -->
          BUILDING CLIENT CONFIDENCE
        </v-tab>
        <v-tab>
          <!-- <v-icon left> mdi-lock </v-icon> -->
          COMMITMENT TO CLEAR COMMUNICATION
        </v-tab>
        <v-tab>
          <!-- <v-icon left> mdi-lock </v-icon> -->
          TRANSPARENT, FLEXIBLE & FAIR ESTIMATES
        </v-tab>

        <v-tab-item>
          <v-card flat>
            <v-card-text>
              <p>
                At Atlantic Trading Solutions Limited we believe in providing
                the highest standard of work for our clients with a friendly and
                reliable approach. Honesty, integrity and putting customers
                first are at the heart of our service. We are a fully qualified
                team of tradesmen who have built up a solid reputation for
                successfully carrying out all types of building and construction
                projects, ranging from new builds, refurbishments and extensions
                to plastering, electrical work and block maintenance. Whatever
                the size of your building plans, whether it’s maximising space
                in your home, or a large commercial development we have the
                experience to make it happen.
              </p>
            </v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item>
          <v-card flat>
            <v-card-text>
              <p>
                It is of the utmost importance that our clients have confidence
                in our team and the work we do which is why we invest heavily in
                accreditations and associations. We offer additional reassurance
                by guaranteeing all our services and work are all fully insured.
              </p>
            </v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item>
          <v-card flat>
            <v-card-text>
              <p>
                To ensure we do the very best building or construction work for
                you we know that communication and total understanding of what
                you want to achieve from your project is key. We don’t just pay
                lip service to this idea; we make it our aim to understand your
                needs right from the start. The important first step is to have
                a conversation with us, there’s no risk or cost to you in
                calling us to chat things over, and we can start the process of
                understanding your desires and achieving your dreams.
              </p>
            </v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item>
          <v-card flat>
            <v-card-text>
              <p>
                Once we have a complete understanding of what you want to
                achieve we will supply a detailed quote that outlines all
                aspects of the work to be carried out with timings, materials
                and costs that is totally transparent – with no hidden
                surprises. When we have full understanding on both sides and
                agreement that we have interpreted everything correctly, we can
                then take the next step.
              </p>
            </v-card-text>
          </v-card>
        </v-tab-item>
      </v-tabs>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.aboutheading {
  color: white;
  /* text-align: center; */
}
.aboutpara {
  color: black;
  /* border: 2px solid red; */
  width: 100%;
  text-align: center;
  padding-top: 1%;
}
.aboutcontent {
  /* margin-left: 10%;
  height: 100%; */
  padding: 2%;
  width: 100%;
  background-color: rgb(241, 138, 156);
  margin-top: -1%;
}
</style>