# EventsApp - Your Event Management Platform

## Overview

EventsApp is a events platform designed to host, connect, and celebrate events of all types. Whether you're organizing a small meetup or interesting events, EventsApp provides all the tools you need to create an unforgettable experience. Users can create their own accounts, manage their events, and join others' events based on categories.

## Features

- **User Registration & Authentication**: Secure login and registration using Clerk.
- **Event Creation & Management**: Users can create, edit, and manage their own events.
- **Event Categories**: Events are organized into categories for easy browsing.
- **Free & Paid Events**: Some events are free, while others require payment via Stripe.
- **Photo Uploads**: Users can upload photos for their events using UploadThings.
- **Search Functionality**: Search for events by name or category.
- **Profile Management**: Users can change their passwords and manage their profiles after logging in with Clerk.

## LIVE WATCH -> https://events-app-drab.vercel.app/



## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/eljanrustamov/events-app_54856.git
   cd events-app_54856

   ```

2. Install dependencies:

```bash

npm install
```

3. Set up environment variables:

Create a .env.local file in the root directory and add the following:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

MONGODB_URI=your_mongodb_connection_string

WEBHOOK_SECRET=your_webhook_secret

UPLOADTHING_SECRET=your_uploadthing_secret
UPLOADTHING_APP_ID=your_uploadthing_app_id

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret

NEXT_PUBLIC_SERVER_URL=http://localhost:3000/





4. Start the development server:

npm run dev
