---
title: "Reflective Post: Style and Content"
categories:
- Reflections
---

This week in ENGL 460 we learned about style and content through CSS. CSS is basically a set of rules that tells your website how you want it to look. This is when you can use your creativity in the coding world. This week's lesson was probably the hardest lesson we've had this semester, but it was also the most rewarding! 

After watching Dr, Pilsch’s screencast, I finally knew where to start. The first thing I did to start this week's activity was figure out how to access the developer tools on my site. In the beginning, I thought if I could just read through the CSS code on Unminify that I wouldn't need the developer tools. I could not have been more wrong. The developer tools are what made editing my blog possible. The tools allowed me to temporarily edit my site and see my edits in real time. This was extremely helpful for editing my scss file later one.  

The first thing I changed on my site was the navigation menu. I wanted to make it horizontal with buttons and change the color. I did this first by editing it in the developer tools. By doing this, I found out that I need to define the classes in both my default.html file and my style.scss file. I did this by adding the navigation list class to my html file. Then, I went to my scss file and added the navigation class with the elements that I wanted to be added to the navigation menu. To make the menu horizontal, I put an inline block display. I also added some other elements to the menu like padding, bold font, and new colors for the text and buttons. I also edited the color of my site’s header and the color of my content. It was somewhat frustrating at first, but once it clicked in my head, it became fairly simple and pretty fun! 

It took me a while to realize but editing the the style of the site followed this basic formula: define the class of the element you are trying to edit in default.html. Then, however you defined it in the html file, add it to the scss file. Then copy and paste the edits from the developer tools. Once I figured out these basic steps, I finally started to get into the flow of using CSS. Not all the edits I made were this simple to figure out, but for the most part, it was that easy. 

One thing that I had trouble with was figuring out how to edit the color of my content’s text without messing up my navigation menu’s text. For some reason, when I would add the main-content class to my scss file, it would edit both. It took a lot of trial-and-error attempts to fix it, but it finally worked out. 

Overall, I am happy with the look of my site now! I am excited to see what else we are going to learn throughout the upcoming weeks. 
