<template>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-[2vw] grid-flow-row-dense">
        
        <ImageCard class="lg:row-span-2 lg:col-span-2">1</ImageCard>
        <ImageCard v-for="i in 8">{{i+1}}</ImageCard>
        <ImageCard class="lg:row-start-4 lg:row-span-2 lg:col-start-2 lg:col-span-2">10</ImageCard>

        <div class="bg-slate-700 row-start-1 col-start-1 col-span-2 
            lg:row-start-3 lg:col-start-2 lg:col-span-2 
            flex justify-center items-center 
        ">
            <h1 class="text-slate-50 text-4xl md:text-[8vw] leading-none font-bold p-10">Minu portfoolio</h1>
        </div>
    </div>

</template>