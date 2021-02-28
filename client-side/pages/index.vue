<template>
  <v-app>
    <header>
      <v-app-bar
        height = 130px
        elevate-on-scroll
      >
        <v-toolbar-title>HitMe</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-list
          nav
          dense
        >
          <v-list-item-group>
            <v-list-item>
              <v-list-item-title>HitMeとは</v-list-item-title>
              <v-list-item-title>Ranking</v-list-item-title>
              <v-list-item-title>Post</v-list-item-title>            
            </v-list-item>
            <v-list-item>
              <v-list-item-title>ログイン</v-list-item-title>
            </v-list-item>
          </v-list-item-group>
        </v-list>
      </v-app-bar>
    </header>
  </v-app>


</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
