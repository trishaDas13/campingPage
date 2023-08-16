# campingPage

![1](https://github.com/trishaDas13/campingPage/assets/126088849/ea5e2779-34e8-43d4-be0f-601e9e4a5bb6)
![1a](https://github.com/trishaDas13/campingPage/assets/126088849/50889f9c-8b17-4df3-b730-b2a0e2e8a95a)

Wrapped within a "header" element, a structured navigation bar is designed as follows:

The "navbar" division encompasses the entire navigation bar layout, comprising a "logo" section and a "button" section.

The "logo" area houses a logo text that reads "LOGO" ("h2"), with an anchor ("a") tag that links to "#" and carries the ID "logo1."

The "button" section includes an unordered list ("ul") with the class "right," which aligns the list items to the right-hand side of the navigation bar.

Within the list, each "list" item is styled as a navigation link. The list items include:

"Home" linked to "#home" ("link" class).
"Services" linked to "#service" ("link" class).
"Portfolio" linked to "#portfolio" ("link" class).
"About Us" linked to "#aboutUs" ("link" class).
"Contact Us" linked to "#contactUs" ("link" class).
The structure of the navigation bar is well-organized, with the logo at the left and navigation links aligned to the right. The use of anchor tags allows for smooth navigation to different sections of the webpage. This HTML code effectively creates a header containing a navigation bar with logo and navigation links.

![1b](https://github.com/trishaDas13/campingPage/assets/126088849/5da921ac-09f3-4e04-90f0-d8fe3058f011)
![1c](https://github.com/trishaDas13/campingPage/assets/126088849/b43f44d2-6346-463f-939d-9df0b4a57105)

The .container class:

Occupies 100% width within its containing element.
The body element:

Sets background color to rgb(242, 242, 242).
The .navbar class styles a navigation bar:

Occupies 100% width of the viewport.
Takes up 12% of the viewport height.
Uses flex layout with space-between distribution.
Aligns items vertically centered.
Applies padding of 1.5% vertically and 6.3% horizontally.
Has a background color of rgb(51, 51, 51).
Is fixed in position.
Has a z-index of 5 for stacking.
The .logo class styles the logo section:

Sets width to 10%.
The #logo1 ID selector modifies an element with the ID 'logo1':

Removes text decoration (underline).
Sets text color to white.
Sets font weight to 700 (bold).
Hover state for #logo1:

Adjusts text color to rgba(255, 255, 255, 0.8) for a subtle effect.
The .button class styles a button section:

Sets width to 42.5%.
The .right class:

Uses flex layout with space-between distribution.
The .list class:

Removes the default list-style (bullets) from lists.
The .link class styles hyperlinks:

Removes text decoration (underline).
Sets text color to white.
Hover state for .link:

Adjusts text color to rgba(255, 255, 255, 0.8) when hovered.
These styles contribute to the layout and appearance of the container, navigation bar, logo, button, and links within the webpage. The use of flex layout and consistent colors enhances the visual design of the navigation and content.

![2](https://github.com/trishaDas13/campingPage/assets/126088849/863eb348-2b8a-409f-8a3f-60eed7e4f85c)
![2a](https://github.com/trishaDas13/campingPage/assets/126088849/526fda1e-b4ee-4de5-b753-6e8bbf3dc8eb)
![2b](https://github.com/trishaDas13/campingPage/assets/126088849/aa523d6b-0fc1-4753-b907-03b65c95a8c6)

Contained within a "section" with the class "homepage" and the ID "home," I've structured a segment tailored for the homepage:

The "content" division encapsulates the main content of the section.

Inside the "content," a "text" division holds:

An "h1" tag displaying "Camping Gear and Essentials" as the main heading.
A "p" tag with descriptive text about discovering high-quality camping gear for memorable outdoor adventures.
Additionally, an anchor tag ("a") is provided, leading to the "services" section ("#services") with the text "OUR SERVICES."

This HTML code forms a coherent and engaging section for the homepage, offering a clear headline, descriptive text, and a link to explore further services.

![2c](https://github.com/trishaDas13/campingPage/assets/126088849/6fa81904-8d19-4c7a-8d99-f02713ea140f)
![2d](https://github.com/trishaDas13/campingPage/assets/126088849/b079f9fa-d0c9-4355-8407-4bfd0f715727)

The .homepage class:

Occupies 100% width and 100% viewport height.
Uses an image as a background (url("https://koa.com/blog/images/family-camping-at-sunset.jpg?preset=heroimagecropped")).
Sets background-size to cover, ensuring the image covers the entire container.
Adjusts background-position to center vertically at 65%.
Uses background-attachment as fixed, keeping the background image stationary during scrolling.
Utilizes flex layout with center alignment for content.
Sets position to relative.
The ::before pseudo-element of .homepage:

Creates a pseudo-element in the .homepage container.
Covers the entire area of the container with a semi-transparent black overlay (background: rgba(0, 0, 0, 0.2)).
The .content class within .homepage:

Utilizes flex layout with center alignment.
Spans 85% height of the container.
Spans 70% width of the container.
Adjusts z-index to 3 for layering.
Uses a column flex direction.
The .text class within .homepage:

Adds text shadow for a subtle effect (text-shadow: 0px 0px 10px rgba(0, 0, 0, 0.3)).
Sets text color to white.
Sets font size to 20px.
Aligns text center.
Adds bottom margin of 40px.
The .text h1 selector within .homepage:

Adjusts font size to 60px.
Adds bottom margin of 10px.
The a elements within .homepage:

Removes text decoration (underline).
Sets text color to black.
Sets font size to 18px.
Sets background color to white.
Applies padding of 10px vertically and 30px horizontally.
Adds vertical margin of 10px.
Adds a white border with 2px width and rounded corners (border-radius: 5px).
Applies box shadow for a subtle elevation effect.
Adds transition animation with cubic-bezier easing.
Hover state for a elements within .homepage:

Changes text color to white.
Adjusts background color to semi-transparent white (rgb(255, 255, 255, 0.3)).
These styles contribute to the layout, background image, overlay, content arrangement, and link appearance on the homepage. The use of flex layout and background techniques create an attractive and engaging hero section.
![3](https://github.com/trishaDas13/campingPage/assets/126088849/3fc47db6-4945-473f-a306-40f91f8fcba3)
![3a](https://github.com/trishaDas13/campingPage/assets/126088849/e8c80f3f-df8a-4c3b-9e1d-b5df9d05cb3e)


![3b](https://github.com/trishaDas13/campingPage/assets/126088849/925ab9a4-3c5b-4557-aa34-a621f91d11e2)
![3c](https://github.com/trishaDas13/campingPage/assets/126088849/e6524808-7e58-4023-ba28-3b0a5a24a5ab)
![3d](https://github.com/trishaDas13/campingPage/assets/126088849/a1c51524-2987-47c4-a0ed-7c5d58ab1205)
![3e](https://github.com/trishaDas13/campingPage/assets/126088849/396d8f14-bf18-40d0-883b-16696ef03ddf)

Structured within a "section" element featuring the class "ourService":

A "heading" division carrying the ID "service" introduces the section with:

An "h1" tag displaying "Our Services" as the main heading.
A "p" tag with a descriptive paragraph inviting users to explore the range of camping gear services.
In "div1," a set of three "card" divisions are presented:

Each "card" encapsulates an image sourced from an external link, with an alternate text "error."
Beneath the image, there's an "h3" tag specifying the gear category, followed by a descriptive paragraph about the service.
Similarly, in "div2," another set of three "card" divisions is presented:

The structure mirrors the previous "card" setup, containing an image, a heading, and a descriptive paragraph for each service.
The section is thoughtfully organized to showcase various camping gear services, each accompanied by an image, a heading, and informative text. This HTML code effectively creates a visually appealing and informative section highlighting the range of services offered.

![3f](https://github.com/trishaDas13/campingPage/assets/126088849/ec8d6962-f7cd-4a44-ae00-078e4989d26f)
![3g](https://github.com/trishaDas13/campingPage/assets/126088849/6e336839-bd40-4bf5-bb1e-16fa20d5c2d6)

The .service class:

Removes text decoration (underline).
Sets text color to black.
Does not apply background color.
The .ourService, .about, and .contact classes:

Span 100% width.
Add top margin of 5rem.
The .heading and .heading1 classes:

Align text center.
Add bottom margin of 4rem.
The .div1 and .div2 classes:

Span 88% width.
Occupy 55% of the viewport height.
Center horizontally with margin-inline: auto.
Add top margin of 2rem.
Utilize flex layout with space-between distribution.
The .card class:

Span 31% width.
Occupy 100% height of its container.
Have a white background color.
Apply a box shadow for a subtle elevation effect.
Add padding of 3%.
Align text center.
The .img class:

Set width to 40%.
Set height to 42%.
Apply a circular border radius.
Add vertical margin of 6% and horizontal margin of 0.
The .card > h3 selector within .card:

Set font weight to bold.
Add bottom margin of 1%.
The .card > p selector within .card:

Set font weight to lighter.
These styles contribute to the appearance and layout of service sections, headings, and cards on the webpage. The use of margins, widths, and flex layout ensures consistent spacing and arrangement. Card elements are styled for a clean and appealing presentation of information.

![4](https://github.com/trishaDas13/campingPage/assets/126088849/ddb183c0-6f3c-434b-a5c0-9d88fee63670)
![4a](https://github.com/trishaDas13/campingPage/assets/126088849/536e5af6-04aa-4d08-ab94-e759630ba865)
![4b](https://github.com/trishaDas13/campingPage/assets/126088849/2f3f85e8-1115-4170-9f75-2746793cab63)
![4c](https://github.com/trishaDas13/campingPage/assets/126088849/229e2815-681d-4904-a205-02100d9b851a)

Enclosed within a "section" element having the class "about" and the ID "aboutUs":

The "heading1" division, marked by the "aboutUs" ID, serves as an introduction with:

An "h1" tag displaying "About Us" as the main heading.
A "p" tag with a service-oriented paragraph that invites users to uncover the journey of providing camping services.
Within the "story" division:

An "h3" tag bears the heading "Our Story."
A "p" tag elaborates on the journey, spanning over a decade, of furnishing outdoor enthusiasts with high-quality camping gear and essentials. The commitment to quality and customer satisfaction is emphasized.
In the "mission" segment:

An "h3" tag with the heading "Our Mission."
A "p" tag outlines the mission of equipping outdoor enthusiasts with top-tier camping gear and essentials, enriching their outdoor escapades. The emphasis is on providing reliable, durable, and innovative products.
The "vision" part carries:

An "h3" tag titled "Our Vision."
A "p" tag articulates the vision of becoming a prominent hub for camping enthusiasts, known for premium gear and exceptional service. The aim is to inspire nature exploration and create lasting camping memories.
The "team" division showcases the members:

An "h3" tag with the heading "Our Team."
An unordered list ("ul") contains list items ("li") with individual names and roles.
This HTML code effectively constructs a comprehensive section that acquaints users with the essence of the organization, its journey, mission, vision, and the dedicated team members behind the scenes.

![4d](https://github.com/trishaDas13/campingPage/assets/126088849/c3c7f457-ad5d-44f7-89c5-74e486f32135)

The .card > p selector within .card:

Sets font weight to lighter for the paragraph content within the card.
The .story, .mission, .vision, and .team classes:

Have a width of 87% and centered horizontally with margin: 2% auto.
These classes likely represent sections on the webpage (such as the story, mission, vision, and team sections).
The .heading3 class:

Adds padding to the bottom of elements with this class (padding-bottom: 1rem).
This class is likely applied to subheadings within the sections.
The .list2 class:

Adjusts the position of list item markers within lists (list-style-position: inside).
This class is likely used to align list item markers to the inside of the list container.
The .contact class:

Adds a margin at the bottom to give space for the contact section (margin-bottom: 14vh).
These additional styles enhance the appearance and layout of various sections and elements on the webpage. The use of margins, widths, and other styling properties ensures a consistent and visually appealing design.

![5](https://github.com/trishaDas13/campingPage/assets/126088849/22dcf039-11b3-499b-8b5d-15e14dfef9bb)

![5a](https://github.com/trishaDas13/campingPage/assets/126088849/d79cf951-88fe-4622-8adf-b1f693452068)

![5b](https://github.com/trishaDas13/campingPage/assets/126088849/2a03ecc6-c414-4e41-872e-a5e13bf204b0)

Enclosed within a "footer" division:

The "contactinfo" division showcases the contact details, each contained within separate divisions ("a" to "g"):

In "a," a location_on icon and corresponding address ("123 Campsite Avenue, Wilderness, CA 98765") are displayed.
In "b," an email icon and email address ("info@campinggearexperts.com") are provided.
In "c," a phone icon and contact number ("123-456-7890") are presented.
In "d," "e," and "f," watch_later icons depict the working hours for different days:
Monday - Friday: 9:00 AM - 5:00 PM in "d."
Saturday: 10:00 AM - 3:00 PM in "e."
Sunday: Closed in "f."
In "g," a language icon is followed by a website URL ("www.codingnepalweb.com").
The "form" division accommodates a user contact form:

Input fields include a text field for the user's name, a mail field for email, and a larger textarea for the message.
A "Send Message" button ("button2" class) is provided for submission.
This HTML code effectively constructs a footer segment comprising essential contact information, working hours, and a contact form for user interaction.

![5c](https://github.com/trishaDas13/campingPage/assets/126088849/3f828154-6371-4e61-8ebb-39fb716f6858)
![5d](https://github.com/trishaDas13/campingPage/assets/126088849/325062c1-965c-4eb3-91de-2ddc87471801)

The .contact class:

Adds a margin at the bottom to provide space for the contact section (margin-bottom: 14vh).
The .footer class:

Has a width of 87% and is centered horizontally with margin: 2% auto.
Utilizes flex layout with space-between distribution and vertical alignment.
Likely represents a footer section on the webpage.
The .contactinfo class:

Spans 50% width within its container.
Has a height of 35vh.
Utilizes flex layout with column direction and space-between distribution.
Likely represents a container for contact information.
The .form class:

Spans 50% width within its container.
Likely represents a container for a contact form.
The .material-icons class:

Sets the color of icons to rgb(122, 122, 122).
Icon IDs (#location, #email, #phone, #clock1, #clock2, #clock3, #language):

Sets font size to 16px for various icons.
Classes .a through .g:

Set font size to 16px.
Set width to 70%.
Utilize flex layout with a gap of 18px between items.
input and textarea elements:

Span 90% width within their containers.
Add padding of 1%.
Set font size to 16px.
Add vertical margin of 2% and remove default outline.
Apply a 1px solid border with a gray color.
The .button2 class:

Adds padding of 2% vertically and 4% horizontally.
Sets font size to 16px.
Sets background color to rgb(51, 51, 51).
Sets text color to white.
Removes borders.
Applies border radius of 5px.
Adds left margin of 3.5rem.
Hover state for .button2:

Changes background color to a slightly transparent dark gray (rgba(51, 51, 51, 0.7)).
These additional styles contribute to the appearance and layout of the contact and footer sections, icons, form elements, and buttons on the webpage. The use of flex layout and consistent styling ensures a visually pleasing and user-friendly design.
