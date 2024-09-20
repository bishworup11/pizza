# Pizza Hut Sylhet Co. React App

## Overview

This project is a simple React application showcasing a pizza menu for "Pizza Hut Sylhet Co." It provides an interactive user interface to display various pizzas, including their ingredients and prices, as well as an ordering feature based on operating hours. The app serves as a great introduction to React fundamentals, including component structure, props, and conditional rendering.

## Features

- Display a list of pizzas with their details (name, ingredients, price, and availability).
- Highlight sold-out pizzas.
- Show dynamic operating hours and a call-to-action button for ordering when the restaurant is open.

## Technologies Used

- React
- ReactDOM
- CSS for styling

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v14 or later)
- npm (comes with Node.js)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/pizza.git
   cd pizza-hut-sylhet
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Add Pizza Images:**
   - Make sure you have the images for the pizzas in a folder named `pizzas` within the `public` directory of your project. The images should be named according to the `photoName` properties in the `pizzaData` array (e.g., `focaccia.jpg`, `margherita.jpg`, etc.).

### Running the Application

To start the development server, run:

```bash
npm start
```

This will start the application on [http://localhost:3000](http://localhost:3000).

### Building for Production

To create an optimized build for production, run:

```bash
npm run build
```

This will generate a `build` directory containing the production build of your app.

## Usage

- Upon loading the app, you'll see a header with the restaurant name, a menu with various pizzas, and a footer indicating whether the restaurant is currently open or closed.
- When the restaurant is open, you can click the "Order Now" button to simulate placing an order.

## Future Improvements

- Add routing for individual pizza details.
- Implement a shopping cart feature for ordering multiple pizzas.
- Enhance styling with animations and transitions.
- Incorporate state management with Redux or Context API for better state handling.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

This project is part of "The Ultimate React Course 2024: React, Next.js, Redux & More" on Udemy. Special thanks to the course instructors for providing the foundational knowledge to build this application.