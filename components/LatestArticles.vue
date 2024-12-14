<template>
    <div class="p-12 min-h-screen">
        <div>
            <h4 class="text-7xl mb-1">Latest Articles</h4>
            <p class="text-xl">Discover our newest insightes into the world of nature and greenery.</p>
        </div>

        <div class="grid grid-cols-2 gap-6 mt-6">
            <!-- Latest Articles -->
             <div>
                <img 
                    src="/pexels-pixabay-158063.jpg" 
                    alt=""
                    class="object-cover rounded-xl"
                >
                <div class="mt-2">
                    <h5 class="text-4xl">The Healing Power of Forest Bathing</h5>
                    <p class="mt-2 mb-4">
                        Discover how forest bathing reduces stress and boosts well-being by
                        immersing yourself in nature.                    
                    </p>
                    <div class="flex items-center justify-between">
                        <p class="italic">Published on 25 Jul, 2024</p>
                        <p class="border rounded-full px-2">Nature Therapy</p> 
                    </div>
                </div>                
             </div>   
             
             <!-- Older Articles -->
            <div class="flex flex-col gap-6">
                <div class="flex gap-4">
                    <img 
                        src="/pexels-pixabay-147411.jpg" 
                        alt=""
                        class="object-cover rounded-xl h-36 w-36"
                    >
                    <div class="mt-2">
                        <h5 class="text-4xl">How to Create a Green Oasis in Your Home</h5>
                        <p class="mt-2 mb-4">
                            Urban gardening is a popular way to bring nature into your home, and it can be a fun and rewarding experience.                             
                        </p>
                        <div class="flex items-center justify-between">
                            <p class="italic">Published on 20 Jul, 2024</p>
                            <p class="border rounded-full px-2">Sustainable Living</p> 
                        </div>
                    </div>                
                </div>        
                
                <div class="flex gap-4">
                    <img 
                        src="/pexels-pixabay-414837.jpg" 
                        alt=""
                        class="object-cover rounded-xl h-36 w-36"
                    >
                    <div class="mt-2">
                        <h5 class="text-4xl">Top 10 Indoor Plants for Cleaner Air</h5>
                        <p class="mt-2 mb-4">
                            Enhance your home's air quality whith these easy-to-care-for indoor plants, 
                            which can help purify the air around you.
                        </p>
                        <div class="flex items-center justify-between">
                            <p class="italic">Published on 18 Jul, 2024</p>
                            <p class="border rounded-full px-2">Home Improvement</p> 
                        </div>
                    </div>                
                </div>  

                <div class="flex gap-4">
                    <img 
                        src="/pexels-pixabay-158028.jpg" 
                        alt=""
                        class="object-cover rounded-xl h-36 w-36"
                    >
                    <div class="mt-2">
                        <h5 class="text-4xl">The Benefits of Green Roofs</h5>
                        <p class="mt-2 mb-4">
                            Discovery how green roofs can help reduce energy costs, reduce carbon emissions, and improve the air quality in your home.
                        </p>
                        <div class="flex items-center justify-between">
                            <p class="italic">Published on 25 Jul, 2024</p>
                            <p class="border rounded-full px-2">Nature Therapy</p> 
                        </div>
                    </div>                
                </div>  
                
                <button class="rounded-full border font-semibold py-2 px-6 self-center">View All Articles</button>
            </div>
        </div>
    </div>
</template>