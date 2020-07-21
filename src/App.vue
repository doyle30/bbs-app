<template>
  <div id="app">
    <Header/>
    <BoardVisual/>
    <router-view/>
    <Acodian/>
    <Gallery/>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import BoardVisual from "@/components/BoardVisual"
import Gallery from "@/components/Gallery"
import Acodian from "@/components/Acodian"
import Footer from "@/components/Footer"
export default {
  name: "App",
  components: {
    Header,
    BoardVisual,
    Acodian,
    Gallery,
    Footer
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
