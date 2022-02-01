<template>
  <section id="download">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col sm="4" class="hidden-xs-only">
              <v-img src="@/assets/img/ill2.png" class="rounded d-block ml-auto mr-auto" max-width="200em" height="20em"/>
            </v-col>
            <v-col cols="12" sm="8" class="black--text text-left">
              <h1 class="font-weight-light display-2 mb-2">My Work</h1>
              <h1 class="font-weight-light">
              Through her abstract paintings, Jaleh conveys themes of community, unity, and love. Jaleh creates pieces that express her own life experiences – being surrounded by a trusting community, holding hands with family and friends, witnessing a baptism. .
              </h1>
              <v-btn rounded outlined href="https://jsadravi.com/" target="_blank" large color="black" class="mt-4">
                <v-icon class="mr-2">
                  
                </v-icon>
                The Art of Jaleh
              </v-btn>
              <br />
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#download {
  background-image: url("~@/assets/img/bgDownload.png");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 500px;
}

#download .container,
#download .row {
  height: 100%;
}
</style>