---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Community Engagement
subtitle: ""

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Filter on criteria
  filters:
    author: ""
    category: ""
    publication_type: ""
    tag: ""
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 2

gallery_item:
- album: mentorship
  image: image1.jpg
  caption: Mentorship session at Open Dreams Organization, Yaounde, Cameroon
- album: mentorship
  image: image4.jpg
  caption: Mentorship session at Open Dreams Organization, Yaounde, Cameroon
- album: awards
  image: vbetter_breed.jpg
  caption: Youth of the Month, Better Breed Cameroon, December 2020
- album: hobbies
  image: baobab.jpg
  caption: Baobab Leadership Summit Kigali, Rwanda 2018
- album: hobbies
  image: baobab2.jpg
  caption: Baobab Leadership Summit Kigali, Rwanda 2018
---
**Mentorship:** I am very passionate about mentoring and supporting others to realize their true potential. I co-founded [Anansi Mentorship](), with [@Twum-Ampofo](https://www.linkedin.com/in/kofiapeakorang/) and [@Ermyntrude](https://mcfscholars.asu.edu/scholars/phase-ii-scholars/ermyntrude-adjei), together we are helping bridge the gap between students from Universities in Africa and opportunities around the globe. I am also a member of the [Elevate Mentorship program](https://sites.google.com/miafrik.org/elevate/about-us/our-mentors) where I help mentor university students back in Cameroon. At [Open Dreams Organization](https://www.open-dreams.org/), I help high-achieving, low-income high school students from Cameroon in their quest for securing scholarships to pursue a university education.
{{< gallery album="mentorship" >}}

**Tutoring:** When I am not leading mentorship initiatives, I am busy taking part in [initiatives](https://www.linkedin.com/feed/update/urn:li:activity:6607347347779387392/) that build other people's technical skills. I was the lead for Artificial Intelligence at the [KNUST Innovation Centre]() where I led several training initiatives. At Goldman Sachs, I am part of the Career Development Pillar of the Black Engineer's Network, where I help run initiatives to promote black excellence.  These experiences have hugely influenced my decision to pursue a career in academia.
{{< gallery album="tutoring" >}}

**Volunteering:** I took part in a number of community give back iniatives during my time as a [Mastercard Foundation Scholar](https://mastercardfdn.org/all/scholars/). From teaching highschool students to blood donation campaigns. I cherish every opportunity I had to give back to my community and I am looking forward to doing more.
{{< gallery album="community" >}} 

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body>

<h2>Automatic Slideshow</h2>
<p>Change image every 2 seconds:</p>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.facebook.com%2Fomgvoice%2Fphotos%2Fladies-and-gentlemen-meet-mr-hermann-kumbong-the-class-of-2020-overall-best-stud%2F3599974533388005%2F&psig=AOvVaw3DTha6UQ2ff_9Z7oOKs_da&ust=1637953107881000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCIic3vqYtPQCFQAAAAAdAAAAABAD" style="width:100%">
  <div class="text">Caption Text</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="img_snow_wide.jpg" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="img_mountains_wide.jpg" style="width:100%">
  <div class="text">Caption Three</div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>

</body>
</html> 

**Hobbies:** I love to travel, meet like-minded youths and brainstorm on issues facing society. I also love learning about other people's cultures. I am an avid basketball player, you can hit me up for a pickup game but [please mind your ankles](https://youtu.be/OlUe4uzSQD4?t=85) :) . I led my high school team to win the regional basketball tournament  in Cameroon. 
{{< gallery album="hobbies" >}} 

Please feel free to reach out if you want to colloborate on something, I am always open to learning from other people's ideas.  
{{< figure src="albums/hobbies/baobab.jpg" caption="A caption" numbered="true" >}}
