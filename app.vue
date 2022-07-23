<template >
  <body class="bg-black">
    <div class="flex flex-col w-full items-center justify-center">
      <TheHeader />
      <div class="flex flex-col-reverse lg:flex-col">
        <TheLore />
        <TheCollection />
      </div>
      <TheRoadmap />      
      <TheExpeditions />
      <TheTokenomics />
      <TheFooter />
    </div>
  </body> 
</template>

<script>
  export default {
    head() {
      return {
        title: 'Decimus Dynamics',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: '4000 Dystopian robots... piloted by raccoons'
          }
        ]
      }
    }
  }
</script>

<style>

</style>