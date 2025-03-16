# Basic version

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).


---
# E-commerce Demo with Next.js

This project is a demonstration of my e-commerce website built with Next.js with a heavy focus on the UI end using KendoReact, a react library. It showcases my skills as a Full Stack web developer with a specialization in Front-End development.

## Project Goals

* To create a portfolio piece that demonstrates proficiency in building modern web applications with Next.js.
* To showcase the implementation of key e-commerce functionalities.
* To prioritize accessibility and user experience.
* To create a foundation for building e-commerce sites with options for different languages

## Features

* **Product Catalog:**
    * Browse a selection of mock products.
    * Product details pages.
* **Shopping Cart:**
    * Add items to the cart.
    * View and manage cart contents.
* **Checkout Flow:**
    * Simulated checkout process using Stripe's test mode.
    * Order confirmation (mock).
* **Data Management (Optional):**
    * Integration with Sanity (or similar) to demonstrate dynamic content management (see "Branches" below).
* **Accessibility Focus:**
    * Built with accessibility best practices in mind.

## Technologies

* Next.js
* React
* Stripe (test mode)
* Sanity (optional, for content management)
* (Add any other libraries or frameworks you use)

## Branches

* `main`: This branch contains the core Next.js project setup.
* `local-data`: This branch features the e-commerce demo using local mock data (e.g., JSON files). This version is easy to run without any external dependencies.
* `sanity-integration`: (Optional) This branch demonstrates integration with Sanity for content management. See setup instructions below.

## Getting Started

### Local Data Version

1.  Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2.  Navigate to the project directory:

    ```bash
    cd <project-directory>
    ```

3.  Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

4.  Run the development server:

    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```

5.  Open [http://localhost:3000](http://localhost:3000) in your browser to view the demo.

### Sanity Integration (Optional)

1.  Follow the steps above to clone and navigate to the project.
2.  Checkout the `sanity-integration` branch:

    ```bash
    git checkout sanity-integration
    ```

3.  **Set up Sanity:**
    * Create a Sanity account and project.
    * Define the product schema (see `sanity.io` for documentation).
    * Populate your Sanity dataset with data.
4.  **Configure environment variables:**
    * Create a `.env.local` file in the project root.
    * Add your Sanity project ID, dataset, and API token:

        ```
        NEXT_PUBLIC_SANITY_PROJECT_ID=your-project-id
        NEXT_PUBLIC_SANITY_DATASET=your-dataset
        NEXT_PUBLIC_SANITY_API_VERSION=your-api-version
        NEXT_PUBLIC_SANITY_TOKEN=your-token (if needed)
        ```

5.  Install dependencies and run the development server as described above.

## Important Notes

* This project uses Stripe in test mode. No real transactions are processed.
* The `local-data` branch provides a simplified setup for quick viewing.
* The `sanity-integration` branch showcases the use of a headless CMS for content management.

## Demo

A video demonstration of this project is available here: \[Link to your video demo]

## Author

\[Alverto Ortega-Garcia]

## Contact

\[Your preferred contact method, e.g., email, LinkedIn]

## License

\[Choose a license, e.g., MIT License]

---
