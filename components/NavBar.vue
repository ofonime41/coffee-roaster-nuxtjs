<template>
    <div class="container md:px-20 px-10">      
    <!-- Section 1 -->
    <section class="flex  justify-between w-full h-full  bg-white mx-auto my-10">
        <nuxt-link to="/" class="md:flex hidden"> 
            <img src="~/static/images/logo.svg" alt="logo">
          </nuxt-link>

      <div class="   ">   
        <nuxt-link to="/" class="flex md:hidden"> 
            <img src="~/static/images/logo.svg" alt="logo">
          </nuxt-link>
    
          <nav id="menu" class="items-center justify-center hidden space-x-8 md:space-y-0 space-y-8 text-gray-200 md:flex md:mt-0 mt-10 ">
              <nuxt-link to="/" class=" text-base font-bold text-gray-700 uppercase transition duration-150 ease hover:text-gray-900  hover:text-green-800">
                  <span class="block">Home</span>
              </nuxt-link >
              <nuxt-link to="/" class=" text-base font-bold text-gray-700 uppercase transition duration-150 ease hover:text-gray-900  hover:text-green-800">
                  <span class="block">About</span>
              </nuxt-link >
              <nuxt-link to="/" class=" text-base font-bold text-gray-700 uppercase transition duration-150 ease hover:text-gray-900  hover:text-green-800">
                  <span class="block">Create Your Plan</span>
              </nuxt-link >
          </nav> 
      </div>
      <!-- Mobile Button -->
      <button id="menu-btn" class="flex items-center justify-center h-full md:hidden" @click=" hambugerMenu">
              <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 8h16M4 16h16"></path>
              </svg>
            </button>
    </section>
    
    </div>
    </template>
    
    <script>
    export default {
        mounted: function() {
     this.hambugerMenu();
  },

  methods:{
    hambugerMenu(){
    const btn = document.getElementById('menu-btn');
    const menu=document.getElementById('menu');
    btn.addEventListener('click',()=>{  
          menu.classList.toggle('hidden')
    })
    }
  }
    
    }
    </script>
    
    <style>
    
    </style>