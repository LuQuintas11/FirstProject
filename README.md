# **Facundo Quintas, Piano Lessons.**


This webpage belongs to a pianist. He has a Bachelor of Music Composition Diploma and he offers online or in-person classes. This site is aimed to any that want to take piano lessons.

Users of this website will be able to find information about this musician and his classes: his education, what kind of classes he offers, what people will learn from them, reviews from other students, a video showing a bit of his music, contact information and sing up form. 
**The website is live on Github Pages [Linked Here](https://luquintas11.github.io/FirstProject/index.html)**
 screenshot



## **Features**

The website has three pages:
1. Home
2. Classes
3. Contact form and map location

The navigation and footer features are present in the three pages:

### **Navigation**
* Featured at the top of the page, the navigation shows the name of the teacher in the left corner: Facundo Quintas, Piano lessons.
* The other navigation links are in the right corner: Home, Classes and Contact page. 
* The navigation section has a background color that contracts with the the rest of the website. 

![Menu Nav](/assets/image/ReadMe-MenuNav.png)

### **Footer**
* The footer includes social media icons to the users can find the teacher facebook, intagram and youtube channel.
* The footer also includes icons that direct the user to the contact form and the map with the teacher location. 
* The footer has the a background color that contracts with the rest of the website. 


![Footer](/assets/image/ReadMe-Footer.png)

### ** Home site**

* The home site has a main section with a picture of a piano. Embeddeb in this picture there is a small text explaining the teacher education and his motivacion.
* Next to this small text there is a video showing Facundo playing the piano with his band,  offering an eye catching content to grab users attention. 

![Main-Section](/assets/image/ReadMe-Main%20picture.png)

* Below the main section there is a student reviews section. Each of the review has the student picture. 
![Student-Reviews](/assets/image/Readme-StudentReviews.png)

### ** Classes site**

* In this page there is a main text explaining what people will learn if they take piano lessons
* Beside the main text there is a small text explaining the diferent lessons modalities either online or in-person. In this small text there is a link that direct the users to the contact form page, encouraging them to make any enquiry they may have. 
![Classes-site](/assets/image/ReadMe-Classes.png)

### **Contact Me site**

* In this page there is a contact form that collect  users name, email and any question they may have about the lessons.
* Below the form there is a map with teacher location. 

*Contact Form:

![Contact-Form](/assets/image/ReadMe-Contact%20Form.png)

*Map:
![Map](/assets/image/ReadMe-Map.png)


## **Testing**

* This page works in different browser: Firefox, Chrome and Internet explore. 
* This page has a proper responsive design that allows to run it in different screen sizes
* The contact form field works: requires entry in every field, only accept and email in the email field, and the submit button works. 

## **Bugs**

* When I was testing the form I noticed the email field was not requiring an email. Trying to fix this in HTML, the CSS broke down as the screenshot shows. Fortunately I was able to fix it later on.

![Contact Form Bug](/assets/image/ReadMe-Bug.png)



##  **Validator Testing**

* HTML: No errors were returned when passing through the official W3C validator. 
* CSS:  No errorrs were returned when passing through the  official (jigsaw) validator. 

## **Lighthouse report**

When I run the lighthouse report, on mobile and desktop, it showed the same problem every time; the perfomance score was not good enough. I had three main option to improve this: 
                                              1. Serve static assets with an efficient cache policy: I talked about this with my mentor and we concluded that the caching policy is defined by server. In this case, github  pages is defining the duration which can't be controlled.
                                              2. Serve images in next-gen formats: Each of the pictures were transform from jpg format to WebP format
                                              3. Properly size images: the image [../image/Woman.jpeg] was resize
                                              4. Preconnect to required origins: the attribute <rel="preload"> was added to the video and to the src="https://kit.fontawesome.com/a3bbce37e5.js".


![Lighthouse-Test](/assets/image/ReadMe-Perform.png)

* Lighthouse Test once it was fixed:

![LightHouse-Test](/assets/image/ReadMe-Perfom-After.png)

## **Unfixed Bugs**

* The bug "Serve static assets with an efficient cache policy" was not fixed as is not something I can control.

## **Credits **

#### **Media and content**

* The icons in the footer were taken from Font Awesome  https://fontawesome.com/start
* The idea  about how to make a responsive design form was taken from https://www.w3schools.com/
* The images were taken from https://www.pexels.com/
* The font-family was imported from https://fonts.google.com/
* The Facebook video embedded in index.html was taken from https://www.facebook.com/
* The README sample was taken from Coding Club Project. 
* I want to give credits to the students Ionut Ciobanu, David Bowers and my tutor Sandeep Aggarwal. 

## **Deployment**

The site was deployed to GitHub pages using the following steps:

In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here: https://luquintas11.github.io/FirstProject/index.html 




















