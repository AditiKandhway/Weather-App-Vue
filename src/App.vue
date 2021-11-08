<template>
  <div class="container1">
    <NavBar></NavBar>
    <WeatherTemperature></WeatherTemperature>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import WeatherTemperature from '@/components/WeatherTemperature.vue';
export default{
  name: 'App',
  components:{
    NavBar,
    WeatherTemperature
}
}
</script>

<style>

*{
  margin:0;
  font-family: sans-serif;
}

.container1{
  background-image: url('./assets/background.jpg');
  margin-top:10px;
  border:5px solid rgb(250, 229, 229);
  border-radius:10px;
  width:700px;
  box-shadow:5px 5px 5px 5px rgb(250, 229, 229);
  margin-left:auto;
  margin-right:auto;
  box-sizing: border-box;
}
</style>
