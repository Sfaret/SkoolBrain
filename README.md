# Duolingo Clone

This project is a clone of Duolingo, built using modern web technologies. It features a comprehensive set of functionalities including an admin dashboard, Stripe integration for premium features, and SSO authentication with Google.

## Features

- **Frontend**: Next.js, TypeScript, TailwindCSS, ShadCN UI
- **Backend**: Drizzle, Neon (PostgreSQL)
- **State Management**: Zustand
- **HTTP Requests**: Axios
- **Admin Dashboard**: `react-admin`
- **Payments**: Stripe integration
- **Authentication**: Google SSO

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/RikhiSingh/Duolingo-Clone.git
   cd Duolingo-Clone
   
2. **Install Dependencies**
   ```bash
   npm install
   
3. **Set up environment variables** <br/>
   Create a .env file in the root directory and add the necessary environment variables.
   *Namely*
   ```bash
   1. NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY 
   2. CLERK_SECRET_KEY 
   3. DATABASE_URL
   4. STRIPE_API_KEY
   5. NEXT_PUBLIC_APP_URL
   6. STRIPE_WEBHOOK_SECRET

4. **Run the development server**
   ```bash
   npm run dev

5. **Access the Application** <br />
   Open http://localhost:3000 in your browser.

## Usage
- Register or log in using Google SSO.
- Explore language courses and track your progress.
- Admins can manage content through the admin dashboard.
- Upgrade to premium for additional features using Stripe.
  
## Contributing <br />
Contributions are welcome! Please follow these steps: <br />

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your branch.
5. Open a pull request.

<br />
This Markdown file provides a clear and styled README for your project. Feel free to further customize it as needed!
