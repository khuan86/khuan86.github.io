---
title: Mwave
excerpt: Responsive one-page checkout redesign for Australia's largest online tech retailer
header:
  image: 
  teaser: /assets/images/MwaveThumb2x.png
sidebar:
  - title: Role
    text: UX/UI Design
  - title: tl;dr
    text:  Designed a more streamlined responsive checkout for new and existing customers. The end result is a clean, focused and fast checkout that is simple to follow and understand whilst maintaining & strengthening the brand identity.
  - title: Tools
    text: 'Balsamiq, Photoshop, Invision'
  - title: Year
    text: '2017'
gallery:
  - url: /assets/images/1-mwave_checkout-welcome.png
    image_path: assets/images/prev_1-mwave_checkout-welcome.jpg
    alt: Welcome page
  - url: /assets/images/2-mwave_checkout-delivery.png
    image_path: assets/images/prev_2-mwave_checkout-delivery.jpg
    alt: Page after creating an account the new user to enter their shipping details
  - url: /assets/images/3-mwave_checkout-payment.png
    image_path: assets/images/prev_3-mwave_checkout-payment.jpg
    alt: New user payment page/finalisation
  - url: /assets/images/1.2-mwave_checkout-existinguser.png
    image_path: assets/images/prev_1.2-mwave_checkout-existinguser.jpg
    alt: Login page for existing user
  - url: /assets/images/1.3-mwave_checkout-existinguser-selectdel-payment.png
    image_path: /assets/images/prev_1.3-mwave_checkout-existinguser-selectdel-payment.jpg
    alt: Existing user screen after filling in required information
  - url: /assets/images/before-mwavecheckout.png
    image_path: assets/images/previews_mwave-before-min.jpg
    alt: Before redesigned
  - url: /assets/images/before-mwavecheckout2.png
    image_path: /assets/images/previews_mwave-before2-min.jpg
    alt: Payment page before redesigned
  - url: /assets/images/wireframe-mwave-checkout-step3.png
    image_path: assets/images/previews_mwave-wf-min.jpg
    alt: Wireframe
  - url: /assets/images/wireframe-mwave-mobile-tablet-view.png
    image_path: assets/images/previews_mwave-wf-tablet-min.jpg
    alt: Wireframe for tablet/mobile view
published: true
---

## Overview
Mwave is one of Australia's leading online IT stores. The homepage has had a few redesigns in the past, however the checkout has been largely left the same.

{% include gallery %}

<a href="http://bit.ly/2kpfTEF" target="_blank" class="btn btn--large btn--info">View on Invision »</a>

## Problem
The old checkout user flow is quite clunky. There were too many steps to achieve a simple goal: purchase the items quickly and painlessly. It was also not responsive, therefore making mobile transactions very frustrating to use.

The previous design was a copy of Amazon's checkout. While it may have worked at the time as a quick fix, over time with additions to the checkout such as mwave dollars (store credit) and various delivery options, the checkout became too cumbersome to navigate and confusing for newer users.

The design was also not aligned with the rest of their branding eg. different button styles, font sizes were all varied, some sections were not aligned properly etc. It definitely required a much needed "designer's touch".


## Solution

### UX
Many users (such as myself) tend to forget they've already made an account with a website. During the checkout process, you want the user to complete their transaction as soon as possible, so instead of having two columns asking the user to pick an option (login or create an account), I consolidated this into one simple field: `Please enter your email address`.

{% include figure image_path="/assets/images/eg-welcome.png" caption="This simple change meant that the user didn't have to think if they've created an account before or not, thus making it much easier for them to get through checkout and making the checkout process a pleasant experience right from the start." %}

The form will validate whether or not the user already has an account and will present them with the proper step (create or enter your password).

Upon successful login, the user will be presented with delivery information. Existing users will already have their details saved and in most cases, would glance at this section to make sure it's the correct address and move onto the next.

{% include figure image_path="/assets/images/eg-selectaddress.png" caption="Having it displayed like this reduced a [whole page](/assets/images/before-mwavecheckout.png) from the previous design!" %}

New users will have to enter in their address, which would be in the form of an address-lookup, thereby reducing the amount of incorrect addresses being entered. The previous form did not have this and they had many incorrectly delivered parcels, which led to customer dissatisfaction. After entering or selecting their address, they will be presented with delivery methods.

{% include figure image_path="/assets/images/eg-enteraddress.png" caption="Using predictive address look-up search reduces a lot of form fields as well as reducing invalid addresses." %}

The payment method section has been cleaned up to be clearer and more trustworthy. The only difference is that the mwave dollars (credit) will only display if the user has any on their account. It will not display if the user does not have any. If they choose to use their credit, it will automatically calculate and update how much they have left and display the updated totals.

Once everything is filled in and has been validated by the system, the `Place Order Now` button will become active and the user may place their order.

### Design
The purple and yellow colours from the mwave logo has been used throughout the rebrand. The previous design did not have much of a brand personality. This was because they did not make heavy use of colour. I kept in mind throughout the rebrand that the majority of the users of mwave are 20-40 year old males. I did not want to make the website look too feminine. Bearing in mind the purple and yellow colours are not what your average male would consider their favourite colours! With this in mind I made liberal use of the purple colour as it is darker and offered better contrast than yellow.

I've paid extra attention to ensure the colour schemes used here was not jarring for the user. I maintained its brand identity whilst keeping it up-to-date with current design trends. With a healthy use of white space, text line-spacing and icons, the redesign achieved a well balanced design of functionality, usability and aesthetics.

<a href="http://bit.ly/2kpfTEF" target="_blank" class="btn btn--large btn--info">View on Invision »</a>

## Showcase
**Before**
<ul>
  <li><a href="http://bit.ly/2kpfYbr" target="_blank">Selecting your address</a></li>
  <li><a href="http://bit.ly/2lKFVSJ" target="_blank">Selecting shipping options</a></li>
</ul>

**After**
<ul>
  <li><a href="http://bit.ly/2YV3xlE" target="_blank">Welcome screen</a></li>
  <li><a href="http://bit.ly/2KB63Z8" target="_blank">Create a password for new user</a></li>
  <li><a href="http://bit.ly/2MH34Bc" target="_blank">Finalising order for new user</a></li>
  <li><a href="http://bit.ly/2YDkbLy" target="_blank">Enter password for an existing user</a></li>
  <li><a href="http://bit.ly/2YX0Sbm" target="_blank">Finalising order for existing user </a></li>
</ul>

**Wireframes**
<ul>
  <li><a href="http://bit.ly/2k5QLSX" target="_blank">Mobile/tablet view</a></li>
  <li><a href="http://bit.ly/2m5Hg74" target="_blank">Desktop view</a></li>
</ul>
