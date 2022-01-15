<template>
  <v-layout>
    <v-flex>
      <v-card>
        <form id="NFT_Wallet" @submit="checkForm"></form>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import {constructMediaData , sha256FromBuffer, generateMetadata} from '@zoralabs/zdk'
import {Signer , Wallet } from 'ethers'

export default {}
</script>

<style></style>
