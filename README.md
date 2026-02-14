

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
=======


# Paradise Nursery Shopping Application

Paradise Nursery Shopping Application is a dynamic e-commerce web application built using React and Redux. The application allows users to browse a collection of houseplants, view plant details, add plants to a shopping cart, and manage cart items with real-time updates.

## Project Overview

This project simulates an online plant shop where users can:

* Browse houseplants grouped into different categories
* View plant thumbnails, names, descriptions, and prices
* Add plants to a shopping cart
* Increase or decrease item quantities
* Remove items from the cart
* View dynamically updated total cost

The goal of this project was to implement a user-friendly shopping experience using modern front-end development practices.

## Technologies Used

* React.js
* Redux Toolkit
* React Router
* CSS
* JavaScript (ES6)

## Features

### Landing Page

* Displays the company name “Paradise Nursery”
* Attractive background image
* “Get Started” button to navigate to product listing page

### Product Listing Page

* Plants grouped into at least three categories
* Each category includes multiple unique plants
* Each plant displays:

  * Thumbnail image
  * Name
  * Price
* “Add to Cart” button:

  * Adds product to cart
  * Disables after adding
  * Updates cart icon count dynamically
* Navigation bar with:

  * Home
  * Plants
  * Cart

### Shopping Cart Page

* Displays all selected plants
* Shows:

  * Thumbnail
  * Name
  * Unit price
  * Quantity controls
  * Total cost per item
* Increase and decrease quantity buttons
* Delete item button
* Total cart amount calculation
* Checkout button (Coming Soon)
* Continue Shopping button

## Folder Structure (Example)

```
src/
│
├── components/
│   ├── AboutUs.jsx
│   ├── ProductList.jsx
│   ├── CartItem.jsx
│
├── redux/
│   ├── CartSlice.jsx
│
├── App.jsx
├── App.css
```

## How to Run the Project

1. Clone the repository
2. Navigate to the project folder
3. Install dependencies

```
npm install
```

4. Start the development server

```
npm start
```

The application will run on:

```
http://localhost:3000
```

## Future Enhancements

* User authentication
* Payment gateway integration
* Backend database integration
* Order history feature

