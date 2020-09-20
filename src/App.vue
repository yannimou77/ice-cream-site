<template>
  <v-app>
    <v-main>
      <div class="main-content-container">
        <v-img :src="require('./logo-white-background.png')"></v-img>
        <HelloWorld></HelloWorld>
      </div>
    </v-main>
  </v-app>
</template>

<script>

// import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  // components: {HelloWorld},

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.main-content-container {
  background:#e46454;
  display: flex;
  height: 900px;
  justify-content: center;
}

.main-contnet {
  width: 200px;
  height: 900px;
  background: white;
  margin-top: 100px;

}
</style>
