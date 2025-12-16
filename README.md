# Student Shop Web Application

## Module: Web Technologies  
University of Central Lancashire

---

## Project Overview
This project is a client-side web application built using HTML, CSS, and JavaScript.  
It represents a simple “Student Shop” where users can browse products, view item details, and manage a shopping cart.

All functionality is handled within the browser using JavaScript, sessionStorage, and localStorage. No server-side code is used.

---

## Pages Included

### 1. Home Page (Index.html)
- Displays a welcome message introducing the Students’ Union.
- Includes an embedded MP4 video.
- Includes an embedded Vimeo video using an iframe.
- Provides navigation links to Products and Cart pages.

---

### 2. Products Page (Product.html)
- Displays a list of all available products using JavaScript.
- Products are generated dynamically from a supplied product array.
- Each product shows an image, name, price, colour, and stock status.
- Users can:
  - View all products.
  - Filter products to show only items that are in stock.
  - Click on a product to view further details.
  - Add products directly to the cart.

---

### 3. Item Page (item.html)
- Displays detailed information about a single selected product.
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
- Displays a running total of the cart value.
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
- Persistent shopping cart using localStorage.
- Cart item quantity management.
- Discount code validation and application.
- Real-time cart total calculation.

---

## Validation
- HTML and CSS code has been checked using the W3C Validator.
- No critical validation errors were found.
- Minor warnings (if any) do not affect functionality.

---

## Unresolved Issues / Limitations
- No checkout or payment functionality is implemented (not required).
- Coupon codes are hardcoded and limited to one example (`SAVE20`).
- Accessibility features such as ARIA labels could be improved further.

---

## Conclusion
This project meets all required “should” criteria and implements several “could” features.  
It demonstrates the use of JavaScript for dynamic content, storage APIs for state management, and structured HTML/CSS for layout and styling.
