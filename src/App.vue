<template>
<div class="main"> 
      <div class="box">
        <NavBar />
      </div>
          <div class="container">
              <div class="box1">
                  <NavBar2 />
              </div>

              <div class="box2">
                I AM RIDE MOTOSHOW  
              </div>
          </div>
</div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import NavBar2 from './components/NavBar2.vue'





export default {
  name: 'App',
  components: {
    NavBar,
    NavBar2
    
  
    
  }
}
</script>

<style>

* {
  overflow: hidden;
}
.container {
  display: flex;
  
  
 
}
.box2 {
  
  border: 1px solid black;
  width: 100%;
  background-image: url(https://m.atcdn.co.uk/ect/media/%7Bresize%7D/41f091f3845247c7989ebadc66c5cd01.jpg);
  background-repeat: no-repeat;
  padding: 20px 20px;
  flex-wrap: wrap;
  background-size: cover;



}

.box2 button {
 
}
.box1 {
  height: cover;
  background-color: rgb(105, 62, 69);
}

.box2sud {

  max-width: 99%;
  flex-wrap: wrap;
  background-color: rgba(227, 28, 207, 0.759);
  border: 1px solid rgb(28, 74, 76);
  border-radius: 10px;
  padding-left: 5px;
}

.box3sud {

  max-width: 99%;
  flex-wrap: wrap;
  background-color: rgb(61, 90, 17);
  border: 1px solid gray;
  border-radius: 10px;
  padding-left: 5px;
  margin-top: 10px;
}

.box4sud {

  max-width: 99%;
  flex-wrap: wrap;
  background-color: white;
  border: 1px solid gray;
  border-radius: 10px;
  padding-left: 5px;
  margin-top: 10px;
}
</style>


