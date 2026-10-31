## OsloMet Study Program Page – Responsive & Accessible Website

A responsive, multi-page website that recreates OsloMet's study program page for Bachelor i matematisk modellering og datavitenskap (Mathematical Modelling and Data Science). Built from scratch with plain HTML, CSS and JavaScript as a group project at OsloMet, with a focus on universal design, responsive layout and collaboration with Git/GitHub.

Live site: marren5.github.io/my-webpage

## Features
Four pages: program page, accessibility report, Git/GitHub reflection and an activity page, all with shared navigation, header and footer
Responsive layout built with Flexbox: a 60/40 content split on desktop that stacks into one column on mobile
Media queries for small screens (≤ 768px) and large screens (≥ 1440px), adjusting text size, padding, tables and navigation
Expandable info boxes (admission requirements, how to apply, teaching, costs, exchange, further studies) toggled with vanilla JavaScript
Course structure tables for the whole program and each of the three specializations, linking to every course on student.oslomet.no
Scrollable tables on small screens so wide content never breaks the layout
Hover effects and transitions on links, cards and buttons for clear visual feedback

## Universal design

Accessibility was a core requirement, not an afterthought:

Semantic HTML (header, nav, main, article, footer) for a logical structure that screen readers can follow
Logical heading hierarchy and descriptive link text, so users know where a link leads
Alt text on images
Readable typography with generous line spacing and visually distinct links
Tested with WAVE: screenshots of the results and our reflections are documented on the Accessibility page


## Run locally

No build tools or dependencies needed.

bash
git clone https://github.com/marren5/my-webpage.git
cd my-webpage

Then open index.html in your browser, or use an extension like Live Server in VS Code.


Some CSS techniques were adapted from W3Schools

## This is a student project made for learning purposes and is not affiliated with or endorsed by OsloMet.
