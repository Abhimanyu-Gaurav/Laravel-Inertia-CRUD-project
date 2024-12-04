<template>
    <Frontend>
        <!-- This is to  setup browser head title. -->
        <Head title="About Us Page" />   

        <h1>This is {{title}} </h1>
    </Frontend>
</template>

<script setup>
import Frontend from '@/Layouts/FrontendLayout.vue';

// This is to  setup browser haed title.  
import { Head } from  '@inertiajs/vue3' 

defineProps({
    title: String
});
</script>

