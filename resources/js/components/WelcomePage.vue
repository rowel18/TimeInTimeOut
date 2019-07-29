<template>
    <div class="container">
        <h1>TIME</h1>
        <div class="container" id="Date"></div>
        <div class="container" id="Time"></div>
        <input type="text" id="RFID">
    </div>
</template>

<script>
import { setTimeout } from 'timers';
    export default {
        mounted() {
            console.log('Component mounted.')
        },
    }
</script>
