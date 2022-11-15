<template>
    
    <div class="columns-3 gap-2">
        <ImageCard v-for="i in 8" :key="i">
            {{i}}
        </ImageCard>
    </div>

</template>