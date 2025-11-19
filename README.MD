Overview

This project is a simple, responsive e-commerce clothing website built using HTML, CSS, and JavaScript only.
It includes a city-selection entry screen, product listing, product details, and WhatsApp-based order placement.
No backend is required — everything runs on the client side.

Features
1. City Selection Entry Page

User must select a city before entering the store.

Available cities: Karachi, Lahore, Islamabad, Rawalpindi.

Selected city is stored using JavaScript for later use.

2. Product Listing

Contains 8 dummy clothing products (shirts, hoodies, trousers, etc.).

Each product displays:

Image

Name

Price (in PKR)

3. Product Detail View

Each product page/modal includes:

Product image

Product description

Available sizes

Price (PKR)

Place Order button

4. WhatsApp Order System

When the user clicks Place Order, the site opens WhatsApp with a pre-filled message containing:

The user's selected city

Product name

Product price

Example:

“Hello! I want to place an order from Karachi. Product: Blue Shirt — Price: PKR 2500.”

This is done using the standard WhatsApp API:
https://wa.me/<number>?text=<encoded_message>

5. Footer

The website includes a clean footer with:

Website logo

Contact email

Phone number

Social links

Copyright text

Technologies Used

HTML5

CSS3

Vanilla JavaScript

WhatsApp API (wa.me)

How to Run the Project

Download or clone the project folder.

Open index.html in any modern browser.

No installation or server setup needed.

Folder Structure
/project
│── index.html
│── styles.css
│── script.js
│── /assets
│     ├── product-images
│     └── logo.png

Customization Guide
Change Products

Edit the products array in script.js
→ Update name, description, image, and price.

Change WhatsApp Number

Update the phone number in the WhatsApp link generator inside script.js.

Change City List

Modify the entry page dropdown/buttons in index.html.

Update Footer

Replace contact details and icons in the footer section of the HTML.

License

This project is free to use, modify, and distribute.