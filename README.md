# Student Shop Web Application

## Module: Web Technologies  
University of Central Lancashire
Name: Yiannos Zachariades
G-number: 21305657

---

## Project Overview
This project is a client-side web application built using HTML, CSS, and JavaScript.  
It represents a simple “Student Shop” where users can browse products, view item details, and manage a shopping cart.

All functionality is handled within the browser using JavaScript, sessionStorage, and localStorage. 

---

## Pages Included

### 1. Home Page (Index.html)
- It features a greeting rext that shows an intoduction of the Student Union 
- Contains an  MP4 video.
- Contains an iframe video.
- Contains navigation links Home,Product, Cart

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
- Shows:
  - image
  - Name
  - Colour
  - Price
  - Stock
  - description
- Product can add to cart
- The page is cannot be accessed from the main navigation and can only be reach by clicking a product.

---

### 4. Cart Page (cart.html)
- It displays the products that have been added to the shopping cart.
- Cart data is stored and retrieved using localStorage.
- Users can remove product from the cart.
- Displays totalprice  of the cart value.
- It has a coupon feature:
  - Code `SAVE20` applies a 20% discount to the cart total.

---

## Design and Styling
- The same colour palette has been maintained throughout the different pages.
- Colours have been used for the to navigation, headings, buttons, and stock indicators.
- The products that are out of stock have been view in red and the stock has been view in green
- The design/layout adjust to different scren sizes by using media queries

---

## JavaScript Features Implemented
- Product display dynamically.
- Products are filtered based on the stock.
- Selected products uses SessionsStorage.
- Shopping-cart uses localStorage.
- Managing the quantity of the cart itmes.
- Discount code usage.

---

## Validation
- HTML and CSS code has been checked using the W3C Validator.
- No critical validation errors were found.
---

## Unresolved Issues / Limitations
- No checkout or payment functionality is implemented (not required).
- Coupon codes are hardcoded and limited to one example (`SAVE20`).
- Accessibility features such as ARIA labels could be improved further.
- GitHub has not been explored and adopted, only used for the Readme file

---
