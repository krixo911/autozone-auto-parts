# Project Report — AutoZone Auto Parts & Accessories

**Task ID:** WD-EC-006  
**Student Code:** DAS-EC-006  
**Domain:** E-Commerce Auto Parts  
**Technology:** HTML5, CSS3, JavaScript

## 1. Objective
The objective of this project is to develop a responsive frontend e-commerce website concept for automotive parts and accessories. The website helps visitors browse parts by category, search and filter products, check sample vehicle compatibility, save favourites, manage a shopping cart and complete a simulated checkout.

## 2. Technologies Used
- **HTML5:** Semantic page structure, navigation, product sections and forms.
- **CSS3:** Responsive layouts, grid/flexbox, typography, hover states, mobile navigation and visual styling.
- **JavaScript (ES6):** Product data, search/filter/sort, cart, wishlist, vehicle fitment, demo authentication and simulated order handling.
- **localStorage:** Persists cart, wishlist, demo user and order history in the browser. No database is required.

## 3. Main Features
1. Home page with hero banner, category cards and promotional section.
2. Product listing with search, category, brand, vehicle and price/rating sorting filters.
3. Product detail modal with description, rating, price and sample compatible vehicles.
4. Shopping cart with quantity controls, remove action, subtotal, shipping and total calculation.
5. Checkout with shipping details and simulated COD, UPI or card payment selection.
6. Demo login/register, order history and saved vehicle display.
7. Wishlist, responsive mobile navigation and contact form feedback.

## 4. Learning Outcomes
This project provided practical experience in structuring a multi-section website, applying responsive CSS, rendering data-driven product cards, handling browser events, validating forms and storing frontend state with localStorage. It also demonstrated how an e-commerce user journey connects product discovery, cart management and checkout.

## 5. Challenges and Solutions
- **Dynamic product display:** Used a JavaScript array of product objects and generated product cards from the data.
- **Keeping cart totals accurate:** Recalculated totals whenever a product quantity changes or an item is removed.
- **Remembering user selections:** Used localStorage for cart, wishlist, user and order data.
- **Responsive design:** Added media queries for tablet and mobile layouts and a collapsible navigation menu.
- **Payment without a backend:** Implemented a clearly labelled simulation and avoided collecting or processing real payment information.

## 6. Conclusion
AutoZone demonstrates the core flow of a frontend automotive e-commerce website using only HTML, CSS and JavaScript. It is a working educational prototype; product data, fitment, authentication, orders and payments are simulated and would require backend services and verified supplier data for a production store.

**Task reference:** https://www.freeinternships.in/blog/
