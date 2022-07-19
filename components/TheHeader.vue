<template id="top">
<div class="relative w-full">
  <header>
    <!-- <div class="bg-[url('~/images/decimus-whitepaper-2-bg4.jpg')] bg-no-repeat bg-[length:1800px_1800px] bg-[position:-1000px_-280px] sm:bg-[length:100%_100%] sm:bg-[position:0px_0px]"> -->
    <div class="bg-[url('/images/background-image-top.jpg')] bg-no-repeat bg-[length:1800px_1800px] bg-[position:-1000px_-280px] sm:bg-[length:100%_100%] sm:bg-[position:0px_0px]">
      <div class="flex flex-col items-center">


        <TheNav />

        <div class="flex w-full items-center relative">

          <div class="flex flex-col w-full mb-[400px] xl:mb-96">
            <div class="flex my-12 h-24 xl:h-40 justify-center">
              <SvgDecimusText />
            </div>

            <div class="hidden md:flex justify-center">
              <div class="w-52 xl:w-96 mb-10">
                <img src="/images/underline-Decimus-Dynamics.png" alt="">
              </div>
            </div>            
          
            <div class="text-2xl xl:text-4xl text-white text-center font-oswald font-bold leading-[2.3rem] xl:leading-[4rem]">
              A collection of 4000<br/>dystopian robots piloted by<br/>chemically enhanced<br/>raccoons.
            </div>
          </div>

          <div class="flex md:hidden absolute w-full bottom-0 justify-center">
            <img src="/images/image-decis-top-mobile.png" alt="">
          </div>

          <div class="hidden md:flex absolute w-full bottom-0 justify-center">
            <img src="/images/image-decis-top-desktop.png" alt="">
          </div>

        </div>

        
        


      </div>
    </div>
    
  </header>
</div>
  
</template>

<script >
export default {
 
}
</script>

<style>

</style>