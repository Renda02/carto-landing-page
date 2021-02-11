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

<h1 class="heading">{{ page.heading | capitalize }}</h1>
<h2 class="sub-heading">{{page.subHeading}}</h2>
<p class="text">{{page.paragraphText}}</p>
<h4 class="paragraph">{{page.paragraph}}</h4>


<style type="text/css">

  h1 {
     width: 441px;
  height: 320px;
  margin: 0 0 44px;
  font-family: Karla;
  font-size: 74px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 0.95;
  letter-spacing: -2px;

  }

  p{  width: 351px;
  height: 281px;
  font-family: Karla;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: normal;
  color: #000000;
}

h2{
      width: 102px;
  height: 52px;
  margin: 0 6px 0 0;
  font-family: Karla;
  font-size: 36px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.44;
  letter-spacing: -1.6px;


}

h4{ width: 322px;
  height: 252px;
  margin: 79px 0 0 103px;
  font-family: Karla;
  font-size: 24px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.5;
  letter-spacing: -0.8px;
  text-align: right;
}

</style>
