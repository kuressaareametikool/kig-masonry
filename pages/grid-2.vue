<template>

    <div class="grid grid-cols-8 grid-rows-10 ">
        
        <ImageCard>1</ImageCard>
        <ImageCard class="row-start-3 col-start-2">2</ImageCard>
        <ImageCard class="row-start-1 col-start-6 col-span-3 row-span-3">3</ImageCard>
        <ImageCard class="col-start-1 row-start-4 col-span-2 row-span-2">4</ImageCard>
            
        <div class="col-start-4 row-start-2 row-span-3 col-span-2 z-2
        bg-slate-700 
            flex justify-center items-center
        ">
            <p class="text-slate-50  lg:text-lg p-6">Grid'is võib olla vähem elemente kui gridi "ruute" ja neid saab siis loomin&shy;guliselt paigutada seal sees nagu malelaua nuppe.</p>
        </div>
    </div>

</template>