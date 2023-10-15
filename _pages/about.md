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


Iman Kianian is my name, and I was born in Rasht, a large city in northern Iran. a researcher and student at the University of Tehran obtaining a master's in computer science. With a strong background in computer science, I was drawn to the fascinating fields of artificial intelligence by my desire to solve challenging problems. I have expertly developed my knowledge and expanded it in the fields of Computer Vision and Natural Language Processing. I also welcome the chance to explore new topics and keep an open mind, which has helped me broaden my horizons in the field of AI and computer science, which is constantly changing.  I am therefore highly motivated to carry on with my graduate studies at a prestigious university, where I will be supervised by the best teachers in the world. My research interests span a variety of cutting-edge technologies, including computer vision, natural language processing, machine learning, deep learning, and medical image analysis.

Background
======
My educational journey commenced at Shapour High School, an institution with a rich history of producing remarkable alumni such as Prof. Samii, Dr. Mohammad Moein, and Dr. Fazlollah Reza. These distinguished individuals were an ongoing source of inspiration during my formative years. Following this, I pursued my Bachelor's degree at the University of Guilan, Northern Iran's most prominent educational institution, boasting a student body of over 18,000. I was privileged to be recognized as one of the top three undergraduate students. Subsequently, I secured admission to the University of Tehran, Iran's foremost university, where I saw myself in the field of Artificial Intelligence. These educational milestones have significantly shaped my academic journey, and the association with such illustrious alumni has continuously motivated me to excel in the field of AI.

Research Field and Interest
======
My main areas of interest in the field of study are computer vision tasks including video and image saliency prediction and medical image analysis. I have a significant interest in investigating the various transdisciplinary sectors where computer vision is used like autonomous driving. Additionally, during my college studies, I became passionate about object and face detection, face recognition, etc. I was passionate about exploring new computer vision frontiers, but time and resource restrictions prevented me from delving into other topics. However, I continue to be enthusiastic as I foster a genuine desire and goal to broaden and enlarge my experiences. In addition, I am particularly interested in combining computer vision and Natural Language Processing (NLP), as I can see fascinating applications like optical character recognition (OCR) and handwriting recognition.
