<script setup>
defineProps({
    linkHeader: String,
    hyperLink: String,
    linkSub: String,
    linkFlavor: String,
});
</script>

<template>
    <a :href="hyperLink" target="_blank">
        <div
            class="md:w-120 md:mx-auto flex flex-row p-3 border-black border-2 border-solid rounded-3xl my-5 mx-5 transition bg-zinc-200 hover:bg-slate-800 hover:text-white"
        >
            <slot>
                <img src="https://placehold.co/48x48/png" />
            </slot>
            <div class="mx-4">
                <h1 class="text-md font-bold">{{ linkHeader }}</h1>
                <h1 class="text-sm">{{ linkSub }}</h1>
                <h1 class="text-sm font-light">{{ linkFlavor }}</h1>
            </div>
        </div>
    </a>
</template>
