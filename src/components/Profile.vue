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
    <div class="starter">
        <h1>Basic Information</h1>
        <p>Hello everyone, Welcome to FANGPLAY official website.<br>Now this site have available now!</p>
    </div>
    <div class="slogan">
      <p>"Though I'm alone but not alone all times."</p>
      <p>"雖然我一個人，但並非總是孤單。"</p>
      <p>"私は一人ですが、すべての時間だけではありません。"</p>
      <p>"나는 혼자이지만 항상 혼자가 아닙니다."</p>
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

.slogan h1,h2,h3,h4,h5{
  font-size: 1.5rem;
}

.starter h1,h2,h3,h4,h5{
  font-size: 2.5rem;
}

@media (min-width: 1024px) {
  .letter h1,
  .letter h3 {
    text-align: left;
  }
}
</style>