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
        <img src="./img/profile-2023.jpg" style="width:100%; border-radius: 50%;">
    </div>
    <div class="starter">
        <p>Hello everyone, Welcome to FANGPLAY official website.<br>Now this site have available now!</p>
    </div>
    <div class="slogan">
      <p>"Though I'm alone but not alone all times."</p>
      <p>"雖然我一個人，但並非總是孤單。"</p>
      <p>"私は一人ですが、すべての時間だけではありません。"</p>
      <p>"나는 혼자이지만 항상 혼자가 아닙니다."</p>
    </div>
    <div class="define">
      <h4>Why set nickname is "FANGPLAY"?</h4>
      <p>FANG is speaking in English at 2 phrase.<br>First speaking in fˈæŋ (f a1 ng)<br>Second speaking in F AE1 NG</p>
      <p>Extra conclution : FANG has available in girl name and in old friends name.</p>
    </div>
    <div class="copyright" id="copyright">
      ©{{ new Date().getFullYear() }} Developed By FANGPLAY SIRIRAK<br> This site is developing on VueJS3.
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

.define h1,h2,h3,h4,h5{
  font-size: 1.5rem;
}

@media (min-width: 1024px) {
  .letter h1,
  .letter h3 {
    text-align: left;
  }
}
</style>