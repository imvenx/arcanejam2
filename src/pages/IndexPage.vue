<template>
  <div id="cont"
    style="text-align: justify; hyphens: auto; word-break: break-word; color:white; max-width: 1000px; margin: auto; padding: 20px; overflow: hidden;">

    <p style="font-size: 1.8rem">
      <!-- border: 2px solid rgb(147, 196, 196); box-shadow: 0 0 20px white; border-radius: 10px; padding: 1em; -->
      <b>
        Welcome to the ArcaneJam! This is your opportunity to push the boundaries of gaming!
      </b>
    </p>
    <AHeader text="About" />
    <p>
      Here is the basic idea, you have a phone that will be the controller and a PC that is the viewer.
      The phone could be anything, a lantern, a key, a gun, a baseball bat, a steering wheel, an airplane
      control, a classic gamepad, basically is a link between the player and the videogame.
    </p>

    <div style="text-align: center;  position: relative;    width: 100%;    padding-bottom: 56.25%; ">
      <!-- <iframe style="min-width: 60%;" width="auto" height="320"
        src="https://www.youtube.com/embed/-B9HoCHmcl8?si=Jv1ABQ0ghYAkJL0t" title="YouTube video player" frameborder="0"
        allowfullscreen></iframe> -->

      <iframe src="https://www.youtube.com/embed/-B9HoCHmcl8?si=Jv1ABQ0ghYAkJL0t"
        style="  position: absolute;    top: 0;    left: 0;    width: 100%;    height: 100%;" frameborder="0"
        allow="encrypted-media" allowfullscreen>
      </iframe>
    </div>

    <AHeader text="Motivation & What is Arcanepad?" />

    <p>
      <b> Arcanepad </b> is a tool for Unity, Godot and Web that makes life easier when creating
      multi-device apps like the ones for this gamejam, also is a platform that allows to run those games without
      having to install a new desktop and android app for every new game. You can create and
      distribute games that use Arcanepad without an account. You don't need to ask us
      for permission to get a devkit, is our commitment to remain open and dev friendly. Nevertheless, in the future we
      plan to support a way to distribute and sell your apps within Arcanepad.
    </p>

    <AHeader text="How?" />

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));">
      <p>
        I created many examples and mini games, as showcased on the video, so you can get started as soon as possible
        creating awesome games. There is a baseball game, a flying car game, a retro space ship game, and a starter
        template that shows how to use the pointer of our phones, to... paint? shoot? interact? Is your desicion.
        <br>
        <br>
        There is a dedicated tutorial section for each Unity, Godot and Web, you can find it on the
        <a href="https://imvenx.github.io/arcanedocs" target="_blank">ArcaneDocs</a>
      </p>

      <LinkImg link="https://imvenx.github.io/arcanedocs" img="images/ArcaneDocs2.png" />
    </div>

    <p>
      Also I'll be keen to help you if needed, <a href="https://discord.com/invite/6Pr9JBCGXy">go to our Discord</a>,
      there I will be answering questions on the channels: "help", "arcane-dev", "godot", "unity" and "web".
    </p>

    <LinkImg link="https://discord.com/invite/6Pr9JBCGXy" img="images/join-discord.png" />

    <AHeader text="Rules" />

    <p>&#9670; The game uses at least two different screens to work (Example: A controller and a viewer)</p>
    <p>&#9670; The theme is free, you can do whatever you want</p>
    <p>&#9670; You own the rights of the game. </p>
    <p>&#9670; You agree that we can feature your game in videos and in the Arcanepad Home</p>

    <AHeader text="Questions & Answers" />
    <p>&#9670; <b style="text-decoration: underline;">Who can vote?</b> Everyone can vote, the criteria will be
      Creativity, Style, Mechanics, and
      Innovation. </p>
    <p>&#9670; <b style="text-decoration: underline;">Are teams allowed?</b> Yes! </p>
    <p>&#9670; <b style="text-decoration: underline;">Is it mandatory to use Arcanepad?</b> You are not required to use
      Arcanepad, if you prefeer you can
      create the whole networking system on your own, altho realistically that may be very challenging for the time of
      this gamejam, in any case, we encourage you to use Arcanepad but feel free to do all on your own if you prefeer</p>
    <p>&#9670; <b style="text-decoration: underline;">Can I adapt an existing game?</b> Yes, the work will be on the
      controller part and the change in
      mechanics and user experience</p>
    <p>&#9670; <b style="text-decoration: underline;">Can I submit multiple entries?</b> Yes </p>

    <AHeader text="Prize" />
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, max-content)); align-items: center;">

      <div style="max-width: 300px; margin: auto;">
        <LinkImg img="images/prize.png" link="https://arcanepad.com" />
      </div>

      <p>
      <ul>
        &#9670; Projects may be offered to continue development under possible ways of financing
        like teaming up on a crowdfunding or some other possibilities. We are open to talk ways to continue
        collaborating!
      </ul>
      <ul>
        &#9670; There will be a hall of fame on Arcanepad.com or the ArcaneDocs for the winners of the first Arcanejam
        with a
        link to your itch.io profile.
      </ul>
      </p>

    </div>

    <AHeader text="Grand Finale & Live Gaming" />

    <p>
      The submissions will be featured on the main menu of Arcanepad for a period of time, and will be played
      live at Barcelona Afterlife Gaming Bar after the ArcaneJam ends. You don't need to assist to this event to
      participate, but you can join us if you are near to have a fun time trying out some of the games.

      <LinkImg
        link="https://www.google.com/maps/dir//Carrer+de+Mari%C3%A0+Cub%C3%AD,+192,+Sarri%C3%A0-Sant+Gervasi,+08021+Barcelona/@41.3943967,2.1251487,13.75z/data=!4m8!4m7!1m0!1m5!1m1!1s0x12a498764097cb21:0x98060535cdf313d1!2m2!1d2.1437428!2d41.3948647?entry=ttu"
        img="images/afterlife.png" />
    </p>

  </div>
  <!-- <svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
    <rect width="100%" height="100%" fill="black" />
    <circle cx="20" cy="30" r="2" fill="white" />
    <circle cx="50" cy="70" r="1" fill="white" />
    <circle cx="100" cy="50" r="1.5" fill="white" />
    <circle cx="150" cy="100" r="2" fill="white" />
    <circle cx="170" cy="150" r="1" fill="white" />
  </svg> -->
</template>

<script setup lang="ts">
import AHeader from 'src/components/AHeader.vue';
import LinkImg from 'src/components/LinkImg.vue';


</script>

<style scoped>
#cont {
  margin: 5%;
}
</style>
