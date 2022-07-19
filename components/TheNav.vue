<template>
    

        <div class="hidden md:flex h-44 md:h-52 xl:h-[246px] 2xl:w-[1740px] bg-[url('/images/background-navigation.png')] bg-contain bg-no-repeat">

            <div class="flex w-full px-28 h-44 lg:h-36 xl:h-56">

                <div class="flex w-full h-28 xl:h-36 2xl:h-48 items-center text-xl xl:text-3xl text-white font-oswald font-bold uppercase focus:outline-none justify-between">
                    <div class="flex w-28 md:w-44 xl:w-60 2xl:w-72 justify-center">
                        <a href="#roadmap">Roadmap</a>
                    </div>
                    <div class="flex w-28 md:w-44 xl:w-60 2xl:w-72 justify-center">
                        <a href="https://issuu.com/decumusdynamicwp/docs/decimus-whitepaper-2.0" target="_blank">Whitepaper</a>
                    </div>
                    

                    <div class="flex w-16 lg:w-24 xl:w-60 2xl:w-72 justify-center">
                        <SvgDecimusHead />
                    </div>
                    
                    <div class="flex w-28 md:w-44 xl:w-60 2xl:w-72 justify-center">
                        <a href="#missioncontrol">Mission Control</a>
                    </div>

                    <div class="flex justify-center w-28 h-7 lg:h-9 md:w-44 xl:w-60 2xl:w-72">
                        <div class="flex w-20 md:w-40 justify-between">
                            <a href="https://discord.com/invite/decimusdynamics" target="_blank"><SvgIconDiscord /></a>
                            <a href="https://magiceden.io/marketplace/decimusdynamics" target="_blank"><SvgIconMagicEden /></a>
                            <a href="https://twitter.com/DecimusDynamic" target="_blank"><SvgIconTwitter /></a>
                        </div>
                        
                    </div>
                </div>

            </div>
            
        </div>

    <div class="flex items-center justify-start content-start py-7">
        <div class="flex md:hidden absolute top-7 left-8">
            <!-- Mobile menu button -->
            <button
            @click="toggle"
            class="inline-flex items-center justify-center rounded-md border-[3px] border-white text-white font-bold focus:outline-none focus:text-white"
            >
            <svg :class="[isOpen ? 'hidden' : 'block', 'h-10 w-10']" stroke="currentColor" fill="none" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
            <svg :class="[isOpen ? 'block' : 'hidden', 'h-10 w-10']" stroke="currentColor" fill="none" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
            </svg>
            </button>
        </div>

        <div class="flex md:hidden">
            <SvgDecimusHeadSmall />
        </div>
        
    </div>
    

    <div :class="[isOpen ? '' : 'hidden', 'md:hidden']">
        <div class="text-white uppercase px-2 pt-2 pb-3 sm:px-3"> 
        <a href="#roadmap" class="mt-1 block px-3 py-2 rounded-md text-base font-medium focus:outline-none">Roadmap</a>
        <a href="https://issuu.com/decumusdynamicwp/docs/decimus-whitepaper-2.0" target="_blank" class="mt-1 block px-3 py-2 rounded-md text-base font-medium focus:outline-none">Whitepaper</a>
        <a href="#missioncontrol" class="mt-1 block px-3 py-2 rounded-md text-base font-medium focus:outline-none">Mission control</a>
        </div>
    </div>
</template>

<script lang="ts">
import SvgIconDiscord from "./SvgIconDiscord.vue"
import SvgIconTwitter from "./SvgIconTwitter.vue";
import SvgIconMagicEden from "./SvgIconMagicEden.vue";
export default {
    data() {
        return {
            isOpen: false
        };
    },
    methods: {
        toggle() {
            this.isOpen = !this.isOpen;
        }
    },
    components: { SvgIconDiscord, SvgIconTwitter, SvgIconMagicEden }
}
</script>

<style>

</style>