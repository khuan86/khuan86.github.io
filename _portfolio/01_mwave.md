---
title: "Mwave"
excerpt: "Redesign checkout for one of Australia's leading online PC stores"
header:
  image:
  teaser: /assets/images/mwavethumb.png
sidebar:
  - title: "Role"
    text: "UX/UI Design, Product Management"
  - title: "tl;dr"
    text: "Designed a less confusing checkout for new and existing customers. The end result is a clean, focused and fast checkout that is simple to follow and understand whilst maintaining the brand."
  - title: "Tools"
    text: "Balsamiq, Photoshop"
  - title: "Year"
    text: "2017"
gallery:
  - url: /assets/images/after-mwave_checkout-welcome.png
    image_path: assets/images/previews_mwave-chkout-welcome-min.jpg
    alt: "Welcome page"
  - url: /assets/images/after-mwave_checkout-newuser-delivery.png
    image_path: assets/images/previews_mwave-chkout-newusr-del-min.jpg
    alt: "Page after creating an account for new user"
  - url: /assets/images/after-mwave_checkout-existinguser-payment.png
    image_path: /assets/images/previews_mwave-chkout-oldusr-del-min.jpg
    alt: "Existing user screen after filling in required information"
  - url: /assets/images/before-mwavecheckout.png
    image_path: assets/images/previews_mwave-before-min.jpg
    alt: "Before redesigned"
  - url: /assets/images/before-mwavecheckout2.png
    image_path: /assets/images/previews_mwave-before2-min.jpg
    alt: "Payment page before redesigned"
  - url: /assets/images/wireframe-mwave-checkout-step3.png
    image_path: assets/images/previews_mwave-wf-min.jpg
    alt: "Wireframe"
  - url: /assets/images/wireframe-mwave-mobile-tablet-view.png
    image_path: assets/images/previews_mwave-wf-tablet-min.jpg
    alt: "Wireframe for tablet/mobile view"
---

{% include gallery %}

## Problem

The old checkout flow is quite clunky and all over the place. There were too many steps to achieve a simple goal: purchase the items quickly and painlessly. It was also not responsive, therefore making mobile transactions very frustrating to use.

The previous design was a copy of Amazon's checkout. While it may have worked at the time as a quick fix, over time with additions to the checkout such as mwave dollars (store credit) and various delivery options, the checkout became too cumbersome to navigate and confusing for newer users.

The web design was also not aligned with the rest of their branding eg. different button styles. Font sizes were all varied, some sections were not aligned properly etc. It definitely required a much needed "designer's touch".

## Solution

#### UX
Many users (such as myself) tend to forget they've already made an account with a website. During the checkout process, you want the user to complete their transaction as soon as possible, so instead of having two columns asking the user to pick an option (login or create an account), I consolidated this into one simple field: `Please enter your email address`. This simple change meant that the user didn't have to think if they've created an account before or not, thus making it much easier for them to get through checkout and making the checkout process a pleasant experience right from the start. The form will validate whether or not the user already has an account and will present them with the proper step (create or enter your password).

Upon successful login, the user will be presented with delivery information. Existing users should already have their details saved and in most cases, would glance at this section to make sure it's the correct address and move onto the next. New users would have to enter in their address, which would be in the form of an address-lookup, thereby reducing the amount of incorrect addresses being entered. The previous form did not have this and they had many incorrectly delivered parcels, which led to customer dissatisfaction. After entering or selecting their address, they will be presented with delivery methods.

The payment method section has been cleaned up to be clearer and more trustworthy. The only difference is that the mwave dollars (credit) will only display if the user has any on their account. It will not display if the user does not have any. If they choose to use their credit, it will automatically calculate and update how much they have left and display the updated totals.

Once everything is filled in and has been validated by the system, the `Place Order Now` button will become active and the user may place their order.

Basically, the goal of this checkout is to have the user presented with choices as they go down the list and only presenting choices relevant to them. This cuts down a lot of unnecessary fields. For existing users, the average time to checkout were several minutes. With the new checkout, I tested it to be on average around 40 seconds.

#### Design
The purple and yellow colours from the mwave logo has been used throughout the rebrand. The previous design did not have much of a brand personality. This was because they did not make heavy use of colour. I kept in mind throughout the rebrand that the majority of the users of mwave are 20-40 year old males. I did not want to make the website look too *feminine*. Bearing in mind the purple and yellow colours are not what your average male would consider their favourite colours! With this in mind I made liberal use of the purple colour as it is darker and offered better contrast than yellow.

I've paid extra attention to ensure the colour schemes used here is not jarring for the user. I maintained its brand identity whilst keeping it up-to-date with current design trends. With healthy use of white space, text line-spacing and icons, it helped achieved a well balanced design of functionality and aesthetics.

## Before

![mwave checkout before](/assets/images/before-mwavecheckout.png "Checkout before")

----------

![mwave checkout before](/assets/images/before-mwavecheckout2.png "Checkout before")

## After

Welcome screen
![Welcome screen](/assets/images/after-mwave_checkout-welcome.png "Welcome screen")
[(View original size)](/assets/images/after-mwave_checkout-welcome.png)

----------

New user screen after creating an account
![New user screen after creating an account](/assets/images/after-mwave_checkout-newuser-delivery.png "New user screen after creating an account")
[(View original size)](/assets/images/after-mwave_checkout-newuser-delivery.png)

----------

Existing user screen after filling in required information
![Existing user screen after filling in required information](/assets/images/after-mwave_checkout-existinguser-payment.png "Existing user screen after filling in required information")
[(View original size)](/assets/images/after-mwave_checkout-existinguser-payment.png)

## Wireframes

![Checkout mobile wireframe](/assets/images/wireframe-mwave-mobile-tablet-view.png "Checkout mobile wireframe")

----------

![Checkout wireframe](/assets/images/wireframe-mwave-checkout-step3.png "Checkout wireframe")
