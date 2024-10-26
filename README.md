This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

This project is a Next.js application with Tailwind CSS and DaisyUI for styling. It includes a structured set of components, layouts, and pages to demonstrate routing, component reuse, and data fetching.

- Home Page (app/page.tsx): The main entry point of the app, displaying a "Hello World" message, a link to the Users page, and a ProductCard component with an "Add to Cart" button.

- Users Page (app/users/page.tsx): Fetches and displays a list of users from an external API in a table format. The table includes columns for user names and email addresses.

- New User Page (app/users/new/page.tsx): A placeholder page for new users, displaying the text "UserPage." This demonstrates how to set up nested routes in Next.js.

- Root Layout (app/layout.tsx):

* This file defines the root layout for the entire application. It imports and applies global styles from globals.css and includes two custom fonts (GeistSans and GeistMono) with variable weights.
* It sets the <html> tag to lang="en" and applies the data-theme="winter" attribute for DaisyUI themes. The body tag includes classes for font variables and the antialiased text rendering for smoother font display.

- Components:

* AddToCart.tsx: A client-side button labeled "Add to Cart" that logs a message when clicked.
* ProductCard.tsx: A placeholder component for product information that contains the AddToCart button.

Global Styles (globals.css): Configures Tailwind CSS, sets up light and dark mode variables, and applies basic styling for the application.
