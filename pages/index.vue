<template>
  <v-layout>
    <v-flex>
      <v-card class="body-1 px-6 py-8 mb-4" max-width="800" outlined>
        <h1 class="headline">
          Welcome to the demo app for  NFT's payouts with Circle
        </h1>

        <p class="mt-6">
          This sample web application demonstrates utility of
          <a href="https://www.circle.com/en/developers" target="_blank">
            Circle APIs
          </a>
          for allowing user to receive their
          <a href="" target="_blank">
            funding from zora based auction 
          </a>
          in USDC  via fast feeless offchain API's , whereas the transactions are committed to be completed onchain .
        </p>

        <p class="font-weight-bold mt-8">This app provides:</p>

        <ul>
          <li>a sample UI showing the currently auctioned NFT's</li>
          <li>
            And the particular user can try to get their returns in USDC in
            banking account
          </li>
        </ul>
      </v-card>

      <v-card class="body-1 px-6 py-8 mb-4" max-width="800" outlined>
        <h2 class="title">Steps : </h2>

        <p class="mt-2">
          Explore the sample applications using your private api key.
        </p>
        <p class="font-weight-bold mt-6">
          Step 1: search for the zora / rarible based NFT on your address.
        <br>
         <v-btn href="/flow/charge" color="primary"> Zora Auction  </v-btn>
         <v-btn href="/flow/charge" color="primary">  Rarible Auction </v-btn>
        </p>
        

        <p class="font-weight-bold mt-6">
          Step 2 : Adding card details for registeration and paying charge
        </p>
       
        <p>
          <v-btn href="/flow/charge" color="primary"> Add card details </v-btn>
        
        <p>
          <v-btn href="/flow/charge/existing-card" color="primary">
           Use existing registered card
          </v-btn>
        </p>

        <p class="font-weight-bold mt-6">Step 3:</p>
        <p class="font-weight-light">Simple form to enter card details.</p>

        <p>
          <v-btn href="/flow/card/create" color="primary">
            Add card flow
          </v-btn>
        </p>
      </v-card>

      <v-card class="body-1 px-6 py-8 mb-4" max-width="800" outlined>
        <h2 class="title">API viewer</h2>

        <p class="mt-2">
          Make api calls using your private api key. Explore payload and
          response data in the UI.
        </p>

        <v-btn href="/debug/" color="primary"> API endpoints </v-btn>
      </v-card>

      <v-card class="body-1 px-6 py-8 mb-4" max-width="800" outlined>
        <h2 class="title">Circle API documentation portal</h2>
        <p class="mt-2">
          View API guides and reference documentation, including available
          endpoints and parameters.
        </p>

        <p>
          <v-btn
            href="https://developers.circle.com"
            target="_blank"
            color="primary"
            outlined
          >
            Circle API documentation portal
          </v-btn>
        </p>
      </v-card>
      <v-card class="body-1 px-6 py-8 mb-4" max-width="800" outlined>
        <h2 class="title">Glossary</h2>
        <p class="mt-2">
          These words are commonly used across the app and documentation.
        </p>
        <p>
          <span class="font-weight-bold">Customer:</span> the entity that enters
          an agreement with Circle to gain access to the Payments API (i.e. a
          business).
        </p>
        <p>
          <span class="font-weight-bold">End user:</span> the entity that owns a
          payment method used throughout the API (in other words, a Customer's
          customer).
        </p>
        <p>
          <span class="font-weight-bold">Payment Method:</span> an external
          account that can originate or receive transfers (payments and
          payouts), i.e. a debit or credit card, a bank account, etc. Payment: a
          complex transaction involving fiat funds being transferred from an end
          user's payment method, and depositing an associated amount of
          stablecoin on a wallet.
        </p>
        <p>
          <span class="font-weight-bold">Payout:</span> a complex transaction a
          certain amount of stablecoin from a wallet and transferring the
          associated fiat funds to a payment method Please use the menu on the
          right to configure the api key.
        </p>
      </v-card>
    </v-flex>
  </v-layout>
</template>
