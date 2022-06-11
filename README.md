# Mobile Responsive Boostrap 5 Webpage Template

This template is designed for use as a generalized webpage layout containing elements
common to modern websites. It is built using the Boostrap 5 grid system which utilizes
the CSS flexbox utilities and media queries to approach an opinionated box layout design
and mobile responsive functionality, respectively.

This particular template features common elements such as `header`, `aside`, and the concept
of a masthead. These elements, while common across the web, are presented here
in an opinionated form. Below is a discussion of design choice decisions.

## Demo

A demo version of this template is available at the following URL:

https://www.alpharithms.com/demos/alphaweb/index.html

It reflects the latest updates along with the options `vibes` class applied to the body.

## Mobile Responsiveness

This template uses the Boostrap Grid system to organize content using the standard
CSS Box Model paradigm. It uses media queries to control the widths of elements in 
response to screen widths. These changes accommodate dynamic resizing and alter the page
layout in real time accordingly.

In accord with fusibility standards, the mobile navigation menu has been removed from its
primary location on the navigation bar and is accessible as a modal overlay that
covers the entirety of the screen using absolute positioning and a calculated height
value. This menu is accessible via clicking the "hamburger" menu icon that appears
on the far right of the mobile navigation menu.

## Placeholder Content

Placeholder content has been included in the HTML file as a means to suggest appropriate
use of this template. The removal of this content will not affect the mobile responsiveness
of the containers on the page. HOWEVER, the removal of elements such as the 
menus in the footer area might affect other elements in that same area if not done appropriately.

## Colors
The CSS included in this template has a section containing various colors and size values
for elements on the page. These styles are included in the `vibes` class which is applied
to the main `body` element by default. Removing the `vibes` class will remove these colors
and some specifications for element sizing. Like the placeholder content, the styles conferred
by this class will not affect the mobile responsiveness of any elements if removed -- they are
included as visual tools.

## SASS/SCSS

The CSS styles for this template were generated from a source `.scss` file. It is not required to
use this file but encouraged. The mapping file and source file are included in this repository
for debugging and development purposes. The `.css` file is the one loaded into the page within
the browser.