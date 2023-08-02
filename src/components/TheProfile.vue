<script setup>
import ProfileItem from './ProfileItem.vue'
</script>

<template>
    <ProfileItem>
        <template #heading>Birth Date</template>
        <p>5 August 1995</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Langauge</template>
        <p>Thai,English,Chinese,Japanese,Korean</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Education</template>
        <h4>Bechalor's Degree</h4>
        <p>B.Sc.Computer Science Thaksin University</p>
    </ProfileItem>
    <ProfileItem>
        <template #heading>Skills</template>
        <h3>Programming</h3>
        <p>PHP,JavaScript,C#,Python,HTML,CSS,Java,Kotlin,ReactJS,VueJS,Laravel,FastAPI,DJango,.Net,ASP.Net</p>
        <h3>Operating System</h3>
        <p>Linux,Windows</p>
        <h3>Multimedia</h3>
        <p>Adobe Photoshop,Adobe Illustrator,Adobe Premire Pro,Adobe After Effects,Adobe Audition,VegasPro</p>
    </ProfileItem>
</template>
