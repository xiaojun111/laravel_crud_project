<template>

    <div>Main</div>
    <Link href="/hello">Home</Link>
    <div>
        The message is {{ message }}
    </div>

</template>

<script setup>

import { Link } from '@inertiajs/vue3'
defineProps({
    message:String
})

</script>

<!--
<script>
import MainLayout from '../../Layouts/MainLayouts.vue';

    export default {
        layout: MainLayout
    }
</script>
-->