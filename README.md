<h1 style="text-align: center">The Barbell Gym</h1>

![screenshot_wolfpit_desktop_1](https://user-images.githubusercontent.com/75330172/109046216-67188c00-76cc-11eb-948f-a1b3e74324fb.JPG)

This is my submission for Milestone project 1. The Barbell Gym is the main site for the Barbell Gym business,
an independently owned gym providing various strength and fitness classes and a line of merchandise. The purpose 
of this site is to increase brand awareness, advertise the services and products available and how and where to 
get in touch with the gym.

[View live project here](https://john-wallace89.github.io/MS1-BarbellGym/)

<h3 style="text-align: center">User Experience (UX)</h3>

* User Story 1<br>
As a business, I want to provide an introduction to my business and brand for new
customers 

* User Story 2<br>
As a personal trainer/business I want to provide a bit of background to myself and my
qualifications, so that customers can feel confident in me and my brand.

* User Story 3<br>
As a customer, I want to be able to land on the homepage and know what is the 'Barbell
Gym' who is it for and what does it represent AND who is running it.

* User Story 4<br>
As a customer, I want to know what the facilties for the
Barbell gym like and what is available to me.

* User Story 5<br>
As a customer, I would like to know the location of the 
gym, it's address and it's location on google maps.

* User Story 6<br>
As a business I would like to show potential customers
what facilities are available at the gym and provide the
gym location so the gym is easy to find.

* User Story 7<br>
As a customer I would like to know what services are available
to me, what they include and how much they are.

* User Story 8<br>
As a customer I want to know when I can access these services and how I can enquire about 
them.

* User Story 9<br>
As a business, I want customers to see the range of services
provided, how much they cost, when they're happening, and how to enquire about them.

* User Story 10<br>
As a customer, I want to see the what merchandise is available from
and how I can enquire about obtaining/purchasing this merchandise.

* User Story 11<br>
As a business, I want to be able to advertise the merchandise I have available, provide
information on this merchandise and advise clients how they it be obtained.

<h3>Design</h3>

* Colour scheme - Main colours of the site are black and white, inkeeping with the brand logo and colour scheme.

* Typography - Big shoulders stencil text has been used for titles as it is eye-catching and brings a different
dimension to a black & white site. back-up is Sans-serif, should either of the other fonts fail to load.

* Imagery - The logo/hero image is used to promote brand awareness. It is permanently fixed in the middle of the header
to draw the attention of the user back to the brand as they navigate through the site. We've also incorporated images
of the gym and classes as well as the business owner to support user stories 1 - 11. All images uploaded are donated
by the Barbell Gym business, with exception of the background image for the header which is from freepik.com
(see credits/references).

* WireFrames:
Desktop and Mobile wireframes - https://marvelapp.com/prototype/6h5e3i4

* Features:
Responsive layout on mobile and tablet

<h3>Technologies:</h3>

* Languages - 
HTML5
CSS3

* Frameworks/libraries/programs - 
  https://favicon.io/favicon-converter/ - Used to create logo for title.

  https://www.rawpixel.com/image/2337562/free-illustration-png-frame-black-texture - Used for background image.

  https://fonts.google.com/ - used for font design.

  Bootstrap 4.3.1 - https://getbootstrap.com/docs/4.3/getting-started/introduction/ - used to help with responsiveness
  of the site as the JS query for the hover inmation on the nav bar.

  W3 schools.com - https://www.w3schools.com/howto/howto_css_zoom_hover.asp used for hover animation for social links 
  in footer.

  Free formatter - https://www.freeformatter.com/css-beautifier.html used to beautify CSS3 code

<h1 style="text-align: center">Testing</h1>

The W3C Markup Validator and W3C CSS Validator Services were used to validate the project pages to ensure there were no syntax errors.

* [W3C Markup validator](https://validator.w3.org/#validate_by_input)

Results picked up 'illegal' characters in the favicon linked images in the head - these were update with an acceptable naming convention.<br>
Results picked up possible misuse of aria-label attribute - these were removed from the head of all pages.<br>
Results picked up obsolete attribute assigned to iframe element in barbellgym.html - attribute removed.<br>
Results picked up missing alt attrtibute from img element in barbellclasses.html - alt added.<br>
Results picked up unexpected characters '%' and 'px' against height and width attributes assigned to iframe element - width and height removed
from html and styled against class/element in css.
Results advised 'h1' element should only be used top level heading only - page updated so only 1 header has 'h1' tag and others have 'h2'.<br>


* [W3C CSS validator](https://jigsaw.w3.org/css-validator/validator)

No errors were found

<h3>Testing user stories</h3>

1. [Home](https://john-wallace89.github.io/MS1-BarbellGym/index.html)
2. [The Wolf Pit](https://john-wallace89.github.io/MS1-BarbellGym/barbellgym.html)
3. [What We Do](https://john-wallace89.github.io/MS1-BarbellGym/barbellclasses.html)
4. [Barbell Gear](https://john-wallace89.github.io/MS1-BarbellGym/barbellgear.html)
5. [Contact Us](https://john-wallace89.github.io/MS1-BarbellGym/contactus.html)<br>

* User Story 1<br>
   *As a business, I want to provide an introduction to my business and brand for new
   customers.*

   i. As you land on the homepage you are presented with the business brand (logo and color scheme) followed by
   an introductory message about the business, the ethos and accompanying images. You can see the site is 
   structured around the brand.

   ![screenshot_home_desktop_1](https://user-images.githubusercontent.com/75330172/109138010-cc629080-7751-11eb-8d99-3e4fcd986c09.JPG)
   ![screenshot_home_pixel2_1](https://user-images.githubusercontent.com/75330172/109138264-16e40d00-7752-11eb-8494-ed826f3a4150.JPG)

* User Story 2<br>
   *As a personal trainer/business I want to provide a bit of background to myself and my
   qualifications, so that customers can feel confident in me and my brand.*

   ii. As a customer lands on the homepage, there is an introduction to both the business and the business
   owner, with details about the owners experience and qualifications in order to provide confidence in the
   product.

   ![screenshot_home_desktop_2](https://user-images.githubusercontent.com/75330172/109138436-4430bb00-7752-11eb-9db1-1500b5f21ae2.JPG)
![screenshot_home_pixel2_3](https://user-images.githubusercontent.com/75330172/109138469-4e52b980-7752-11eb-849e-6551c597a820.JPG)

* User Story 3<br>
   *As a customer, I want to be able to land on the homepage and know what is the 'Barbell
   Gym' who is it for and what does it represent AND who is running it.*

   iii. As a customer, you land on the image immediatley are shown the brand and what the business is.
   As you scroll through the homepage you are provided with text providing more detail on what the business
   is and wo runs it.

   ![screenshot_home_Ipadpro_1](https://user-images.githubusercontent.com/75330172/109138677-878b2980-7752-11eb-839a-b9badc207f8e.JPG)

* User Story 4<br>
     As a customer, I want to know what the facilties for the
     Barbell gym like and what is available to me.

     i. As a customer, I navigate to the 'The Wolf Pit' page and i'm presented with a slideshow of images
     of the gym so I can see waht it looks like and what equipment is there. this is followed by text describing
     what kind of gym it is.  

     ![screenshot_wolfpit_desktop_2a](https://user-images.githubusercontent.com/75330172/109140703-c8843d80-7754-11eb-89a6-b115c9051ee9.JPG)
     ![screenshot_wolfpit_desktop_2b](https://user-images.githubusercontent.com/75330172/109140715-ccb05b00-7754-11eb-9e7d-d23603147200.JPG)
     ![screenshot_wolfpit_desktop_2c](https://user-images.githubusercontent.com/75330172/109140724-cf12b500-7754-11eb-9bfe-816e6ebf9dc8.JPG)

* User Story 5<br>
     As a customer, I would like to know the location of the 
     gym, it's address and it's location on google maps.

     ii. As a customer on the 'The Wolf Pit' gym, When I scroll down, I can see a clear section labelled 'Location'
     with the address and embedded google maps with the location of the gym so I can see exactly where the gym is located.

* User Story 6<br>
     As a business I would like to show potential customers
     what facilities are available at the gym and provide the
     gym location so the gym is easy to find.

     iii. As a business, the location of my business is clearly presented on an embedded google maps, and
     the address is provided.     

     ![screenshot_wolfpit_desktop_3](https://user-images.githubusercontent.com/75330172/109140838-efdb0a80-7754-11eb-8bd7-fbed72c30f74.JPG)
     ![screenshot_wolfpit_iphone5_3](https://user-images.githubusercontent.com/75330172/109140856-f5d0eb80-7754-11eb-83ca-93e9bce7af2f.JPG)

* User Story 7<br>
     As a customer I would like to know what services are available
     to me, what they include and how much they are.

     i. As a customer, as I navigate to the 'What We Do' page of the site, i'm presented with a strong introduction
     informing me of what I need to succeed in my fitness goals, followed by information on the variety of classes.
     As I scroll down I can see a detailed description of each class on offer with accompanying images of progress
     photos from existing clients and images from the class building confidence in the service being provided and
     what I can expect if I attend. This is followed by the duration and cost highlighted in bold font to draw my 
     attention to essential information.

     ![screenshot_whatwedo_desktop_3](https://user-images.githubusercontent.com/75330172/109141398-9aebc400-7755-11eb-9780-415cae3d2773.JPG)
     ![screenshot_whatwedo_desktop_4](https://user-images.githubusercontent.com/75330172/109141406-9d4e1e00-7755-11eb-94d0-5c61f688e544.JPG)
     ![screenshot_whatwedo_IphoneX_6](https://user-images.githubusercontent.com/75330172/109141725-f6b64d00-7755-11eb-903a-fca2d6510de5.JPG)
* User Story 8<br>
     As a customer I want to know when I can access these services and how I can enquire about 
     them.

     ii. As a customer, I can see a link provided beneath each class option with a CTA to 'click here' directing
     me to the contact us page where I can enquire about any of the services provided. This is provided beneath each
     class so the customer does not have to scroll through the whole page if they wish to enquire.

* User Story 9<br>
     As a business, I want customers to see the range of services
     provided, how much they cost, when they're happening, and how to enquire about them.

     iii. As a business, I'm providing a detailed description of each of our signature classes and 121 PT info,
     accompanied by supporting images showing the success of these services. Cost and duration are clearly shown
     beneath each service section, directing customers to the important information.

     ![screenshot_whatwedo_desktop_8](https://user-images.githubusercontent.com/75330172/109141859-1e0d1a00-7756-11eb-9676-3a8f5645aaeb.JPG)
     ![screenshot_whatwedo_IphoneX_4](https://user-images.githubusercontent.com/75330172/109141883-22d1ce00-7756-11eb-84c4-effbbd7afc57.JPG)

* User Story 10<br>
     As a customer, I want to see the what merchandise is available from
     and how I can enquire about obtaining/purchasing this merchandise.

     i. As a customer, when I navigate to the 'Barbell Gear' page, i'm presented with a clear title and a
     video advertising the gear available for purchase. As I scroll down I can see clearly each product, 
     it's price and a link directing us to the contact us page beneath item informing me of how to get in touch if I wish to
     make a purchase.

* User Story 11<br>
     As a business, I want to be able to advertise the merchandise I have available, provide
     information on this merchandise and advise clients how they it be obtained.

     ii. As a business, my products are clearly shown/advertised through the use of imagery and a video.
     the cost and any offer are clear and in bold directing the customers attention to key information,
     with a link to the contac us page beneath each item so the customer doesn't have to scroll through the
     full page to enquire about a product.
    ![screenshot_barbellgear_desktop_1](https://user-images.githubusercontent.com/75330172/109142117-688e9680-7756-11eb-8e6e-eeff0c6ad53f.JPG)
    ![screenshot_barbellgear_desktop_2](https://user-images.githubusercontent.com/75330172/109142123-6a585a00-7756-11eb-8e73-bf70335f6f58.JPG)
    ![screenshot_barbellgear_desktop_4](https://user-images.githubusercontent.com/75330172/109142159-70e6d180-7756-11eb-82ad-ae692c2d8ef7.JPG)
    ![screenshot_barbellgear_desktop_5](https://user-images.githubusercontent.com/75330172/109142212-80feb100-7756-11eb-84bf-6f3f75c54896.JPG)
    ![screenshot_barbellgear_galaxys5_5](https://user-images.githubusercontent.com/75330172/109142239-8a881900-7756-11eb-88af-c2caf1f332dd.JPG)
<h3>Further testing:</h3>
     Tested extensively over a range of devices using dev tools and tested on Safari, Chrome and Edge.
     See screenshots from testing [here](https://github.com/John-wallace89/MS1-BarbellGym/blob/c803cd9a106dbf7ca7308387e5d000bed413bf97/documentation/screenshots).<br>
     Extensive testing was done to ensure there were no broken links.<br>
     Site was shared with product owner and friends for review, issues with user experience.

* Bugs<br>
     3 bugs were found:<br>
     1. Bug - Media query wasn't updated with new file path when CSS was being tidied and
     screenshots folder was removed from assets folder. [screenshot bug 1](https://user-images.githubusercontent.com/75330172/109042123-ba3c1000-76c7-11eb-9d01-9738129987db.JPG).
     Fix - updated file path in media query in CSS.
     2. Bug - Title above video isn't rendering correctly above video on mobile (text is wrapping)
     [screenshot for bug 2](https://user-images.githubusercontent.com/75330172/109042508-30d90d80-76c8-11eb-9eeb-a62048e1d4d8.JPG)
     Fix - created class to target heading making font-size smaller allowing it to render on one line for all devices.
     3. Bug - accidentally deleted warning message from contact us page when updating header for all pages.
     [screenshot for bug 3](https://user-images.githubusercontent.com/75330172/109042857-92997780-76c8-11eb-8ff5-65126ffd1eb4.JPG))
     Fix - added warning message back into contact us page.

* Changes from design: <br>
There were 2 changes from the original designs provided in the wireframes:<br>
1. The nav bar in mobile view is in a grid view and in 2 separate rows in mobile view instead of one
row. This was done so the navigation CTA could remain clear and was a more aesthetically pleasing design.
2. The barbell gear products were displayed in their own row, rather than side by side as shown in the
wireframes. This is because there are 4 product groups total and no shop functionality as of yet, therefore
it seemed more appropriate to make more space for images and information about the products rather than  give
it a typical shop layout.

* Potential enhancements:<br>
1. In order to advertise more of the gym, the CSS slideshows could be replaced with a carousel using JS. This would
allow us to upload more photos of the facilities, gear and classes.
2. The Barbell gear could be turned into a Barbell'Shop' where customers might be able to place orders via the site.
This is dependent on business behaviour going forward.
3. 1 user enhancement could be the introduction of a booking calendar allowing potential clients to see when classes
start and what slots are available for Personal training sessions allowing bookings to take place.


<h1 style="text-align: center">Deployment</h1>

<h3>GitHub Pages</h3>
The project was deployed to GitHub Pages using the following steps...

<h4>Log in to GitHub and locate the GitHub Repository</h4>

* At the top of the repository section, locate the "Settings" Button on the menu.
* Scroll down the settings page until you find the "GitHub Pages" section.
* Under "Source", click the dropdown and select "Master Branch".The page will refresh.
* Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

<h3>Forking the GitHub Repository</h3>
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

<h4>Log in to GitHub and locate the GitHub Repository<h4>

* At the top of the repository section just above the "Settings" button on the menu, click the "Fork" button.
  The original repository in your GitHub account should now have duplicated.

<h4>Making a Local Clone</h4>

* Log in to GitHub and locate the GitHub repository, under the repository name, click "clone or download".
* To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
* Open Git Bash
* Change the current working directory to the location where you want the cloned directory to be made.
* Type git clone, and then paste the URL you copied in Step 2.
   * $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
* Press Enter. Your local clone will be created.
   * $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.

<h1 style="text-align: center">Credits</h1>

<h3>Code</h3>
Bootstrap4: Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

W3 schools: W3 schools was used to create the alert message on the Contact us page. Tutorial
can be found [here](https://www.w3schools.com/howto/howto_js_alert.asp).

Hyde-design: Hyde-design was used to create the slideshow using CSS3. Tutorial can be found
[here](https://www.hyde-design.co.uk/joomla-bites/80-create-a-css-slideshow-no-javascript-required#:~:text=If%20you're%20only%20after,slideshow%20using%20CSS%20trickery%20alone).

Code Institute: Code institute was referred back to aid in creating the hover animation for the nav bar.



<h3>Content</h3>
All content was written by the developer.


<h3>Media</h3>
All Images were provided by the Product Owner, Gavin Smith and the Barbell Gym with the exception
of the background image was taken from Raw Pixel.

<h3>Acknowledgements</h3>
My mentor Aaron for his support and expertise.


Gavin Smith and the Barbell Gym for trusting me with their brand and letting me use it for this
project.

Tutor support at Code Institute for their support.