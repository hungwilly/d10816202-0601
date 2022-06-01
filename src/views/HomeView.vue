<template>
<v-container>
  <v-row>
    <v-col cols="12">
      <h1 class="text-center py-10">
        人員清單
      </h1>
    </v-col>
    <v-col md="4" cols="12">
      <v-card height="150px" class="px-5 py-3 rounded-lg">
      <div class="d-flex align-center flex-grow-0">
        <h3 class="primary--text flex-grow-0"><strong>王小明</strong></h3>
        <h4 class="gray--text d-flex ml-auto">男</h4>
      </div>

      <div>
          <span class="gray--text">
            2021062011493428
          </span>
      </div>

    <div>
        <v-icon left color="secondary">
          mdi-gmail
        </v-icon>
        <span class="secondary--text">
          Takmig001@takming.edu.tw
        </span>
    </div>
      </v-card>
    </v-col>
  </v-row>
</v-container>
</template>
  
<script>
export default {
  data(){
    return{

    }
  }
}
</script>
