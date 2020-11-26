<template>
    <div class="p-4 sm:p-12 md:p-24 flex flex-row flex-wrap items-start justify-around w-full bg-gray-900">
        <FooterItem title="LANGUAGES" :items="['JavaScript', 'TypeScript', 'PHP', 'C#']"/>
        <FooterItem title="FRONTEND" :items="['Vue.js', 'jQuery', 'Tailwind', 'Bootstrap']"/>
        <FooterItem title="BACKEND" :items="['Express.js', 'MongoDB', 'Laravel', 'MySql', 'Discord.js']"/>
        <FooterItem title="STACKS" :items="['MEVN', 'LAMP']"/>
    </div>
</template>

<script>
import FooterItem from '@/components/FooterItem.vue';

export default {
    components: {
        FooterItem
    }
}
</script>