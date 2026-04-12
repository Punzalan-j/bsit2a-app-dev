<template>
 <div>
   <h1>Calculate</h1>
    <v-card width="500">
     <v-card-text>
      <v-form>
        <v-text-field label="Enter 1st Number: " v-model="firstnumber"></v-text-field>
        <v-text-field label="Enter 2nd Number: " v-model="secondnumber"></v-text-field>
        <v-text-field label="Total: " v-model="total"></v-text-field>
        <v-btn :label="loading? 'Calculating ... ' : 'Calculate' " color="primary" @click="calculate">Calculate</v-btn>
      </v-form>
     </v-card-text>
    </v-card>
 </div>
</template>

<script setup>
const firstnumber = ref ("0");
const secondnumber = ref ("0");
const total = ref ("0");

function calculate(){
total.value = Number(firstnumber.value) + Number(secondnumber.value)
}

</script>

<style>

</style>