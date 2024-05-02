<script setup lang="ts">
import Auth1 from './components/Auth1.vue';
import DarkMode from './components/DarkMode.vue';
import TeamMembers from './components/TeamMembers.vue';
import axios from "axios";

axios.get('https://api.torn.com/user/?selections=&key=7QNZtLcs9zelxrmD')
.then (response => console.log(response))
.catch(error => console.log(error))

</script>

<template>
    <div>
        
    </div>
    <DarkMode></DarkMode>
    <Auth1><</Auth1>
    <TeamMembers></TeamMembers>
</template>


