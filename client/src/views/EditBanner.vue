<template>
  <div>
    <div class="area">
      <Header :word="'Edit Banner'"></Header>
      <FormEditBanner></FormEditBanner>
    </div>

    <NavBar></NavBar>
  </div>
</template>

<script>
import NavBar from '../components/NavBar'
import FormEditBanner from '../components/FormEditBanner'
import Header from '../components/Footer' 

export default {
  name: 'EditBanner',
  components: {
    NavBar,
    FormEditBanner,
    Header
  }
}
</script>

<style scoped>
.area {
  float: left;
  background: #e2e2e2;
  width: 100%;
  height: 100%;
}
@font-face {
  font-family: "Titillium Web";
  font-style: normal;
  font-weight: 300;
  src: local("Titillium WebLight"), local("TitilliumWeb-Light"),
    url(http://themes.googleusercontent.com/static/fonts/titilliumweb/v2/anMUvcNT0H1YN4FII8wpr24bNCNEoFTpS2BTjF6FB5E.woff)
      format("woff");
}
</style>
