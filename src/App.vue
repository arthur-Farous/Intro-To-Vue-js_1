<script setup>
import TheNavbar from './components/TheNavbar.vue'
import HeaderComponent from './components/HeaderComponent.vue'

</script>

<template>
  <div><TheNavbar/></div>
  <section class="main_text">
    <p>Findtrend helps you to increase your productivity and reduce your computer's
    memory load,</p><p class="different"> an application that can fulfill your daily browsing needs.</p>
  </section>
  <HeaderComponent headerText="Findtrend make +1000 Startup grow"/>
  <div class="container">
    <div class="box"><img src="..assets/Rectangle.svg" alt=""/></div>
    <div class="box"><img src="..assets/image 116.svg" alt=""/></div>
    <div class="box"><img src="..assets/image 128.svg" alt=""/></div>
    <div class="box"><img src="..assets/image 121.svg" alt=""/></div>
    <div class="box"><img src="..assets/image 119.svg" alt=""/></div> 
  </div>
  <div class="container">
    <div class="box"><img src="..assets/Rectangle.svg" alt=""/></div>
    <div class="box"><img src="..assets/image 112.svg" alt=""/></div>
    <div class="box"><img src="..assets/coinbase.svg" alt=""/></div>
    <div class="box"><img src="..assets/Expedia.svg" alt=""/></div> 
  </div>
  <div class="container">
    <div class="box"><img src="..assets/Airtable.svg" alt=""/></div>
    <div class="box"><img src="..assets/image 112.svg" alt=""/></div>
    <div class="box"><img src="..assets/coinbase.svg" alt=""/></div>
    <div class="box"><img src="..assets/Expedia.svg" alt=""/></div> 
  </div>
  <div class="container">
    <div class="box"><img src="..assets/Airtable.svg" alt=""/></div>
    <div class="box"><img src="..assets/image 112.svg" alt=""/></div>
    <div class="box"><img src="..assets/coinbase.svg" alt=""/></div>
    <div class="box"><img src="..assets/Expedia.svg" alt=""/></div> 
  </div>
  <HeaderComponent headerText="All platform connect to Findtrend"/>
  <div class="straight">
    <img src =..src/assets/Retangle39.png alt=""/>
    <img src =..src/assets/Retangle39.png alt=""/>
    <img src =..src/assets/Retangle39.png alt=""/>
    <img src =..src/assets/Retangle39.png alt=""/>
    <img src =..src/assets/Retangle39.png alt=""/>
    <img src =..src/assets/Retangle39.png alt=""/>
    <img src =..src/assets/Retangle39.png alt=""/>
    <img src =..src/assets/Retangle39.png alt=""/>
  </div>
  <div class="twitter">
    <img src="../src/assets/tweet1.jpg" alt=""/>
    <img src="../src/assets/tweet2.jpg"  alt=""/>
    <img src="../src/assets/tweet3.jpg"  alt=""/>
  </div>
  <ButtonComponent buttonText="View More Trend"/>
</template>

<style scoped>
.main_text{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding-top: 220px;
  padding-left: 140px;
  padding-right: 140px;
}

p{
  color: #000;
font-size: 64px;
font-style: normal;
font-weight: 700;
line-height: normal;
}

h4{
  color: #ADADAD;
font-size: 64px;
font-style: normal;
font-weight: 700;
line-height: normal;}

.different{
  color: #ADADAD;
font-size: 64px;
font-style: normal;
font-weight: 700;
line-height: normal
}
.container{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 32px;
}
.straight img{
  max-width: 124px;
 max-height: 124px;
   flex-shrink: 0;
}

.twitter{
display: flex;
flex-direction: column;
align-items:center ;
justify-content:center;
gap: 43px;
}

button{
  color: #FFF;
text-align: center;
font-family: Effra;
font-size: 18px;
font-style: normal;
font-weight: 700;
line-height: 140%; /* 25.2px */
background: #000;
}
@media screen and (max-width: 1200px) {
  
  .main_text{
    padding-right: 20px;
    padding-left: 20px;
  }
  .different{
    font-size: 36px;
  }
  
  p{font-size: 36px;}
}

.container{
  display: grid;
  grid-row: 1fr 1fr;
}

.twitter{
  gap:16px;
}
</style>
