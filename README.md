# **Facundo Quintas, Musician.**

## **Website Intro**


This webpage belongs to a pianist. He has a Bachelor of Music Composition Diploma and he offers online or in-person classes.

Users of this website will be able to find information about this musician and his classes: his education, what kind of classes he offers, what people will learn from them, reviews from other students, a video showing a bit of his music, contact information and sing up form. 
**The website is live on Github Pages [Linked Here](https://luquintas11.github.io/FirstProject/index.html)**
 screenshot



## **Features**

The website has three pages:
1. Home
2. Classes
3. Contact form and map location

The navigation and footer featured are present in three pages:

### **Navigation**
* Featured at the top of the page, the navigation shows the name of the teacher in the left corner: Facundo Quintas, Piano lessons.
* The other navigation links are in the right corner: Home, Classes and Contact page. 
* The navigation section has a background color that contracts with the the rest of the website. 

SCREENSHOT

### **Footer**
* The footer includes social media icons to the users can find the teacher facebook, intagram and youtube channel.
* The footer also includes icons that direct the user to the contact form and the map with the teacher location. 
* The footer has the a background color that contracts with the rest of the website. 
Screenshot

1. Home site

* The home site has a main section with a picture of a piano. Embeddeb in this picute there is a small text explaining the teacher education and his motivacion.
* Besides this small text there is a video showing Facundo playing the piano with his band.

screenshot

* Below the main section there is a student reviews section. Each of the review has the student picture. 
screenshot

2. Classes site

* In this page there is a main text explaining what people will learn if they take piano lessons
* Beside the main text there is a small text explaining the diferent lessons modalities either online or in-person. In this small text there is a link that direct the users to the contact form page, encouraging them to make any enquiry they may have. 
screenshot

3. Contact Me site

* In this page there is a contact form that collect  users name, email and any question they may have about the lessons.
* Below the form there is a map with teacher location. 



## Testing

* This page works in different browser: Firefox, Chrome and Internet explore. 
* This page has a proper responsive design that allows to run it in different screen sizes
* The contact form field works: requires entry in every field, only accept and email in the email field, and the submit button works. 

## Bugs

* When I was testing the form I noticed the email field was not requiring an email. Trying to fix this in HTML, the CSS broke down as the screenshot shows. Fortunately I was able to fix it later on.


   screenshot


## ** Validator Testing**


* HTML: No errors were returned when passing through the official W3C validator. 
* CSS:  No errorrs were returned when passing through the  official (jigsaw) validator. 
screenshot 

## Lighthouse report

When I run the lighthouse report, on mobile and desktop, it showed the same problem every time; the perfomance score was not good enough. I had three main option to improve this: 
                                              1. Serve static assets with an efficient cache policy: I talked about this with my mentor and we concluded that the caching policy is defined by server. In this case, github  pages is defining the duration which can't be controlled.
                                              2. Serve images in next-gen formats: Each of the pictures were transform from jpg format to WebP format
                                              3. Properly size images: the image [../image/Woman.jpeg] was resize
                                              4. Preconnect to required origins: the attribute <link rel=preconnect> was added to the video and to the src="https://kit.fontawesome.com/a3bbce37e5.js".
                                              

















