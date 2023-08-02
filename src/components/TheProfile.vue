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
</template>
