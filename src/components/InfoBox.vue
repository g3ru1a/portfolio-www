<template>
    <div class="flex w-full h-screen">
        <div class="flex my-auto w-full md:ml-24 lg:ml-32 xl:ml-44">
            <img class="image" src="@/assets/g3ru1a.png" alt="">
            <div class="my-auto">
                <h1 class="title">Hi, I'm Egidiu, a software developer.</h1>
                <h4 class="subtitle">
                    Here's some of my <a class="subtitle-link">projects</a>.
                </h4>
                <div class="links">
                    <a href="https://github.com/g3ru1a" target="_blank">
                    <img class="link" src="@/assets/icons/github.svg" alt="github icon"></a>

                    <a href="https://www.linkedin.com/in/egidiufarcas/" target="_blank">
                    <img class="link" src="@/assets/icons/linkedin.svg" alt="linkedin icon"></a>
                    
                    <a href="@/assets/cv.pdf" download="egidiu-farcas-resume.pdf">
                    <img class="link" src="@/assets/icons/cv.svg" alt="cv icon"></a>
                </div>
                <div class="contact">
                    <div class="discord">
                        <img class="icon" src="@/assets/icons/discord.svg" alt="discord icon">
                        G3ru1a#1337
                    </div>

                    <p class="email">egidiufarcas@maze.ws</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
    .image{
        @apply hidden lg:block mr-8 h-48 xl:h-64 2xl:h-96 rounded-full my-auto border-4 border-solid border-white;
    }

    .title{
        @apply text-white text-4xxl 2xl:text-6xl leading-snug w-3/4;
    }

    .subtitle {
        @apply my-4 text-gray-300 text-2xxl 2xl:text-4xl font-light;
    }

    .subtitle-link {
        @apply underline;
    }

    .links {
        @apply my-6 w-full flex flex-row;
    }

    .links .link {
        @apply mr-4 w-14;
    }

    .contact{
        @apply text-lg 2xl:text-xl mt-2 w-full flex flex-col items-center text-gray-400;
    }

    .contact .discord {
        @apply w-full flex flex-row;
    }

    .contact .discord .icon {
        @apply mr-4 w-6;
    }
    .contact .email {
        @apply mb-2 w-full text-gray-400;
    }
</style>