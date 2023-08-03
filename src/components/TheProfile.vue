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
        <p>Age : {{calculateAge}} Years Old</p>
        <p>Blood Line : B</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Langauge</template>
        <p>Thai,English,Chinese,Japanese,Korean</p>
        <p>泰語,英語,中文,日語,韓語</p>
        <p>タイ語,英語,中国語,日本語,韓国語</p>
        <p>태국어, 영어, 중국어, 일본어, 한국어</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Education</template>
        <h4>Bechalor's Degree</h4>
        <p>B.Sc.Computer Science Thaksin University</p>
        <h4>High School Degree</h4>
        <p>Math-Science Traim Udom Suksa Of The South</p>
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
        <p>Fast Learner,Quick Thinking,Combine Compatibilities,Critical Thinking,Multi-langauge communication,Analyst,Teamwork Speaking,Problem-solving,Active listening,Leadership,Time management,Transferable</p>
    </ProfileItem>
    <ProfileItem>
      <template #heading>Performance Projects</template>
      <h3>Completed Projects</h3>
      <p><a href="https://github.com/fangplay/laravel-8-webapp/" target="_blank">Laravel Diary Full Stack(Work on Laravel Version 8)</a></p>
      <p><a href="https://github.com/fangplay/nodejs-diary" target="_blank">NodeJS Diary Full Stack</a></p>
      <p><a href="https://github.com/fangplay/fangplay-reactjs-version/tree/rev-5" target="_blank">ReactJS FrontEnd Project</a></p>
      <p><a href="https://github.com/fangplay/money-stack-nodejs" target="_blank">NodeJS Money Stack Project</a></p>
      <p><a href="https://github.com/fangplay/sci-edu-official" target="_blank">Science Edu Project(Graduate Project)</a></p>
      <p><a href="https://github.com/fangplay/fangplay.github.io" target="_blank">VUEJS Resume Web Project(Currently Viewing)</a></p>
      <h3>Inprogressing Projects</h3>
      <p>C# API Diary</p>
      <p>DJango API Diary</p>
      <p>Sping Boot API App</p>
      <p>Symfony Diary API App</p>
      <p>Kotlin Mobile App</p>
      <p>Go Web Application</p>
      <p>Flutter Mobile App</p>
    </ProfileItem>
    <ProfileItem>
      <template #heading>Language Scale</template>
      <h3>TOEIC(English)<a href="https://drive.google.com/file/d/1YHGa1SnYnpPSm12nOmjRfjRR5nZnXIuK/view" target="_blank">File Detail</a></h3>
      <p>Total : 415<br>Listening : 210<br>Reading : 205<br>Score on : 27 May 2023</p>
      <h3>CU-TEP(English)<a href="https://drive.google.com/file/d/15IMh4wfO2vv97qQl6J5lN_BAHt8QVvFB/view" target="_blank">File Detail</a></h3>
      <p>Total : 43<br>Listening : 10<br>Reading : 25<br>Writing : 8<br>Score on : 27 May 2023</p>
      <h3>JPLT(Japanese)</h3>
      <p>Will in the future</p>
      <h3>TOPIK(Korean)</h3>
      <p>Will in the future</p>
      <h3>HSK(Chinese)</h3>
      <p>Will in the future</p>
    </ProfileItem>
    <ProfileItem>
      <template #heading>Certification</template>
      <p>NodeJS Certification Course : Google Developer Launchpad(on 4 March 2023)</p>
      <p>PHP Certification Course : Google Developer Launchpad(on 17 June 2023)</p>
      <p>Laravel Certification Course : Google Developer Launchpad(on 3 March 2023)</p>
      <p>C# Certification Course : Google Developer Launchpad(on 3 August 2023)</p>
      <p>SQL Certification Course : Google Developer Launchpad(on 12 June 2023)</p>
    </ProfileItem>
    <ProfileItem>
      <template #heading>Contacts</template>
      <p>E-mail : fangplay-working@hotmail.com</p>
      <p>LinkedIn : Sirirak Sophakarn</p>
      <p>GitHub : FANGPLAY Sirirak</p>
    </ProfileItem>
</template>
