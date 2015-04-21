---
layout: page
link: Process
title: Process
order: 3
permalink: /process/
---

##Research

(<a href="https://youtu.be/EHQXXXD_vWQ?list=PLs67-K8l4nrqpTrFnF5J3FfgAG0NugKY7" target="_blank">&larr; Get comfy for a long read</a>)

My first approach to analyzing layout design was to research existing design. I decided to study how web design had evolved over the past twenty years, so I wrote a simple bot that crawled the Internet Archive’s WayBack Machine and generated sequential screenshots of any given website. Using these image sequences as individual frames, I created short stop-motion films of web history.

Unfortunately, since older browsers varied significantly from each other, many web developers resorted to only supporting a single browser and used non-standard, vendor-specific code. This hiccup in web development meant that many of the archive’s snapshots from the early ’00s could not be rendered correctly in a 2014 version of webkit.

[ Stop motion films ]

Explore this way on your own – [get the bot on Github &rarr;](https://github.com/Rumudiez/Web-Archive-Scraper)

These films are intriguing. They are representative of so many things: of screen sizes, web standards, proprietary format wars, vendor-specific features, visual trends, industry changes and more. Significant layout changes are visible and on some of the less active films they are actually very apparent. However, the fluctuant content of most websites makes it difficult to examine them closely.

In order to see these sites’ layouts in a broader, brighter light I needed to simplify the image sequences. Referencing low fidelity wireframes, I outlined several screenshots with simple shapes and lines to test readability. Going from the minimum up, I took note that block-level shapes weren’t descriptive enough to determine the functionality of a site, but adding too many elements that represented more ornamentation than content brought me back to the previous issue of density. I ultimately decided to fill in all advertising spaces, large images and certain interactable elements with solid colors and to only show lines representing text as headlines, navigation, or similarly emphasized content.

[ Layout illustrations ]

Exploring fidelity through reductive illustrations

Now that I had a consistent method to discern structural basics from finished products I could start looking more deeply into specific samples. I drew upon my stop-motion films to look for sites across a theme and with large and generally usable archives. It was important that the sites I chose be similar to each other so that I would later be able to make cross-sectional examinations and determine trends reliably.

I found three sites each with close to twenty years’ worth of archives in the WayBack Machine and all in the same field. It is also noteworthy that AOL, MSN and Yahoo have been heavily invested in over that period of time, ensuring that each update to the site would have been an honest attempt at driving usability and ultimately revenue. The final driving point to choose these three was their prominence in web history. 

AOL is well known for its past as an internet service provider as well as its now-infamous browser (the remnants of Netscape, too). MSN has been an international news source and over time has gained and lost integration with various other Microsoft products, as well as being the default homepage in Internet Explorer, and finally Yahoo, with its early search engine and over half-billion monthly users today, is another internationally known brand.

[ AOL, MSN, Yahoo screenshots ]

The pages of AOL, MSN and Yahoo at their earliest available snapshots on the WayBack Machine

I started investigating these news media through the identification of site redesigns. By isolating these I could pin down the most active periods of web design and track specific points across other factors, such as the most common screen dimensions and wider gamut color support at the time.

[ News media site redesigns ]

These visual updates often resulted in a new user experience through changes to interaction patterns

By looking at every redesign, it’s clear to see that site updates have gotten less frequent as of late. This is an indicator of the changing approach to web design; from small, incremental, public tweaks to behind-the-doors full overhauls (at least visually) with great days of unveiling. There’s much to be said about the benefits of the former method. Namely, it is likely the biggest contributor to the savviness of the average adult web browser today. Developers, designers and users alike all learned how to organize and navigate digital content together as needs and wants grew and they were able to build upon simple interaction techniques one small step at a time; a process which has now led to complex web apps without the expense of reading a tutorial to check your news feed. Users today are expected to know how the web works and are seldom offered help with complicated applications or roundabout interaction flows.

If we narrow the selection down, however, we can find that there are about five major redesigning points in each of these sites' archives. I decided, to help illustrate my research, to use these samples as keyframes for a series of animations showing how layouts have changed over time.

##Creating the animations

Watch the animations: [AOL](/case-studies/aol/), [MSN](/case-studies/msn/) and [Yahoo](/case-studies/yahoo/)

In order to be accurate in as many aspects of my animations as possible, I looked up the most common screen sizes over the past twenty years. The Nielsen Norman Group was an immediate hit and gave a good generalization of the upward trend in screen dimensions. Among other agreeing sources was Statcounter.

Using a slight combination of these sources to get a wider range of data, I picked out the largest average monitor size with a simple share majority around each of my five samples, with the exception of using 1920×1080 pixels for 2015’s samples; the actual most common is still 1366×768 pixels, but that is waning quickly as higher density displays become more and more popular.

In efforts to find suitable audio to accompany the animations, I searched high and low for what I thought would be appropriate (and royalty-free) music. Ultimately, I both felt and was advised to record my own music. Using [a pair of mics](/sources/#recording) and a combination of [audio software](/sources/#recording), I recorded Robert Muczynski’s “[Gallery](/sources/#music)” suite for unaccompanied cello. The pieces within vary naturally, but have of an earnest and jaunty vibe that pairs well with my visual approach.

[View more about my sources &rarr;](/sources/)

##On Continuation and Usage

I believe these definitions of [layout patterns](/#patterns) can be further abstracted into a more flexible and less content-based system of components. Hopefully layout patterns can be utilized in design practice to provide safer methods of experimentation and to help beginners understand just how multifaceted web design can be.