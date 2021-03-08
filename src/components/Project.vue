<template>
    <div clas="">
        <div class="p-4 h-full w-full">
            <div class="project-box" :style="{'background-image': 'linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(' + require('@/assets/images/' + image) + ')'}">
                <div class="project-container">
                    <h1 class="lg:hidden project-title">
                            <slot name="title"></slot>
                    </h1>
                    <div class="hidden lg:flex flex-row">
                        <h1 class="project-title">
                            <slot name="title"></slot>
                        </h1>
                        <a v-if="git" :href="git">
                            <i class=" project-icon fab fa-github fa-3x">
                            </i>
                        </a>
                        <a v-if="chrome" :href="chrome">
                            <i class="project-icon fas fa-globe fa-3x"></i>
                        </a>
                        <a v-if="npm" :href="npm">
                            <i class="project-icon fab fa-npm fa-3x"></i>
                        </a>
                    </div>
                    <p class="project-desc"><slot name="desc"></slot></p>
                    <div class="lg:hidden flex flex-row items-center justify-center">
                        <a v-if="git" :href="git">
                            <i class="project-icon fab fa-github fa-3x">
                            </i>
                        </a>
                        <a v-if="chrome" :href="chrome">
                            <i class="project-icon fas fa-globe fa-3x"></i>
                        </a>
                        <a v-if="npm" :href="npm">
                            <i class="project-icon fab fa-npm fa-3x"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: ['image', 'git', 'chrome', 'npm']
}
</script>

<style>

</style>