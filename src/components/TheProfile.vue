<script setup>
import ProfileItem from './ProfileItem.vue'
</script>
<script>
    export default {
      computed:{
        calculateAge: function() {
          let currentDate = new Date();
          let birthDate = new Date("1995/08/05");
          let difference = currentDate - birthDate;
          let age = Math.floor(difference/31557600000);
          return age
        }
      }
    }
</script>
<template>
    <ProfileItem>
        <template #heading>Basic Information</template>
        <p>Name : Sirirak Sophakarn</p>
        <p>Chinese Name : 西裡拉克·索法卡恩</p>
        <p>Japanese Name : シリラク・ソファカーン</p>
        <p>Korean Name : 시라크 소타카르</p>
        <p>Nickname : Fangplay</p>
        <p>Chinese Nickname : 方普拉</p>
        <p>Japanese Nickname : ファングプレイ</p>
        <p>Korean Nickname : 팡플레이</p>
        <p>Birth Date : 5 August 1995</p>
        <p>Age: {{age}} Years</p>
        <p>Blood Line : B</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Langauge</template>
        <p>Thai,English,Chinese,Japanese,Korean</p><br>
        <p>泰語,英語,中文,日語,韓語</p><br>
        <p>タイ語,英語,中国語,日本語,韓国語</p><br>
        <p>태국어, 영어, 중국어, 일본어, 한국어</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Education</template>
        <h4>Bechalor's Degree</h4>
        <p>B.Sc.Computer Science Thaksin University</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Skills</template>
        <h3>Programming Langauge</h3>
        <p>PHP,JavaScript,C#,Python,HTML,CSS,Java,Kotlin,ReactJS,VueJS,Laravel,FastAPI,DJango,.Net,ASP.Net,SQL,NoSQL</p>
        <h3>Programming Essentials</h3>
        <p>Visual Studio Code,Docker,Github,Git</p>
        <h3>Operating System</h3>
        <p>Linux,Windows</p>
        <h3>Multimedia Editor</h3>
        <p>Adobe Photoshop,Adobe Illustrator,Adobe Premire Pro,Adobe After Effects,Adobe Audition,VegasPro</p>
        <h3>General Skills</h3>
        <p>Fast Learner,Quick Thinking,Combine Compatibilities,Critical Thinking,Multi-langauge communication,Analyst</p>
    </ProfileItem>
</template>
