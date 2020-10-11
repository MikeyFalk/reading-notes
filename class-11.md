# Code 201 Day 11 Reading Notes

## HTML Book

### Chapter 16: "Images" (406 -427)

- You can specify the dimensions of an images with CSS
- Images can be aligned horizontally and vertically 
- background images can be created behind any box on any element on the page
- background images can appear just once or be repeated across the background of the box
- image rollover effects can be created by moving the background of the box
image sprites can be used to reduce the number of images your browser has to load.  

### Chapter 19: "Practical Information" (476 - 492)

SEO - search engine optimization  - practice of helping your site appear nearer to the top of search engine results when people type in a topic that your site is about.

best to figureout keywords peopmight use to find your site and add them to specific places on your site.
 
search engines also look at how many sites link to you 

#### on page techniques

mainly keywords and getting them in HTML, text content, and alt images text.
7  places search engines look: page title; URL/Web address; Headings; Text; Link Text; Image alt text; and Page Descriptions.

How to identify keywords and phrases:
Brainstorm, Organize, Research, Compare, Refine, Map

#### off page techniques
looks at how many and how relevant sites are that link to yours
also looks at words between `<a>` tags in the link to determine if it used keywords instead of just 'click here'

### Site Analytics

- Google Analytics is a good tool for determining how many visitors are coming to your site.
- Need to sign up for an account then you will need to add a tracking code to put on each page on your site

- Google Analytics will give you the following metrics

1. Visits
2. Unique Visits
3. Page Views
4. Pages per Visit
5. Average Time on Site
6. Date Selector- to change time periods of the metrics
7. Export can be used to export the data to be used in excel

- Domain Names - domain names and hosting will be need to put your site on the web

- FTP (File Transfer Protocol) programs allow you to transfer files from your computer to your web server

- There are many companies that provide platforms for blogging, email, newsletters, e-commerce and other tools to save you from writting from scratch.


## MDN Article

- HTML5 comes with elements for embedding rich media in documents `<video>` and `<audio>` which come with their own APIs.

`<controls>` enables the default set of playback controls. It needs to be specified.

-Native browser controls are different in each browser and most aren't keyboard accessible.

you can hide controls and programming your own with HTML, CSS and JavaScript.

`HTMLMediaElement` API provides features to allow you to control video and audio players programmatically

`HTMLMediaElement.play()`, `HTMLMediaElement.pause()` available to both `<audio>` and `<video>` elements

- its a good idea to wrap the whole group in a div element so it can me styled as one unit.

- `<video>` will sometimes contain 2 `<source>` elements so that different formats can be loaded depending on the browser

- `<button>` has class name and `data-icon` attribute for defining what icon should be shown on each button

- `aria-label` attirbute is for accessibility they are used by screen readers.

- give controls `<opacity>` of 0.5 by defualt so they are less distracting.

- buttoms inside the control bar uses flexbox (`display:flex`) to help make alignment easier

- `@font-face` is a custom web font that can be used to create icons. These work better than files and easier to use because you can use text properties to style them.

- good practice to create a JS file specific to the player

- to add the play pause button you need to add `playPauseMedia()` and a listener with `addEventListener('click',playPauseMedia);`

- then use a `if` statement to check if the viedo is paused.

- `stopMedia` is used to add a stop button.

- `mediaBackward()` and `mediaForward` are used to add fast forward and rewind to the player.

- Last step is adding the elapsed time


## Chapter 9 Flash (pp 201 - 206)

overview of flash and why it is less popular now. Not supported in mobile and tablets has issues with accessibility and it cost money to use (Adobe product)


[<-- Back](README.md)