---
layout: post
title: Housekeeping
---

When I was in high school my computer science teacher assigned us a project where we had to create a website to showcase ourselves and our work, dubbed an <em>“e-portfolio”.</em>

Whereas others had created simple websites with their name and some of their class projects, I had taken the more grandiose approach and wanted a website that looked a bit better. 

I decided to modify a template and hosted it using Github Pages. Using a domain I purchased off namecheap, I created some CNAME and A records and pointed it to Github’s servers. I modified the HTML and CSS for the template and was all set.

I left it as is for a while, but at this point it’s been a few years now and I realized that my website needed an update. It’s outdated and has information from back when I was in high school. Time for a fresh coat of paint.

The first thing I wanted to do is change the domain name. I currently own <em>“dylangarcia.me”, “dylanjcgarcia.com”, and “dylangarcia.rocks” </em>, which are all great but I felt that I could do better. I really wanted a domain name that was just my name but unfortunately someone took <em>“dylan.com”</em> back in 1995 and I don’t have a time machine yet. <em>“dylan.rocks”</em> would’ve been my next choice but unfortunately the .rocks TLD hates Dylan’s and decided to make it a $3000 premium domain. I considered purchasing it but I’ve run out of kidney’s to sell so I settled on <em>“dylan.sh”</em>, which I like because ‘.sh’ is the linux shell script file extension and I’ve always been a fan of British overseas territories.

<img src="images/housekeeping_html_text.png" width="80%" height="80%" style="display: block; margin-left: auto; margin-right: auto;">

I updated all of the information by modifying the HTML in my github repo. It isn’t too much work because it’s just changing the text. I also changed some of the icons and colors just to make it a bit more refined.

At the bottom of the website there’s a “contact” section. The submission section has been broken for a while so it needs to be updated. Because Github Pages only allows for static HTML/CSS/JS, I have to use an external service to accept submissions. I could just use the standard mailto: field but I’d prefer to have the submission section because it feels just a bit more polished.

<img src="images/housekeeping_contact.png" width="80%" height="80%" style="display: block; margin-left: auto; margin-right: auto;">

I used formspree to do this and it allows a message as well as a reply email. I had to modify the form to post to a formspree.io link with an email and message field. Works fine so feel free to try it yourself with a job offer and your company email.

Because my domain is pretty short I decided that I’d like to throw in a URL shortener just for fun. Like I said previously though, Github Pages is static only and I’d rather not build out a whole huge backend so I have it call an API for short.io that I whitelabel with my own domain so that it looks nice but I’m really just a fraud.

<img src="images/housekeeping_urlshortener.png" width="80%" height="80%" style="display: block; margin-left: auto; margin-right: auto;">

I added a textbox for inputting your URL and a button to submit it for shortening. Because they’re slightly different than the other ones I had to add additional CSS for them but that was pretty simple.

I added the script that short.io provides and modified it a bit since it didn’t work exactly right and it didn’t return a hyperlink result. Now whenever I have to send a link to someone I can shorten it to flex my domain name I paid $60 for in a namecheap auction.

For my final trick I opened the site on mobile and realized it was poorly optimized and decided to write a script that removes the URL shortener if viewed on mobile because I figured that’s what was giving me the error I observed. 

<img src="images/mobilescript.png" width="80%" height="80%" style="display: block; margin-left: auto; margin-right: auto;">

It uses the "mobile-detect" library to check if a user is on mobile. I had to include the library first and then create a "MobileDetect" object and call the "mobile()" method to check. While this was successful at removing the shortener, the error still occurred so I guess I have to fix that at some point.

For the blog I considered writing it from scratch but decided I’d rather not have it look like Amazon from the 90’s. I picked out a jekyll theme because Github Pages seems to like it and they tend to use a standard MIT license so I can modify it to my heart’s content. I picked <a href="https://github.com/nicoelayda/celeste">Celeste</a> because it looked nice and I liked the way it has a wave when you hover over the ‘d’ at the top. I modified some things like adding my LinkedIn and Github as well as my vanity email (<a href="mailto:contact@dylan.sh">contact@dylan.sh</a>), and replaced the text with my own. Because capybaras are my favorite animal I decided to ask DALLE to make me some capybaras (be sure to see what happens when you 404 the site). My girlfriend thought they were super cute so I guess that’s a win in my book.

Anywho, now everything is up and running so I have to fill it with posts. Honestly this is mostly just a test blog post to see how everything works out. The goal from here is to link it with my main page so that posts automatically populate on the site. Hopefully this goes well or else I wasted good coffee for nothing. Stay tuned!







