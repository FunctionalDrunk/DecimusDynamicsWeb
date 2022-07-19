<template>
  <section class=" flex justify-center w-full bg-[url('~/images/background-image-bottom.jpg')] bg-no-repeat bg-cover">
    <div class="max-w-7xl">

      

      <div class="md:hidden flex py-4 px-8 items-end justify-center">
        <img src="/images/graphic-tokenomics-mobile.png" alt="">
      </div>
      <div class="hidden md:flex py-4 px-8 items-end justify-center">
        <img src="/images/graphic-tokenomics-desktop.png" alt="">
      </div>
    
      <div class="flex justify-between py-4 xl:py-24 px-4 items-end">

        <div class="flex justify-start items-start content-start w-20 md:w-56 h-9 md:h-20 overflow-hidden">
          <SvgDeMacLogo />
        </div>
        
        <div class="flex w-20 md:w-56 md:h-44 overflow-hidden justify-center">
          <SvgDecimusFooterLogo />
        </div>
        
        
        <div class="flex w-16 md:w-56 overflow-hidden items-center">

            <div class="hidden md:block font-oswald font-bold text-[#648383] text-xl uppercase">
                <a href="#top">Take me to the top</a>
            </div>
            <div class="h-4 md:h-8">
              <a href="#top"><SvgUpIcon /></a>
            </div>
            
        </div>
        
      </div>
    </div>
    
  </section>
</template>

<script>
export default {

}
</script>

<style>

</style>