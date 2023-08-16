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

