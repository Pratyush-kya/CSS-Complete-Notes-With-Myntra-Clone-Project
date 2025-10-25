# CSS-Complete-Notes-With-Myntra-Clone-Project

Myntra Clone
This repository contains a fully responsive Myntra homepage clone crafted using pure HTML and CSS. All components including the header, navigation bar, banner, category section, and footer accurately reflect Myntra’s user interface and aesthetic.

Features
Responsive navigation bar

Integrated search bar and action buttons (Profile, Wishlist, Bag)

Promotional banner and dynamic category listing

Structured footer with navigation and informational links

Clean and mobile-friendly layout​

Project Structure
text
/
|-- index.html           # Main HTML file
|-- myntra.css           # Main CSS file for all styling
|-- /images              # Project images (logo, banner, sale items, etc.)
Key CSS Highlights
The styling utilizes resets, modern layouts, and easy-to-read class names. Some main features:

Global reset (* { margin: 0; padding: 0; box-sizing: border-box; })

Custom font for enhanced UI appearance

Flexbox for header/navigation and layout containers

Style for hover effects on navigation items

Utility for responsive design with media queries

BEM-like class naming for maintainability​

Example CSS:

css
* {
    margin: 0;
    padding: 0;
    font-family: Assistant,-apple-system,BlinkMacSystemFont,Sego UI,Roboto,Helvertica,Arial,sans-serif;
    box-sizing: border-box;
}
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #fff;
    border-bottom: 1px solid #b6b1b1;
}
.nav_bar a:hover {
    border-bottom: 4px solid #ff3f6c;
}
How to Use
Clone/download this repository.

Place your images in the images folder.

Open index.html in any browser to view the project.

Credits & Learning Outcomes
Practiced modern front-end development skills using HTML5 and CSS3.

Implemented responsive design, Flexbox, and class-based styling for UI components.​

The structure and appearance closely match Myntra's real homepage for practical UI experience.

