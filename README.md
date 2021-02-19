### About this project
* This project is based on [Jekyl](https://jekyllrb.com/docs/).
* This is a annual conference landing page which keeps all the information.
* I followed through step-by-step tutorial on how to step up my page. (https://jekyllrb.com/docs/step-by-step/01-setup/) .
* Create ```_layouts``` directory on the root which I added  ```default.html``` in the directory.
* I then created ``` _includes``` directory which I added ```navigation.html``` which I created and my navbar content in.
* I then embbed the ``` {% include navigation.html %}``` at the top of ```{{ content }}`` in the body of ``` default.html```. 
* Inside ```index.markdown``` I then changed layout to ```default``` which the file will render the content to ```default.html```.
* Also the ```index.markdown``` is where I am able to change the content of the landing page and render it on  landing page.
* I then went created ```assets``` directory which I have ```images``` and ```css``` folder.


## Instructions

Jekyll requires the following:

-Ruby version 2.4.0 or higher
-RubyGems
-GCC and Make
-See [Requirements](https://jekyllrb.com/docs/installation/#requirements) for guides and details.


1. Install all [prerequisites](https://jekyllrb.com/docs/installation/).

2. Install the jekyll and bundler gems.
```gem install jekyll bundler```

3. Create a new Jekyll site at ```./myblog.```
```jekyll new myblog```
4.Change into your new directory.
```cd myblog```

5. Build the site and make it available on a local server.
```bundle exec jekyll serve```

6. Browse to (http://localhost:4000).


### TODO's /improvements
-I need to improve on the video layout which will make it easy for non-technical person to add their own content.
-Continue to imrove the responivenss of the page.