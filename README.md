This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

# Candle E-Commerce Website (Advanced Version - Sanity Integration)

## Overview

This is the advanced version of the candle eCommerce website, which extends the basic version by integrating **Sanity.io** for content management and **AI-powered features** to enhance user experience.

---

## Additional Features in This Branch

- **Sanity.io CMS** for dynamic product and content management
- **AI-powered scent quiz** for personalized candle recommendations
- **AI-enhanced candle customization** allowing users to create unique candle blends
- **AR Candle Preview** for an interactive shopping experience
- **Advanced filtering and search functionality** powered by Sanity queries
- **Enhanced state management** with Zustand or Redux

---

## Installation & Setup

1. Clone the repository and switch to this branch:
   ```bash
   git clone -b sanity-integration https://github.com/your-username/candle-ecommerce.git
   cd candle-ecommerce
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up Sanity CMS:
   ```bash
   cd sanity
   sanity init
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Requirements

- A Stripe account (sign up at https://stripe.com).
- API keys from your Stripe account for testing or live payments.

## Setup

1. Create a Stripe account and obtain your API keys (Test or Live).
2. Set the following environment variables:
   - `STRIPE_SECRET_KEY`: Your secret key.
   - `STRIPE_PUBLIC_KEY`: Your public key.
3. Follow the steps in `config/stripe.js` to integrate your keys.

Test payments can be processed using the provided test keys from Stripe.

---

## Contribution

Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests.

---

## License

This project is open-source and available under the MIT License.

