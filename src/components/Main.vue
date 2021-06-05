<template>
  <v-container fill-height>
    <v-row align="center" justify="center">
      <v-card style="opacity: 0.8" dark class="pa-3 mx-auto" max-width="450" outlined>
        <v-list-item three-line>
          <v-list-item-content>
            <div class="text-overline mb-4">Fledra Bank</div>
            <v-list-item-title class="text-h5 mb-1">
              Hoşgeldin, Michael.
            </v-list-item-title>
            <v-list-item-subtitle
              >Hesabında <span class="green--text">$400</span> bulunuyor.</v-list-item-subtitle
            >
          </v-list-item-content>

          <v-list-item-avatar tile size="120">

            <v-img
            style="border-radius: 10px" 
            contain
            src="../assets/logo.png"></v-img>
          </v-list-item-avatar>
        </v-list-item>

        <v-card-actions>
          <v-btn outlined text> Para Yatır </v-btn>
          <v-btn outlined text> Para Çek </v-btn>
        </v-card-actions>
      </v-card>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
  
    
  }),
};
</script>
