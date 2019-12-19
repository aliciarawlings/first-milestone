                                             Natural Healings Skincare

This is my user centric frontend development milestone project. This site is prototype for an upcoming natural skincare line. For now, its functionality is limited as there is no backend implemented. 



Strategy:
My goal is to design a page that makes it easy for customers to browse products on. The page is to be simplistic and user friendly. Its purpose is to provide consumers with a platform that has product and company information. 

Scope:
For aspiring customers, I want to provide a page that allows them to browse products in a carefree, easy way. As the company only has a presence on social media they can only portray themselves in a generic manner, furthermore not offering a way for users to purchase their goods. This page is going to act like Natural Healings Skincare online business card. 

Structure:
The opening page is a short introduction to what the company is and what their products entail. A fixed navbar was implemented to allow the user to browse through each page without having to always scroll back up to the top. 
A contact form is made available for users who may have any questions or feedback they would like to share. 
For the display of the products I used products cards from bootstrap. Within the products cards I have a “Quick View” option. This creates a smooth and fast way for users to browse. I don’t want users to have to be redirected to a new page each time they want more product information. 
The “Quick View” modal keeps the user on the same page and eliminates the use of the back button. 

For the third page I created a register section for Natural Healings Newsletter. 
Finally I created the footer. I wanted the footer to supply quick access to information for its users. Contained in the footer are icons which also act as links to consumer relevant information. 
The footer includes links to :
•	Social media pages
•	Delivery information
•	Terms and conditions
•	Contact Information
•	Returns Information
Once clicked on they open as modals and supply the user with the relevant information except for the terms and conditions link. I felt that due to the high volume of information within the terms and conditions file that it would be best read it on a full screen which  also opens in a new tab. 

Skeleton:
I created my wireframe using the program Balsamiq. Please find links below.
https://drive.google.com/file/d/1OXogfGja-Op_CDfnWpMtPG_XynT1l3_P/view?usp=sharing



Surface:
For the surface plane I wanted to use a colour scheme that was neutral and simple. The background colour is white with a gradient effect applied to the navbar and the footer. Using the colour pick in developer tools I took the hex #f8ebe3 directly from the logo image, which I then applied to the gradient effect along with white. 
For the typography I used the google fonts library. The font-family ‘Crimson text’ was applied to the text in the navbar, icons, product cards, homepage content register page and reviews. 
‘Dancing script’ was a font family that was a similar style to the main company logo. This font was used for the logo in the Navbar section and also applied to the header of the modals. 
The colour grey was used for all icons and text in the navbar and footer as it gives a classic and modern look to the page. 

Technologies 
•	HTML
•	CSS
•	Bootstrap 4

Features:
Fixed nav bar :
I created the navbar so that it was fixed. Reason being was to enable the user to navigate throughout all three pages. 



Product Cards:
The use of product cards helped keep the page in a tidy and structured environment. This way customers had a clear and defined section for each product. 

Modal/quick view button:
Modals were required to eliminate being redirected to a new page. The quick view button opens up with product details. The user can quickly exit out of the modal with the use of the close button which is located at the header and footer of the modal. 

Contact form:
The contact form is located on the home page. This allows users to send a message to the company.

Register page:
The register page is an email input box followed by a sign up button. Once the email is entered the user is redirected to a new page stating that the registration was successful. 

Font Awesome Icons:
The font awesome icons were used as links to social media aswell as modals for consumer information (delivery info, terms and conditions etc..).
Using a pseudo class the icons change color upon hover. They change from the color grey to purple. This informs the user of their interaction with the icon/links. 




Features Left to Implement:
This page is merely the foundation of whats needed to create a successful, functioning online shop. Next I would like to implement a “Cart” page , which would require the use of javascript and finally a payment page. 



Testing:
The goal of creating a successful landing page prototype was achieved. The client and I are happy with the overall aesthetic appeal along with the navigationally properties. Upon entry to the site, the homepage will inform the user about what the company does, about the products and where to contact the business. 
The navbar contains a home, products and register link. It was laid out in a conventional manner as not to make users surprised or uncertain. The navbar is fixed to allow the user to scroll down the page and still make snappy decisions about where to navigate to next. The logo within the navbar when clicked on returns the user to the home page successfully. 
The contact form and the register form was created with the “required” attribute on each input field. Users cannot submit the form with an invalid email address or unfulfilled personal information (name, message etc..). If they attempt to, an error will occur noting what information is required. The form will not submit without all required fields being completed. Once the form is submitted the user is met with a modal stating that the message had been received. In the case of the registration page the user is redirected to a welcome page. 
All social media pages are linked with the relevant font awesome icons in the navbar and footer. All links are have the “target=”_blank” property which will enable the link to open in a new page. 

All contact and product modals work effectively. If the user clicks on the “quick view” button they will be met with a fade-in modal containing all product information. This was achieved with the use of the modal “id” which was then triggered and directed with the data-target/data-toggle. If the user wishes to “add to cart” a second modal will appear prompting the user if it is to be added or discarded. Within this modal is a quantity box which is set to a minimum of 1. If the user wishes to increase the quantity the can do so via the arrows provided or by typing. If the user decides to cancel the close button is located at the bottom or an “X” is located at the top, Both functioning. 
The site was tested on all popular browsers such as chrome, internet explorer, safari and firefox. Further more it was tested on all popular viewports to ensure accessibility for all users e.g ,iphone 5/6/7/X , Galaxy s5, Ipad, iPad Pro. The site worked on all viewports. Minor adjustments were made for aesthetic purposes therefore some images and text were removed for smaller devices. 


Deployment:

The page is being hosted on GitHub. A new repository was created, the page was then uploaded from the master branch. 


Credits:
•	The cart modal can be found here :
https://mdbootstrap.com/docs/jquery/modals/additional/
  
•	The CSS background-blend-mode used in the “registration complete page” was found here https://tympanus.net/codrops/css_reference/background-blend-mode/.

•	All product images and the logo image were supplied by the client Andra Pavlovska. 

•	All content and marketing content was created by myself. The ingredients list was supplied by Andra. 

•	Information on how to create customer reviews was found here https://bootsnipp.com/snippets





