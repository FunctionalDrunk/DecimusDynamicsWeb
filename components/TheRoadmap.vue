<template>
<section id="roadmap" class="roadmap-border relative">
  <div class="w-full bg-[url('/images/background-image-roadmap.jpg')] bg-no-repeat">
    <div class="flex flex-col px-8 py-8 items-center text-white font-oswald">
      <h1 class="text-4xl lg:text-6xl my-7 font-bold uppercase">Roadmap</h1>
      
      <div class="grid overflow-hidden grid-cols-1 md:grid-cols-2 lg:grid-cols-3 grid-rows-3 md:grid-rows-2 lg:grid-rows-1 gap-6 md:gap-8 
        text-xl xl:text-3xl leading-normal xl:leading-relaxed py-10
      ">

        <div class="flex flex-col px-8 py-5 xl:py-9 w-[300px] xl:w-[420px] h-[387px] xl:h-[540px] lg:w-72 bg-[url('/images/roadmap-card.png')] bg-contain bg-no-repeat">
          <h2 class="pt-8 pb-6 text-3xl xl:text-5xl font-bold">Phase 1</h2>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-completed.png" alt="">
              </div>
              <span>Launch done</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-completed.png" alt="">
              </div>
              <span>Liquidity Deployment</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-completed.png" alt="">
              </div>
              <span>Staking Platform Launch</span>
          </div>
        </div>
        
        <div class="flex flex-col px-8 py-5 xl:py-9 w-[300px] xl:w-[420px] h-[387px] xl:h-[540px] lg:w-72 bg-[url('/images/roadmap-card.png')] bg-contain bg-no-repeat">
          <h2 class="pt-8 pb-6 text-3xl xl:text-5xl font-bold">Phase 2</h2>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-completed.png" alt="">
              </div>
              <span>Rebranding logo</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-completed.png" alt="">
              </div>
              <span>FFF raffles</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-point.png" alt="">
              </div>
              <span>Expeditions</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-point.png" alt="">
              </div>
              <span>Level system</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-point.png" alt="">
              </div>
              <span>Upgrade system</span>
          </div>
        </div>

        <div class="flex flex-col px-8 py-5 xl:py-9 w-[300px] xl:w-[420px] h-[387px] xl:h-[540px] lg:w-72 bg-[url('/images/roadmap-card.png')] bg-contain bg-no-repeat">
          <h2 class="pt-8 pb-6 text-3xl xl:text-5xl font-bold">Future</h2>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-point.png" alt="">
              </div>
              <span>Mobile fortress collection</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-point.png" alt="">
              </div>
              <span>Special map events</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-point.png" alt="">
              </div>
              <span>Zeon Deci upgrades</span>
          </div>
          <div class="flex mb-4 items-center">
              <div class="h-6 xl:h-8 w-6 xl:w-8 mr-3 xl:mr-4">
                <img src="/images/bullet-point.png" alt="">
              </div>
              <span>Merchandise</span>
          </div>
        </div>

      </div>
    </div>
  </div>
  <div class="absolute -bottom-8 left-2/4 md:left-2/3">
    <img src="/images/img-raccon-welding-roadmap.png" alt="">
  </div>
</section>
  
</template>

<script>
import SvgBulletDone from './SvgBulletDone.vue';
import SvgBullet from './SvgBullet.vue';
export default {
    components: { SvgBulletDone, SvgBullet }
}
</script>

<style>
.roadmap-border {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  font-size: 2em;
  padding: 0.5em 0px 0.5em 0px;
  line-height: 1;
  background-position:  0 0, 0 0, 100% 0, 0 100%;
  background-size: 15px 100%, 100% 15px, 15px 100% , 100% 15px;
  background-repeat: no-repeat;
  background-image:
        repeating-linear-gradient(45deg, transparent, transparent 0px, transparent 0px, transparent 0px), 
        repeating-linear-gradient(135deg, rgb(240, 202, 12), rgb(240, 202, 12) 20px, transparent 10px, transparent 40px),         
        repeating-linear-gradient(225deg, transparent, transparent 0px, transparent 0px, transparent 0px),
        repeating-linear-gradient(315deg, rgb(240, 202, 12), rgb(240, 202, 12) 20px, transparent 10px, transparent 40px);
}

.bullit {
  width: 24px;
  height: 24px;
  border: 3px solid white;
  border-radius: 50%; 
}
.bullit-done {
  width: 24px;
  height: 24px;
  border: 3px solid white;
  background: white;
  border-radius: 50%; 
}
</style>