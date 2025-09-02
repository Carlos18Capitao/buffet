<script setup>
import HearoArea from '@/Layouts/HearoArea.vue';
import Footer from '@/Layouts/Footer.vue';
import Section from '@/Pages/Section.vue';
import { Head, Link } from '@inertiajs/vue3';


defineProps({

});
</script>

<template>

    <Head title="Home" />
    <HearoArea />
    <Section />
     <!-- end client section -->
    <Footer />
</template>
