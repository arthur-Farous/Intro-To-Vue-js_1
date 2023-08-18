<script setup>
defineProps(["headerText"])
</script>


<template>
<header>
    <h2>{{ headerText }}</h2>
</header>

</template>

<style scoped>
h2{
    color: #000;
text-align: center;
font-family: Effra;
font-size: 64px;
font-style: normal;
font-weight: 700;
line-height: normal;
padding-top: 280px;
padding-left: 140px;
padding-right: 140px;
padding-bottom: 80px;
}

    @media screen and (max-width: 1200px) {
        h2{font-size: 36px;
            padding-top: 160px;
            padding-right: 20px;
            padding-left: 20px;
            padding-bottom: 32px;
        }
    }

</style>