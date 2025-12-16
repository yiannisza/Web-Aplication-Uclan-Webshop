# Student Shop Web Application

## Module: Web Technologies  
University of Central Lancashire
##Name: Yiannos Zachariades
##G-number: 21305657

---

## Project Overview
This project is a client-side web application built using HTML, CSS, and JavaScript.  
It represents a simple “Student Shop” where users can browse products, view item details, and manage a shopping cart.

All functionality is handled within the browser using JavaScript, sessionStorage, and localStorage. 

---

## Pages Included

### 1. Home Page (Index.html)
- Displays a welcome message introducing the Students’ Union.
- Includes an  MP4 video.
- Includes an iframe video.
- Provides navigation links Home,Product, Cart

---

### 2. Products Page (Product.html)
- Displays a list of all available products using JavaScript.
- Products are generated dynamically from a supplied product array.
- Each product shows an image, name, price, colour, and stock status.
- Users can:
  - View all products.
  - Filter products to show only items that are in stock.
  - Click on a product to view more details.
  - Add products directly to the cart.

---

### 3. Item Page (item.html)
- Displays detailed about the product
- Product data is passed from the Products page using sessionStorage.
- Shows:
  - Product image
  - Name
  - Colour
  - Price
  - Stock status
  - Product description
- Users can add the selected product to the shopping cart.
- This page is not accessible from the main navigation and is reached only by selecting a product.

---

### 4. Cart Page (cart.html)
- Displays all items currently added to the shopping cart.
- Cart data is stored and retrieved using localStorage.
- Shows:
  - Product image
  - Name and colour
  - Price
  - Quantity
- Users can remove items from the cart.
- Displays totalprice  of the cart value.
- Includes a discount code feature:
  - Code `SAVE20` applies a 20% discount to the cart total.

---

## Design and Styling
- A consistent colour palette is used across all pages.
- Colours are applied to navigation, headings, buttons, and stock indicators.
- Out-of-stock products are visually highlighted using colour changes.
- CSS animations are used to improve visual presentation.
- Layout is responsive for smaller screen sizes using media queries.

---

## JavaScript Features Implemented
- Dynamic product rendering using DOM manipulation.
- Stock-based filtering of products.
- Session-based storage of selected products.
- Shopping cart using localStorage.
- Cart item quantity management.
- Discount code validation and application.

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
