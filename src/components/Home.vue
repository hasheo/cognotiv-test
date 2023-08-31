<script setup>

</script>

<template>
  <div class="relative group/container w-6/12 m-auto">
    <div class="absolute text-9xl text-yellow-400 font-bold z-10 group-hover/container:scale-110" style="top: -50px; left:-100px">We Create</div>
    <div class="grayscale hover:grayscale-0 overflow-hidden">
      <img class="object-cover transition ease-in-out group-hover/container:scale-110" src="../assets/lightbulb2.jpeg">
    </div>
    <div class="group/awesome" >
      <div class="relative group-hover/awesome:bg-yellow-400">
        <div 
          class="absolute text-7xl transition text-yellow-400 font-bold z-10 uppercase group-hover/container:translate-x-full group-hover/awesome:text-white group-hover/awesome:bg-yellow-400 p-4 -translate-x-full" 
          style="bottom: -50px; left: -100%;"
        >
          awesome things
        </div>
        <div
          class="absolute text-7xl transition text-yellow-400 font-bold p-4 z-10 group-hover/container:-translate-x-[25rem] translate-x-full"
          style="bottom: -65px; right: -50%"
        >
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-24 h-24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
          </svg>
        </div>
      </div>
      
    </div>
  </div>
  
</template>