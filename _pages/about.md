---
permalink: /
title: "Welcome to my Virtual Home!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<audio src="resources/AboutMe.mp3" id="audio"></audio>
<button class="play-pause-button paused" onclick="play()" id="play">
    <i>P</i>
    <i>l</i>
    <i>a</i>
    <i>y</i>
    <i>use</i>
</button>
<script>
    function play() {
        var audio = document.getElementById('audio');
        var button = document.getElementById("play");
        if(button.classList.contains('playing')) {
            audio.pause();
            button.classList.remove('paused', 'playing');
            button.classList.add('paused');
        } else {
            if(button.classList.contains('paused')) {
                audio.play();
                button.classList.add('playing');
            }
        }
        if(!button.classList.contains('paused')) {
                    button.classList.add('paused');
                }
}
</script>

I'm a student and researcher currently pursuing a master's degree in Computer Science at the University of Tehran. With a solid foundation in Computer Science, my passion for tackling intricate questions led me into the captivating realms of Artificial Intelligence. I specialize in Computer Vision and Natural Language Processing, where I've skillfully honed my expertise and deepened my understanding. Fuelled by an unquenchable thirst for knowledge, I'm always chasing the thrill of the next big discovery. Additionally, I have an open embrace for new subjects and welcome the opportunity to venture into uncharted territories, further expanding my horizons in the ever-evolving landscape of AI and Computer Science.

About Me
======
I am Iman Kianian who was born in Rasht, A metropolitan northern city of Iran. This city has a humid and forested climate and 

Background
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Research Field and Interest
======
My major research field is medical image analysis and other computer vision tasks like video and image saliency prediction. I really like to work on applications of computer vision in the Interdisciplinary fields. I also have been interested in face recognition and object detection fields since I was studying for my bachelor's degree. Unfortunately, Although I really like to research new areas and aspects of computer vision, I had limited time and I could not broaden my horizons in other topics. But I am not tired or hopeless.I have a dream and ambition to make my experiences wider and deeper. I also really like to work on the combination of Natural Language Processing (NLP) with CV, like OCR and handwriting recognition.
