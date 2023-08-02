<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
    <div class="letter">
        <h1 class="green">{{ msg }}</h1>
        <h2 class="blue">FANGPLAY Official Website</h2>
        <h4 class="red">FANGPLAY Sirirak Sophakarn</h4>
    </div>
    <div class="slogan">
        <h1>Basic Information</h1>
        <p>Hello everyone, Welcome to FANGPLAY official website.<br>Now this site have available on now!</p>
    </div>
    
</template>

<style scoped>
h1 {
  font-weight: 400;
  font-size: 2.5rem;
  position: relative;
  top: -5px;
}

h3 {
  font-size: 1.2rem;
}

.letter h1,
.letter h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .letter h1,
  .letter h3 {
    text-align: left;
  }
}
</style>