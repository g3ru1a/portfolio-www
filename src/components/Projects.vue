<template>
    <div class="w-full md:px-24 lg:px-32 xl:px-44 flex items-stretch justify-evenly flex-wrap mb-8">
    
        <project class="w-full lg:w-1/2" image="scaffoldcli.png" git="https://github.com/g3ru1a/project-scaffolding" npm="https://www.npmjs.com/package/@g3ru1a/scaffolding">
            <template v-slot:title>API Scaffold CLI</template>
            <template v-slot:desc>Basic CLI that scaffolds basic API folders & files in JS or TS.</template>
        </project>

        <project class="w-full lg:w-1/2" image="360tooz.png" git="https://github.com/g3ru1a/360tooz" npm="https://www.npmjs.com/package/360tooz">
            <template v-slot:title>360Tooz</template>
            <template v-slot:desc>Command Line program that pulls images from <a href="https://youtooz.com">youtooz products</a> and creates a spinning gif.</template>
        </project>

         <project class="w-full lg:w-full" image="faqbot.png" git="https://github.com/g3ru1a/faq-discord-bot" chrome="https://top.gg/bot/775872785225351168">
            <template v-slot:title>FAQ Discord Bot</template>
            <template v-slot:desc>A Bot that allows server administrators to register frequently asked questions and it auto replies to messages in specific channels checking similarities with Damerau-Lavenshtein's distance.</template>
        </project>

        <project class="w-full lg:w-1/2 2xl:w-1/3" image="toozdark.jpg" git="https://github.com/g3ru1a/ToozDark" chrome="https://chrome.google.com/webstore/detail/toozdark/ofeandbogmiogflfhknohbgmgpefpdke">
            <template v-slot:title>ToozDark</template>
            <template v-slot:desc>A chrome extension that adds a darkmode for the <a href="https://youtooz.com">youtooz website</a>.</template>
        </project>

         <project class="w-full lg:w-1/2 2xl:w-2/3" image="paidprot.png" git="https://github.com/g3ru1a/PaidProtection" chrome="https://www.spigotmc.org/resources/paidprotection.69512/">
            <template v-slot:title>PaidProtection</template>
            <template v-slot:desc>A simple spigot plugin that allows players to create regions around their bases by selecting 2 corners and buying it.</template>
        </project>
        
         <!-- <project class="md:w-1/3" image="toozdark.jpg" git="https://github.com/g3ru1a/ToozDark" chrome="https://chrome.google.com/webstore/detail/toozdark/ofeandbogmiogflfhknohbgmgpefpdke">
            <template v-slot:title>ToozDark</template>
            <template v-slot:desc>A chrome extension that adds a darkmode for the <a href="https://youtooz.com">youtooz website</a>.</template>
        </project> -->
    </div>
</template>

<script>
import Project from "@/components/Project.vue";

export default {
    components: {
        Project
    },
}
</script>
