# accessible_horiseon
## Accessible Horiseon Website
##### Table of Contents
1. [Overview](#overview)
2. [Importance](#importance)
3. [Steps Taken](#steps-taken)
4. [Motivation](#motivation)
5. [What did I learn](#what-did-i-learn)
6. [Features/Highlights](#features/highlights)
7. [Live URL](#live-url)
8. [GitHub URL](#github-url)

## Overview
A marketing agency sent their website to me to make it more accessible so many people can use the webite. The goal was to consider those who use accessibility features including screen readers or users who  bave slower broadbands to ensure they could view the page and access it without limitations. The website was to remain the same since it is not my original work. 

## Importance 
This is an important task because more and more people have access to the internet including those who have limitations. It's important to include everyone. There are laws stating that websites are accessible. It's important to include accessible features to avoid a potential lawsuit. It's also stated that accessible websites are ranked higher in search engines. Who doesn't want their website to be first?

## Steps Taken
There were many steps taken. According to the Acceptance Criteria, I completed the following
* Used semantic HTML including the following tags: header, main, nav, footer, and section
* Elements are logical
* Alt attributes to all pictures were added.
  * I added an alt attribute to the background image in case it doesn't load. I added it with a title tag.
* Heading tags are in sequential order
* Title element is Concise and Descriptive

I was told the Scout Rule is to:
>"Always leave the code a little cleaner than when I found it."

Therefore, I consolidated the code. Below is how I consolidated the code and the additional changes made.
* Added link to Search Engine Optimization using id tag
* Added a title to be displayed in a tab
* Consolidate code in HTML
  * Removed header class and use a header tag
  * Used nav tag instead of div
  * Removed content class and used a main tag
  * Removed div and used section instead twice
  * For the second section, I named it main_right (benefits will be seen in CSS)
  * Create a key_notes class which will be seen in CSS
  * Deleted three separate classes and consolidated it to benefit class
  * Removed footer class and used footer tag
  * Comments are included
* Consolidate code in CSS
  * Changed .header to header because the class was removed in HTML
  * Changed div to nav 
  * Added max-height to float-left and float-right class because it's an image
  * Changed .content to main tag
  * Changed .benefits class to .main_right because there were three classess with the same properties.
  * Consolidated benefit-lead, benefit-brand, and benefit-cost into one class called benefit because they all shared the same properties
  * Consolidated h3 into one class
  * Consolidated img tags within the benefit class 
  * Consolidate online-reputation-management, social-media-marketing, and search-engine-optimization into one class called .key_notes because all three share the same properities.
  * Consolidated the img tags because they share the same property.
  * Added .key_notes tag to h2
  * Changed footer class to footer tag
  * Comments are included throughout the code

## Motivation
As a person who works with people who have visual impairments, I understand the frustration when websites aren't accessible. I also understand the enjoyment and excitement when a website is accessible and the amount of time it saves trying to navigate a website. It was very important to me to make sure I added as many accessible features as possible.

## What did I learn?
This task was a refactoring of a code. From a web developer stand point, I learned how to manipulate code that's given to me and consolidate it. Even though that doesn't change accessibility, it will simplify editing the website as addtional pages or features are added to the website.

## Features/Highlights
Some highlights include:
* All images have an alt attribute
* Links clicked will go straight to the section

## Live URL
https://whatawhat.github.io/accessible_horiseon/#online-reputation-management


## GitHub URL
<https://whatawhat.github.io/accessible_horiseon/>

