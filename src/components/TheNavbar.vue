<script setup>
import ButtonComponent from "./ButtonComponent.vue"
</script>


<template>
<section>
    <nav>
      <div class="first_nav">
        <img src="../assets/Badge.svg" alt="" class="badge_1"/>
        <h4>Findtrend</h4>
        <img src="../assets/hamburger.svg" alt=""  class="menu_nav"/>
      </div>
      <ul>
        <li><a href="#">About</a></li>
        <li><a href="#">How it works</a></li>
        <li><a href="#">Pricing</a></li>
        <li><a href="#">Solution</a></li>
        <li><a href="#">Features</a></li>
      </ul>
      <div class="nav-buttons">
        <a href="#">Login</a>
        <ButtonComponent buttonText="Register"/>
      </div>
    </nav>
    <div class="text-content">
    <h3>Minimize your tabs.</h3>
    <h3>Find the trends!</h3>
    </div>
    <div class="memory">
        <p>Don’t let your computer memories consumes all of those browser tabs.</p> 
    <p>Findtrend  let you gathers all of your favorite website into one place.</p>
    </div>
    <div class="start">
        <ButtonComponent buttonText="Get Started 🔥" class="bt_1"/>
    </div>
     
  </section>
</template>

<style scoped>
section{background-color: black;}
nav{ 
    display: flex;
    justify-content: space-between;
    background-color: black;
    align-items: center;
    padding: 28px 80px;
    
}


h4{color: #fff;
    font-size: 18px;
    text-align: center;
}

.menu_nav{display:none}
ul{ 
    display: flex;
    gap: 40px;
}

ul li{
    list-style: none;
    
}

a{
    text-decoration: none;
    color: #fff;
    gap: 10px;
    font-size: 20px;
}

.nav-buttons{ 
    display: flex;
    align-items: center;
    gap:40px ;
             
}


.first_nav{
    display: flex;
   /* flex-direction: row;*/
     align-items: center;
     justify-content: center;
    gap: 5px;
}

.text-content{
  display:flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding-top: 140px;
  padding-left: 370px;
  padding-right: 370px;
}

h3{
    color: #FFF;
text-align: center;
font-size: 72px;
font-style: normal;
font-weight: 900;
line-height: 112%;
}
.memory{
    padding-left: 307px;
padding-right: 307px;
padding-top: 24px;
}
p{
    color: #8B8B8B;
text-align: center;
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 27px */

}
.start{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding-top: 40px;
    font-size: 18px;
}
.bt_1{
color: #A8FF35;
}

@media screen and (max-width: 1200px) {
h4,ul,.nav-buttons{
    display: none;
}

.menu_nav{display: flex;}



.first_nav{
    flex-direction: row;
    padding:20px 24px;
    flex-shrink: 0s;
    
    align-items: center;
      justify-content: space-evenly;
     gap: 230px;
     
}


.badge_1{display: flex;}
h3{
    font-weight: 36px;
}
.text-content{
    padding-left: 28px;
    padding-right: 28px;
}
.memory{
    padding-left: 45px;
    padding-right: 45px;
    padding-top: 16px;
}
p{
    font-size: 14px;
}

.start{font-size: 14px;
}
}

</style>