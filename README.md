# cookie-monster

Who wants cookies?! Let's create the frontend of our website to sell our hottest cookie products!

## Objective

Use **HTML Elements** and **CSS Styling** to create the home page for our cookie site.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of CSS (Selectors, properties).

## Concepts

HTML | Description
-----|------------
HTML | **H** yper **T** ext **M** arkup **L** anguage used to create the structure of web pages.
element | An element is an individual part, or a building block, of a web page.
attribute | A modifier of an element.
div | A container element.
nav | A navigation element.
ul | An unordered list element.
li | A list item element.
img | An image element.
a | A link element.
href | An attribute used to specify the link destination.

CSS | Description
----|------------
CSS | **C** ascading **S** tyle **S** heets that describes how HTML elements are displayed.
margin |  The outer space of an element.
padding | The inner space of an element.
text-align | The alignment of text in an element.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS file
3. Link all of your files correctly.

### Part II HTML

To complete Part II, fulfill the following requirements:

1. Create a ```div``` with a ```class``` of container.
2. **Inside** of this div, create the following 4 elements:
---
  * 1. ```nav``` with an ```id``` of "nav-bar".
    * **Inside** of this nav, create the following:
      * ```ul``` with **3** ```li```
      * Each ```li``` has an ```a``` element
      * Each ```a``` element has the text Home, Cookies, and About Us. Each href attribute will be "#top", #middle" and "#bottom" respectively: Ex. ```<li><a href="#top">Home</a></li>```
---
  * 2. ```div``` with an ```id``` of "top".
    * **Inside** of this div, create an ```img``` of your store's cookies. Find one online!
---
  * 3. ```div``` with an ```id``` of "middle".
    * **Inside** of this div, create 4 more ```div``` elements like below to showcase your 4 hottest cookies!
      * 1. Create a div with an ```id``` of "cookie1".
        * Inside of this ```div```, create an ```h1``` element to give the cookie a name, ```img``` element to give the cookie a picture, and ```h3``` element to give the cookie a price like the example below.

        <div id="cookie1">
          <h1 id="cookie1-title">MnM Cookies</h1>
          <img src="https://greatamericancookies.s3.amazonaws.com/app/uploads/2015/10/OriginalChocChipMM1.png" alt="">
          <h3 id="cookie1-price">$5.23</h3>
        </div>

      * 2. Create a div with an ```id``` of "cookie2".
        * Inside of this ```div```, create an ```h1``` element to give the cookie a name, ```img``` element to give the cookie a picture, and ```h3``` element to give the cookie a price.

      * 3. Create a div with an ```id``` of "cookie3".
        * Inside of this ```div```, create an ```h1``` element to give the cookie a name, ```img``` element to give the cookie a picture, and ```h3``` element to give the cookie a price.

      * 4. Create a div with an ```id``` of "cookie4".
        * Inside of this ```div```, create an ```h1``` element to give the cookie a name, ```img``` element to give the cookie a picture, and ```h3``` element to give the cookie a price.

---

  * 4. ```div``` with an ```id``` of "bottom".
    * **Inside** of this div, create another ```div``` with an ```id``` of "about-us".
      * **Inside** of this new div, create an ```h1```, ```h2```, and ```h3``` element like the ones below. Change up the words to spice up your site!

      <h1>Contact Us!</h1>
      <h2>Email us at cookie@net.com</h2>
      <h3>Follow us on Instagram!</h3>

### Part III CSS

Done with HTML already?! To complete Part III, fulfill the following requirements:

1. Target the ```id``` of "nav-bar".
  * Set the height to 100px.
  * Set the width to 100%.
  * Center the text! *Research how to do that by looking up "center text css" in the search engine!*
  * Add padding so that your text isn't so close to the edge of the page. What is padding? *Research it online https://www.w3schools.com/css/css_padding.asp.*

2. Target the ```li``` element.
  * Take away all of the bullet points! How do we do that? *https://www.w3schools.com/cssref/pr_list-style-type.asp*

3. Target the ```id``` of "top".
  * Center the items! For now, you can use the same technique that you used before.

4. Target the ```id``` of "middle".
  * Center the items! For now, you can use the same technique that you used before.

5. Target the ```id``` of "bottom".
  * Center the items! For now, you can use the same technique that you used before.

Great job!

## Stretch Goals

1. Make this the best cookie selling site ever and choose new fonts, images, and styles to best fit the page. Create a color scheme and figure out how to get the nav bar looking like a real nav bar!
*Hint: Try CSS Flexbox!*

2. Create a button anywhere on your page that says "Buy Now!".
