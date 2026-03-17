<template>
  <div class="d-flex justify-center align-center" style="height: 100vh;">

    <v-card width="400" class="text-center" elevation="12">
      <v-icon size="80" color="pink" class="mt-10">mdi-apple</v-icon>
      <v-card-text class="py-10">
        <v-text-field variant="outlined" v-model="username" flat label="Username" prepend-inner-icon="mdi-account" clearable></v-text-field>
        <v-text-field variant="outlined" v-model="password" label="Password" prepend-inner-icon="mdi-lock" type="password" clearable></v-text-field>
        <v-btn color="pink" @click="login" block>Sign in</v-btn>
      </v-card-text>
    </v-card>

<<<<<<< HEAD
=======
    <v-row>
      <v-col cols="12" md="3">
        <v-card height="120" color="#EEEEEE">
          <v-card-text>
            <v-row justify="end">
              <v-col cols="12" class="text-right text-h6 text-uppercase">student</v-col>
              <v-col cols="12" class="text-right text-h4 font-weight-bold">120</v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-col>

            <v-col cols="12" md="3">
        <v-card height="120" color="#EEEEEE">
          <v-card-text>
            <v-row justify="end">
              <v-col cols="12" class="text-right text-h6 text-uppercase">account</v-col>
              <v-col cols="12" class="text-right text-h4 font-weight-bold">234</v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-col>

            <v-col cols="12" md="3">
        <v-card height="120" color="#EEEEEE">
          <v-card-text>
            <v-row justify="end">
              <v-col cols="12" class="text-right text-h6 text-uppercase">expenses</v-col>
              <v-col cols="12" class="text-right text-h4 font-weight-bold">34</v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-col>

            <v-col cols="12" md="3">
        <v-card height="120" color="#EEEEEE">
          <v-card-text>
            <v-row justify="end">
              <v-col cols="12" class="text-right text-h6 text-uppercase">new employee</v-col>
              <v-col cols="12" class="text-right text-h4 font-weight-bold">120</v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <v-row>
            <v-col cols="12" md="6">
        <v-card height="600" color="#EEEEEE">
        </v-card>
      </v-col>

           <v-col cols="12" md="6">
            <v-row>
        <v-col cols="12">
        <v-card height="180" color="#EEEEEE">
        </v-card>
      </v-col>

      <v-col cols="12">
        <v-card height="180" color="#EEEEEE">
        </v-card>
      </v-col>

      <v-col cols="12">
        <v-card height="180" color="#EEEEEE">
        </v-card>
      </v-col>
    </v-row> 
   </v-col>
   
   </v-row>

>>>>>>> 810426b56e629700dc772436cd78d5519262f037
  </div>
</template>

<script setup>
definePageMeta({
    layout: "auth",
});
const defaultUsername = ref("admin");
const defaultPassword = ref("admin123")
const username = ref("");
const password = ref("");


function login() {
alert("Login successful!");
}
</script>