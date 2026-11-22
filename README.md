# 🍽️ Tasty Kitchens – Food Ordering Application

A responsive food ordering web application built using React. Users can explore restaurants, browse menus, sort restaurants by ratings, add food items to their cart, manage quantities and view their order total.

**Developed and customized by Abinayateja**

## 🚀 Live Demo

[Visit Tasty Kitchens](https://abinayateja.github.io/TASTY-KITCHENS/)

## 📸 Application Screenshots

### 1. Home Page
Explore promotional offers and popular restaurants.

![Home Page](./screenshots/homepage.png)

### 2. Restaurant Listing
Browse restaurants with cuisine information, ratings and pagination.

![Restaurant Listing](./screenshots/restaurant-listing.png)

### 3. Restaurant Sorting
Sort restaurants by lowest or highest rating.

![Sorting Options](./screenshots/sorting-options.png)

### 4. Shopping Cart
Manage food quantities, remove items and view the order total.

![Shopping Cart](./screenshots/shopping-cart.png)

## ✨ Key Features

- User authentication using API integration.
- JWT-based authentication and protected routes.
- Restaurant listing with dynamic API data.
- Promotional offers displayed in a carousel.
- Restaurant sorting by ratings.
- Pagination for restaurant listings.
- Restaurant and food menu browsing.
- Add food items to the shopping cart.
- Increase and decrease item quantities.
- Remove items from the cart.
- Automatic order total calculation.
- Persistent cart data using LocalStorage.
- Responsive user interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| React.js | Frontend development |
| JavaScript (ES6+) | Application logic |
| HTML5 | Structure |
| CSS3 | Styling and responsiveness |
| React Router DOM | Client-side routing |
| React Context API | Shared cart state |
| REST APIs | Restaurant and authentication data |
| Fetch API | HTTP requests |
| LocalStorage | Cart persistence |
| js-cookie | JWT cookie management |
| Material UI | UI components and pagination |
| React Slick | Promotional carousel |
| React Icons | Icons |

## 🏗️ Application Architecture

- **Login:** Handles user authentication and JWT token storage.
- **Protected Routes:** Restricts access to authenticated users.
- **Home:** Displays promotional offers and restaurant listings.
- **Restaurant Details:** Displays restaurant menu information.
- **Cart:** Manages selected food items and order totals.
- **Context API:** Shares cart information across components.

## ⚙️ Installation and Setup

Clone the repository:

```bash
git clone https://github.com/Abinayateja/TASTY-KITCHENS.git
```

Navigate to the project:

```bash
cd TASTY-KITCHENS
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

Open:

```text
http://localhost:3000
```

Build for production:

```bash
npm run build
```

## 🔌 API Integration

The application integrates with external CCBP APIs for authentication, promotional offers, restaurant listings and related restaurant data.

The authentication flow uses a JWT token stored in a browser cookie.

**Note:** The application depends on the availability of the external API service.

## 👨‍💻 Author

**Abinayateja**

- GitHub: [@Abinayateja](https://github.com/Abinayateja)
- Portfolio: [My Portfolio](https://portfolio533.netlify.app/)

This repository documents my learning and customization of a React-based food ordering application. The external API service and original educational project requirements are acknowledged.

---

⭐ If you find this project interesting, feel free to explore the repository.
