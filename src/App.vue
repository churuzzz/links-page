<script setup>
import Link from "./components/Link.vue";
import PlaylistsSection from "./components/PlaylistsSection.vue";
</script>

<template>
    <main>
        <div class="m-6 p-4 rounded-3xl text-center bg-white">
            <h1 class="text-6xl font-bold">churuzzz</h1>
            <h1>(It's pronounced "churros")</h1>
        </div>
        <div id="links" class="rounded-t-xl py-4 bg-white">
            <h1 class="text-center font-bold text-4xl">Links</h1>
            <Link
                linkHeader="Checkout my projects if you're interested"
                hyperLink="https://github.com/churuzzz"
                linkSub=""
                linkFlavor="github.com/churuzzz"
                ><img src="./assets/icons8-github.svg" alt="github icon"
            /></Link>

            <Link
                linkHeader="I post every now and again!"
                hyperLink="https://bsky.app/profile/chu.ruzzz.dev"
                linkSub=""
                linkFlavor="chu.ruzzz.dev"
                ><img src="./assets/icons8-bluesky.svg" alt="bluesky icon"
            /></Link>

            <Link
                linkHeader="Check out my photos"
                hyperLink="https://www.instagram.com/chu.ruzzz/"
                linkSub=""
                linkFlavor="chu.ruzzz same as everywhere else"
                ><img src="./assets/icons8-instagram.svg" alt="instagram icon"
            /></Link>

            <Link
                linkHeader="Find all my games and add me!"
                hyperLink="https://steamcommunity.com/profiles/76561198297138653"
                linkSub="Find me playing as churuzzz"
                linkFlavor="Friendcode is 336872925"
                ><img src="./assets/icons8-steam.svg" alt="steam icon"
            /></Link>

            <Link
                linkHeader="Add me on Discord if you like!"
                hyperLink="https://discordapp.com/users/287783308023037952"
                linkSub=""
                linkFlavor="chu.ruzzz (lordruzki3084)"
                ><img src="./assets/icons8-discord.svg" alt="discord icon"
            /></Link>

            <Link
                linkHeader="Check my playlists and liked songs"
                hyperLink="https://music.youtube.com/@chu.ruzzzz"
                linkSub=""
                linkFlavor="Mostly a lot of mecha OSTs and city pop."
                ><img
                    src="./assets/icons8-youtube-music.svg"
                    alt="youtube music icon"
            /></Link>
        </div>
        <PlaylistsSection />
    </main>
</template>

<style scoped></style>
