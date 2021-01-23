# About Project

This is a simple example of what I can do from scratch for people, who need personal web site (portfolio).

__Was it a challange ?__ It was! Let me break it down for you.
One day I was watching videos on YouTube about UI/UX and suddenly bumped into a video where a web designer was challanging himself. How ? He decided to pick up some random colors, fonts and the idea of a web site in general. Eventually, I liked the idea and wanted to do something similar. So, here is what this project is about(I simplified the challange because I knew in advance what I was going to build:smile:).

### Goals 

* :blush:Create a minimalistic design 
* :sunglasses:Practice new JS libraries

### What I used creating this project

* HTML5
* CSS3
* JS
* JS libraries:
  * typed.js
  * swiper-bundle.js
  * mixitup.js
* Figma 


### Some features that pop up most

* If somebody wants to know how i created typing text, I'll provide with the code down bellow

```JavaScript
<script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>

let typed = new Typed(".typing", {
			strings: ["Freelancer", "Web Developer", "UI/UX Designer", "Photographer"],
			typeSpeed:100,
			backSpeed:60,
			loop:true
		}) 
```
* Here is how I created that cool thing in Project section

```JavaScript
const mixer = mixitup('.portfolio__container', {
		    selectors: {
		        target: '.portfolio__content'
		    },
		    animation: {
		        duration: 400
		    }
		});
```
Then you have to create buttons that take attribute data-filter
```HTML
<div class="portfolio__nav">
     	<span class="portfolio__item" data-filter="all">Все проекты</span>
	<span class="portfolio__item" data-filter=".ux">UI/UX</span>
	<span class="portfolio__item" data-filter=".web">Разработка</span>
	<span class="portfolio__item" data-filter=".photo">Фотосессии</span>
</div>
```
After you have completed last step create elements that you want to mix up and put __mix__ and the name that you provided __data-filter__
```HTML
<div class="portfolio__content mix web">...</div>
<div class="portfolio__content mix ux">...</div>
<div class="portfolio__content mix photo">...</div>
```

### What I have learned
This project does not stand out in the crowd BUT i found some pretty cool stuff that I'll continue to work with:

* :white_check_mark:JS library called __MIXITUP.JS__
* :white_check_mark:JS library called __SWIPER-BUNDLE.JS__

### What I would change about this project

To be honest, I would entirely change the exsisting design. I have one project in my mind(personal portfolio as well) that I'll launch...Idk when:smirk:

For now, as this is my very first project that I show to the world, I want to leave everything the way it is. I want to see how far I can go and how I improve myself throughout the years:muscle:.

### What I do not like about this project

1. I did not line up everything the way I wanted.
2. Do not like the colors I chose.(actually, they chose me as it was the challange:sparkles:)
3. Luck of confidance. I know that I can do better, so, I'll show you in later projects.

### Conclusion
I admit, this is so simple web site, but as anybody else i need to start with something. As i go on, I'll be publishing more and more work and trust me, you'll like what you see.