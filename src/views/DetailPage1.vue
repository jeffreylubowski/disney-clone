<template>
  <div class="min-h-screen bg-cover" :style="{ backgroundImage: `url('${background}')` }">
    <div class="pt-32 pl-8 mb-2">
      <img src="@/assets/captain_marvel_logo.png" alt="logo" class="w-96">
    </div>


    <div class="pl-16 mb-4">
      <button class="px-6 py-2 bg-white text-black font-bold uppercase rounded flex items-center hover:bg-gray-300">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"></path><path d="M0 0h24v24H0z" fill="none"></path></svg>
        <span class="pl-1">Play</span>
      </button>
    </div>

    <div class="pl-16 text-gray-500 mb-8">
      PG-13 &middot; 2019 &middot; 2h 4m &middot; Action, Adventure, Science Fiction
    </div>

    <div class="w-96 xl:w-1/3 pl-16 text-white leading-loose">
      Captain Marvel is an extraterrestrial Kree warrior who finds herself caught in the middle of an intergalactic battle between her people and the Skrulls. Living on Earth in 1995, she keeps having recurring memories of another life as U.S. Air Force pilot Carol Danvers. With help from Nick Fury, Captain Marvel tries to uncover the secrets of her past while harnessing her special superpowers to end the war with the evil Skrulls.
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        background: require('../assets/captain_marvel_background.jpg')
      }
    }
  }
</script>

