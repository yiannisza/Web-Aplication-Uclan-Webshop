# Student Shop Web Application

## Module: Web Technologies  
University of Central Lancashire
Name: Yiannos Zachariades
G-number: 21305657

---

## Project Overview
This web application is created by using html,css,javascript.
User can browse on the website and add products items to their card.



---

## Pages Included

### 1. Home Page (Index.html)
- It has a welcome page and gives a introduction 
- It Contains an mp4 video.
- It Contains an iframe video.
- Contains navigation links to Home,Product, Cart

---

### 2. Products Page (Product.html)
- Using JavaScript, it shows the complete list of all the products that are available.
- Products are dynamically created from a given product array
- Each product displays an image, name, price, colour, and stock.
- Users can:
  - See all products.
  - Filter products only those that are available.
  - Click on a product to read more.
  - Add products to cart.

---

### 3. Item Page (item.html)
- Displays discription of product
- Product data is transfer from the Products page using sessionStorage.
- It contains the array of image,colour,price,stock,description
- Product can be added to cart
- The Item page cannot be visited from the main navigation and can only be visit by clicking on a product.

---

### 4. Cart Page (cart.html)
- Products are displayed in the cart
- Cart data is stored by using localStorage.
- Users can remove product from the cart.
-  It updates the totalprice of the cart value.
- It has a coupon feature where the user can add the code 'SAVE20' to apply a 20% discount

---

## Design and Styling
- Same colour palette has been the same throughout the different pages.
- Colours have been used for the to navigation, headings, buttons, and stock indicators.
- The products that are out of stock have been view in red and the stock has been view in green
- The design/layout adjust to different scren sizes by using media queries

---

## JavaScript Features Implemented
- Product display dynamically.
- Products are filtered based on the stock.
- Selected products uses SessionsStorage.
- Cart page uses localStorage.
- Cart total updates dynamically
- Coupon feature

---

## Validation
- HTML and CSS code has been validated using the W3C Validator.
- No critical validation errors were found.
---

## Limitations
- GitHub has not been explored and adopted, only used for the Readme file

---
