<template>
  <section id="about">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col cols="12" md="7">
              <h1 class="font-weight-light display-2">About the AOJ Token</h1>
              <h1 class="font-weight-light display-0 mb-3">
                Each work of art is unique, ownership is provable and transferrable. Click the AOJ token icon at top left to see the contract on Polygon.
              </h1>
              <v-row>
                <v-col cols="12" class="d-flex align-center">
                  <a href="https://opensea.io/theartofJalehV2">
                  <v-img
                    src="@/assets/img/icon1.png"
                    max-width="60px"
                    class="mr-4"
                  />
                </a>
                  <p class="text-justify">
                    AOJ NFTs are on OpenSea! OpenSea, the wildly successful non-fungible token (NFT) market, has integrated Polygon PoS, providing users with faster and cheaper transactions. By working with OpenSea, Polygon is helping bring NFTs to the world. By launching on Polygon, AOJ token is brining Jaleh's art to the world.
                  </p>
                </v-col>
                <v-col cols="12" class="d-flex align-center">
                  <a href="https://polygonscan.com/token/0x2562ffa357fbdd56024aea7d8e2111ad299766c9">
                  <v-img
                    src="@/assets/img/icon2.svg"
                    max-width="60px"
                    class="mr-4"
                  />
                </a>
                  <p class="text-justify">
                    The AOJ token is a verifiable contract launched on Polygon, with real-world assets associated with every NFT. The integration of Polygon with OpenSea offers users with a seamless purchasing and minting experience. Partly due to Polygon’s low transaction fees, OpenSea is able to pay for all gas costs making transactions free for users. Gas fees are only required when transferring ETH funds to the Polygon network. 
                  </p>
                </v-col>
                <v-col cols="12" class="d-flex align-center">
                  <a href="https://solsea.io/collection/622b3289a96d88068ddc97d5">
                  <v-img
                    src="@/assets/img/icon3.svg"
                    max-width="60px"
                    class="mr-4"
                  />
                </a>
                  <p class="text-justify">
                    AOJ NFTs are also on Solana! Solana’s high throughput and low fees make it a perfect fit for NFTs of all shapes and sizes. From auctions to perpetual royalties coded right into the NFT, Solana supports a fully decentralized on-chain experience for artists and collectors.
                  </p>
                </v-col>
              </v-row>
            </v-col>
            <v-col cols="12" md="5" class="d-none d-md-flex">
              <v-img
                src="@/assets/img/ill1.png"
                class="d-block ml-auto mr-auto"
                max-width="400px"
              />
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#about {
  background-color: #f4f7f5;
}
</style>
