<script setup>
 defineProps(["buttonText"])
</script>


<template>
  <div>
    <button>{{buttonText}}</button>
   
  </div>
</template>

<style scoped>
button{
    padding: 12px 32px;
    border-radius: 40px;
    background: #fff;
    color: black;
    border: none;
}
.bt_1{
background-color: #A8FF35;
}

</style>