---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default

title: Carto landing page

heading: Lorem Ipsum Dolor Conference

subHeading: Online

paragraphText: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa .

paragraph: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
---

<div class="content">

  <div class="left">
  <h1 class="heading">{{ page.heading | capitalize }}</h1>
  <h2 class="sub-heading">{{page.subHeading}}</h2>
  <p class="text">{{page.paragraphText}}</p>
  <h4 class="paragraph">{{page.paragraph}}</h4>
  </div>
  <div class="right"><button>Sign Up</button>
  <div class="media-first">
  <div class="media">
    <div class="image " id="image-first"><img src="/assets/images/first.jpg" alt="event"></div>
    <div class="video">
   <iframe width="390" height="215" src="https://www.youtube.com/embed/oVH3j31pV7Y" frameborder="0" id="video-first" allow="accelerometer; autoplay;  encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
</div>
<div class='media-second'>
<div class="video " ><iframe width="390" height="215" src="https://www.youtube.com/embed/gpS7fAZm1_k" frameborder="0" id="video-last" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

   <div class="image" id="image-second"><img src="/assets/images/second.jpg" alt="event"></div>
</div>

</div>
</div>
