<script setup>
    defineProps({
        nama : String,
        kelas : String,
        status : String
    })
</script>
<template>
    <h2>{{ nama }}</h2>
    <h2>{{ kelas }}</h2>
    <h2 v-if="status == 1" >status : hadir</h2>
    <h2 v-else-if="status == 2">status : alpa</h2>
    <h2 v-else="status == 3">status : izin</h2>
</template>