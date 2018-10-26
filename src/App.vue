<template>
	<div id="app">
      <link rel="stylesheet" 
        href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" 
        integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" 
        crossorigin="anonymous">
      <link rel="stylesheet" type="text/css" href="./assets/Gilroy/MyFontsWebfontsKit.css">
      <Header></Header>
      <Container></Container>
      <Footer></Footer>
    </div>
</template>

<script>
import Vue from 'vue'
import Header from './components/Header'
import Container from './components/Container'
import Footer from './components/Footer'

	export default {
    name: 'app',
    components: { Header, Container, Footer }
  }
</script>

<style>
	#app {
    font-family: Gilroy-Light;
    font-weight: normal;
    font-style: normal;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
	}
  .text-left{
    text-align: left;
  }
</style>