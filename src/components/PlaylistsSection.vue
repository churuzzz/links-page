<script setup>
import Playlist from "./Playlist.vue";
</script>
<template>
    <h1 class="bg-white text-center font-bold text-4xl">Playlists</h1>
    <div id="playlists" class="md:px-40 grid grid-cols-2 gap-5 bg-white p-7">
        <Playlist
            playListTitle="Fly With Me"
            playListDescription="Some of my favorite songs in the city-pop genre."
            genres="City Pop, Funk, Jazz, Japanese"
            playListLink="https://music.youtube.com/playlist?list=PL-49DiT_jY9ezuaG_q-RP6kgBgd-s7Cur&si=1iEYSqPw6bMJxvKk"
        />
        <Playlist
            playListTitle="Launching!"
            playListDescription="My favorite mecha OSTs from Evangelion, Gundam, and Gurren Lagann."
            genres="Orchestral, Rock"
            playListLink="https://music.youtube.com/playlist?list=PL-49DiT_jY9fJuFjF50LmbpaCTRqbQZgO&si=DYnkUwBb6sHZ16fR"
        />
        <Playlist
            playListTitle="Speed Speed Racer"
            playListDescription="Get ready to blast off the starting line with some of Project D's Best."
            genres="Eurobeat, Eurobeat, and more Eurobeat"
            playListLink="https://music.youtube.com/playlist?list=PL-49DiT_jY9cvVqb-CdoLvIXmJXRo430s&si=NjG0KInmgvwddkSE"
        />
        <Playlist
            playListTitle="Music Used to Be Ethereal"
            playListDescription="My favorite songs from the 80s and 90s mostly a lot of pop, though."
            genres="Pop, Rock, Disco"
            playListLink="https://music.youtube.com/playlist?list=PL-49DiT_jY9f3JM-63TwsNmXWz5oVRM8U&si=0KxpfNGaCK6Fwzvd"
        />
    </div>
</template>
