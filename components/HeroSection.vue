<template>
    <div 
        class="h-screen bg-[url('mountain_green.jpg')] 
        bg-cover bg-center relative flex flex-col justify-center px-12">

        <div class="bg-black/50 absolute inset-0 z-0" />
        <div class="absolute left-0 top-0 w-full"><HeaderComponent /></div>

        <h4 class="text-white xl:text-7xl md:text-5xl  z-10 w-5/6 mt-24 mb-6 leading-tight">
            Embrace the Beauty of Nature: Explore the Wonders of Greenery and Sustainability
        </h4>

        <div class="z-10">
            <input 
                type="text" 
                placeholder="Search An Article" 
                class="rounded-full w-80 py-1.5 px-4 border-none focus:outline-none"
            >
            <button 
                class="ml-4 rounded-full font-semibold bg-white/80 py-1.5 px-6 text-green-800"
            >
                Search
            </button>
        </div>
        
    </div>
</template>
  