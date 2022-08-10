<template>
  <section id="pricing" class="pb-8">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-card style="width: 100%">
            <h1 class="text-center pt-6 font-weight-light display-2">Featured NFTs</h1>
            <h2 class="text-center pt-3 font-weight-light display-1 ml-5 mr-5">Top listed NFTs by popularity. If purchasing AOJ NFTs listed as shipping with the original work you can opt to contact the artist and provide the shipping address. Each NFT is represented by the AOJ token on the Polygon blockchain.</h2>
            <v-divider class="my-6"></v-divider>
            <v-row class="text-center">
              <v-col class="col-12 col-sm-6 col-md-4">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <!-- <div class="circle1">
                        <div class="circle2"> -->
                          <v-img src="~@/assets/img/legacy.jpg"></v-img>
                        <!-- </div>
                      </div> -->
                    </div>
                    <br/>
                    <div class="text--disabled text-uppercase text-h5 my-2">Legacy of Our Ancestors</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Acryllic on canvas</div>
                    <!-- <v-divider class="my-2"/> -->
                    <div class="text-uppercase blue--text">Pick your canvas size</div>
                    <!-- <v-divider class="my-2"/> -->
                
                    <v-divider class="my-2"/>
                    <div class="text-uppercase text-h4 mt-6 blue--text">
                  <v-img
                    src="@/assets/img/eth.png"
                    max-width="20px"
                    class="mr-2"
                  /> <v-img
                    src="@/assets/img/icon2.svg"
                    max-width="20px"
                    class="mr-2"
                  /> 1 ETH
                  </div>
                    <v-btn
                        v-bind="size"
                        rounded
                        outlined
                        color="blue"
                        class="mt-6"
                    >
                     <a style="text-decoration:none" href="https://opensea.io/assets/matic/0x2562ffa357fbdd56024aea7d8e2111ad299766c9/14">Purchase</a>
                    </v-btn>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
                </div>
                <v-divider class="mx-4" v-if="!this.$vuetify.breakpoint.smAndUp"></v-divider>
              </v-col>
              <v-col class="col-12 col-sm-6 col-md-4">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <!-- <div class="circle1">
                        <div class="circle2"> -->
                          <v-img src="~@/assets/img/joy.jpg"/>
                        <!-- </div>
                      </div> -->
                    </div>
                    <br/>
                    <br/>
                    <br/>
                    <div class="text--disabled text-uppercase text-h5 my-2">Joy in Community</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Acryllic on canvas</div>
                    <!-- <v-divider class="my-2"/> -->
                    <div class="text-uppercase blue--text">Ships with Original</div>
                  
                   <!--  <v-divider class="my-2"/> -->
                   <div class="text-uppercase blue--text">All AOJ NFTs are also available for purchase on JalehsArt.com and via her shop on Etsy</div>
                   
                    <v-divider class="my-2"/>
                    <div class="text-uppercase text-h4 mt-6 blue--text">
                    <v-img
                    src="@/assets/img/eth.png"
                    max-width="20px"
                    class="mr-2"
                  /> <v-img
                    src="@/assets/img/icon2.svg"
                    max-width="20px"
                    class="mr-2"
                  /> 1 ETH
                    </div>
                    <a style="text-decoration:none" href="https://opensea.io/assets/matic/0x2562ffa357fbdd56024aea7d8e2111ad299766c9/15">
                    <v-btn
                        v-bind="size"
                        rounded
                        outlined
                        color="blue"
                        class="mt-6"
                    >
                      Purchase
                    </v-btn>
                  </a>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.mdAndUp"></v-divider>
                </div>
                <v-divider class="mx-4" v-if="!this.$vuetify.breakpoint.smAndUp"></v-divider>
              </v-col>
              <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>

                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <!-- <div class="circle1">
                        <div class="circle2"> -->
                          <v-img src="~@/assets/img/Tied.jpg"/>
                       <!--  </div>
                      </div> -->
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2">Tied Together by our Love</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Acryllic on canvas</div>
                    <!-- <v-divider class="my-2"/> -->
                    <div class="text-uppercase blue--text">Pick your canvas size</div>
                    <!-- <v-divider class="my-2"/> -->
                   
                    <v-divider class="my-2"/>
                    <div class="text-uppercase text-h4 mt-6 blue--text">
                    <v-img
                    src="@/assets/img/eth.png"
                    max-width="20px"
                    class="mr-2"
                  /> <v-img
                    src="@/assets/img/icon2.svg"
                    max-width="20px"
                    class="mr-2"
                  />1 ETH
                    </div>
                    <v-btn
                        v-bind="size"
                        rounded
                        outlined
                        color="blue"
                        class="mt-6"
                    >
                      <a style="text-decoration:none" href="https://opensea.io/assets/matic/0x2562ffa357fbdd56024aea7d8e2111ad299766c9/10">Purchase</a>
                    </v-btn>
                  </v-card-text>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <div class="svg-border-rounded text-light">
      <!-- <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 144.54 17.34"
        preserveAspectRatio="none"
        fill="currentColor"
      >
        <path
          d="M144.54,17.34H0V0H144.54ZM0,0S32.36,17.34,72.27,17.34,144.54,0,144.54,0"
        />
      </svg> -->
      <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 1440 320"
          preserveAspectRatio="none"
          fill="currentColor"
      >
        <path
            d="M0,64L80,90.7C160,117,320,171,480,181.3C640,192,800,160,960,138.7C1120,117,1280,107,1360,101.3L1440,96L1440,320L1360,320C1280,320,1120,320,960,320C800,320,640,320,480,320C320,320,160,320,80,320L0,320Z"
        ></path>
      </svg>
    </div>
  </section>
</template>

<style lang="scss">
$main_color: #283e79;

ul {
  font-size: 13px;
  line-height: 1.5em;
  margin: 5px 0 15px;
  padding: 0;

  li {
    list-style: none;
    position: relative;
    padding: 0 0 0 20px;
  }

  li {
    &::before {
      content: "";
      position: absolute;
      left: 0;
      top: 5px;
      width: 10px;
      height: 10px;
      background-color: $main_color;
      border-radius: 50%;
      -moz-border-radius: 50%;
      -webkit-eeborder-radius: 50%;
    }
  }
}
</style>

<style scoped>
.header {
  background-color: #283e79;
  color: white;
}

.circle1 {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  background-color: #f0f8ff;
  display: flex;
  align-items: center;
  justify-content: center;
}

.circle2 {
  border-radius: 50%;
  width: 100px;
  height: 100px;
  background-color: #e0effc;
  display: flex;
  align-items: center;
  justify-content: center;
}

.flex-center {
  display: flex;
  align-items: center;
  justify-content: center;
}

.svg-border-rounded svg {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  color: #f4f7f5;
  z-index: -1;
}

#pricing {
  z-index: 0;
}

.content {
  z-index: 1;
}

svg {
  overflow: hidden;
}

section {
  position: relative;
}
</style>

<script>
export default {
  data: () => ({
    planos: [
      {
        title: "Básico",
        price: "R$100,00",
        img: "f1.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 3",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 4",
          },
        ],
      },
      {
        title: "Padrão",
        price: "R$150,00",
        img: "f2.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 3",
            color: "success",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 4",
          },
        ],
      },
      {
        title: "Premium",
        price: "R$250,00",
        img: "f3.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 3",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 4",
            color: "success",
          },
        ],
      },
    ],
  }),
  computed: {
    size() {
      const size = {md: "large", xl: "x-large"}[
          this.$vuetify.breakpoint.name
          ];
      return size ? {[size]: true} : {};
    }
  },
};
</script>