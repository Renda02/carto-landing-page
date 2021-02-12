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
    <div class="image"><img src="/assets/images/hivan-arvizu-soyhivan-m-anhvw-0-n-ddy-unsplash.jpg" alt="event"></div>
  </div>
</div>
