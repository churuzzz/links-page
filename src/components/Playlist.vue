<script setup>
defineProps({
    playListTitle: String,
    playListDescription: String,
    genres: String,
    playListLink: String,
});
</script>
<template>
    <a :href="playListLink" target="_blank">
        <div
            class="h-full border-black border-2 border-solid rounded-3xl bg-zinc-200 p-3 transition hover:bg-slate-800 hover:text-white"
        >
            <div class="flex flex-row gap-2">
                <img
                    src="../assets/icons8-youtube-music.svg"
                    alt="youtube music icon"
                    class="w-6"
                />
                <h1 class="text-md font-bold">
                    {{ playListTitle }}
                </h1>
            </div>
            <h1 class="text-sm">{{ playListDescription }}</h1>
            <h1 class="text-sm font-light">{{ genres }}</h1>
        </div>
    </a>
</template>
