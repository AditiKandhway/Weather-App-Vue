<template>
  <div class="container1">
    <div class="components">
      <NavBar></NavBar>
      <WeatherTemperature></WeatherTemperature>
    </div>
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
  margin-top:10px;
  border-radius:10px;
  width:700px;
  margin-left:auto;
  margin-right:auto;
  box-sizing: border-box;
}
.components{
  background-image: url('./assets/background.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  border-radius:10px;
  border:5px solid rgb(250, 229, 229);
  box-shadow:3px 3px 3px 3px rgb(250, 229, 229);
}
</style>
