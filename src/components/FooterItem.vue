<template>
    <div class="w-1/2 md:w-auto text-left">
        <h1 class="mb-1 text-2xl text-theme">{{ title }}</h1>
        <div class="text-lg text-white">
            <p v-for="item in items" :key="item">{{item}}</p>
        </div>
    </div>
</template>


<script>
export default {
    props: ['title', 'items']
}
</script>