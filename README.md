# Pixelant Layout#

Hi My name is Silvia and I'm a Junior Front End Developer.
In this document I want explain to you how I organize my work and what type of decisione i made during the developement.

## What tecnologies I used?


* HTML 5
* CSS 3
* Bootstrap
* jQuery
* Less
* Google font
* Font face (icons)
* GitHub


## How I organize my work?

As metioned on the pervious list I decide to organize my work using GitHub.
In this way I optaion different vatage:

1. I planned my work with task
2. I could have always controll the project
3. I can show to you my work step by step in the develop branch or the final release in the master branch. You can choose!

With SourceTree I managed all my local work but I prefered to merge every single branch with a puòò request in GitHub.
I also create a custom label to indicate the precise issues I was working. 
Every time I found a bug or something could be better I opened a new issue.

## Important elements

I try to describe here some tecnical decision that I made. 


* Top Menu Icon

With Bootstrap you can use the Glyphicons but for this layout I used a set on custom Icon. I used Font Face on the custom.css
In the same file I import all the css rules in order to have only one file.

<pre><code>
@font-face {
  font-family: 'icons';      
  src: url('../icons/fonts/icons.eot');
  src: url('./icons/fonts/icons.eot?#iefix') format('embedded-opentype'), 
  url('../icons/fonts/icons.woff') format('woff'), 
  url('./icons/fonts/icons.ttf') format('truetype'), 
  url('./icons/fonts/icons.svg#glyphicons_halflingsregular') format('svg');
}

</code></pre>





* Slide show: 

I created a slideshow with an over background that show you some contents. The contents were not resposive and I decide to use a bootstrap class to hide some element on small and extra small device.

On small device will be visible only the button (like "BUY NOW")

![alt text](./img_readme/slideshow-xs.jpg "slideshow-xs")

On medium only the title and the button

![Alt text](./img_readme/slideshow-sm.jpg "slideshow-sm")

On mediuam and large all the three elements

![Alt text](./img_readme/slideshow-lg.jpg "slideshow-lg")


* Control Slideshow

The slideshow don't implement a "next" or "prev" icon in the slideshow.
The user can know how many slides exsist and where is it now thank to the rounded controll over the slide show.

  Gray when the slide is active
  
  Orange for the other slide that are not active now









  




 
