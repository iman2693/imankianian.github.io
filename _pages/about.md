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

I'm a student and researcher currently pursuing a master's degree in Computer Science at the University of Tehran. With a solid foundation in Computer Science, my passion for tackling intricate questions led me into the captivating realms of Artificial Intelligence. I specialize in Computer Vision and Natural Language Processing, where I've skillfully honed my expertise and deepened my understanding. Fuelled by an unquenchable thirst for knowledge, I'm always chasing the thrill of the next big discovery. Additionally, I have an open embrace for new subjects and welcome the opportunity to venture into uncharted territories, further expanding my horizons in the ever-evolving landscape of AI and Computer Science. therefore, I'm eagerly motivated to continue my graduate studies at one of the top universities, under the supervision of the best professors in the world.

About Me
======
I am Iman Kianian who was born in Rasht, A metropolitan northern city of Iran. This city has a humid and forested climate and 

Background
======
My educational journey commenced at Shapour High School, an institution with a rich history of producing remarkable alumni such as Prof. Samii, Dr. Mohammad Moein, and Dr. Fazlollah Reza. These distinguished individuals served as an ongoing source of inspiration during my formative years. Following this, I pursued my Bachelor's degree at the University of Guilan, Northern Iran's most prominent educational institution, boasting a student body of over 18,000. I was privileged to be recognized as one of the top three undergraduate students. Subsequently, I secured admission to the University of Tehran, Iran's foremost university, where I saw myself in the field of Artificial Intelligence. These educational milestones have significantly shaped my academic journey, and the association with such illustrious alumni has continuously motivated me to excel in the field of AI.

Research Field and Interest
======
My main areas of interest in the field of study are computer vision tasks including video and image saliency prediction and medical image analysis. I have a significant interest in investigating the various transdisciplinary sectors where computer vision is used like autonomous driving. Additionally, during my college studies, I became passionate about object and face detection, face recognition, etc. I was passionate about exploring new computer vision frontiers, but time and resource restrictions prevented me from delving into other topics. However, I continue to be enthusiastic as I foster a genuine desire and goal to broaden and enlarge my experiences. In addition, I am particularly interested in combining computer vision and Natural Language Processing (NLP), as I can see fascinating applications like optical character recognition (OCR) and handwriting recognition.
