---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
author_profile: false
title: "Complex Systems and Sports Analytics"
lang: en
ref: home
permalink: /en/
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/campo.gif
  actions:
    - label: "Meet us"
      url: "/en/what-we-do/"
excerpt: "King Juan Carlos University (URJC) <br /> [Fuenlabrada Campus](https://maps.app.goo.gl/cmeNMo9FWJqumeA96) / [Móstoles Campus](https://maps.app.goo.gl/AXTKYnZve6CeiVta7) <br /> Community of Madrid, Spain<br /> <button id='toggle-music'>i class='fas fa-spinner fa-spin'></i></button> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> "

---

<!---
Botón para reproducir el audio
-->
<audio id="bg-music" autoplay>
    <source src="{{ '/assets/partido.mp3' | relative_url }}" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
<style>
    #toggle-music {
        background: transparent; /* Transparent background */
        border: none; /* Remove button border */
        font-size: 24px; /* Adjust icon size */
        cursor: pointer;
        color: white; /* Adjust color to fit your design */
        padding: 10px;
    }

    #toggle-music:hover {
        color: #ffcc00; /* Optional: Change color on hover */
    }
</style>

<script>
    document.addEventListener("DOMContentLoaded", function() {
        var audio = document.getElementById("bg-music");
        var button = document.getElementById("toggle-music");

        // Check if user previously paused music
        var isPaused = localStorage.getItem("musicPaused") === "true";

        function updateButton() {
            button.innerHTML = audio.paused
                ? '<i class="fas fa-play"></i>'  // Show Play Icon
                : '<i class="fas fa-pause"></i>'; // Show Pause Icon
        }

        if (!isPaused) {
            audio.play().then(updateButton).catch(() => {
                console.log("Autoplay blocked. User must interact.");
                updateButton();
            });
        } else {
            updateButton();
        }

        button.addEventListener("click", function() {
            if (audio.paused) {
                audio.play();
                localStorage.setItem("musicPaused", "false");
            } else {
                audio.pause();
                localStorage.setItem("musicPaused", "true");
            }
            updateButton();
        });
    });
</script>