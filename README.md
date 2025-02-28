# ReelSphere

**Objective of ReelSphere:**  
ReelSphere is a dynamic short-video sharing platform designed to empower creators with seamless video editing, AI-driven recommendations, and interactive engagement features. It aims to foster a vibrant community where users can create, explore, and share trending content while ensuring a smooth, high-quality viewing experience across devices. 🚀🎥
## Features

- 🔐 User Authentication (NextAuth.js)
- 📹 Video Upload and Management (ImageKit)
  
- 🎨 Modern UI with Tailwind CSS and DaisyUI
- 📱 Fully Responsive Design
- 🔒 Secure API Routes
  
- 🗄️ MongoDB Database Integration

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS, DaisyUI
- **Authentication**: NextAuth.js, JWT
- **Database**: MongoDB with Mongoose
- **File Storage**: ImageKit
- **Payment**: Razorpay
- **Email**: Nodemailer
- **Form Handling**: React Hook Form

## Prerequisites

- Node.js (Latest LTS version)
- MongoDB Database
- ImageKit Account
- Razorpay Account
- SMTP Server (for email notifications)

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd imagekit-video-main
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Fill in the required environment variables

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Environment Variables

Create a `.env` file with the following variables:

```env
# Database
MONGODB_URI=

# Authentication
NEXTAUTH_SECRET=
NEXTAUTH_URL=

# ImageKit
IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=


```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build production application
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run seed` - Seed the database
- 

## Project Structure

```
├── app/                  # Next.js app directory
│   ├── api/             # API routes
│   ├── components/      # Reusable components
│   ├── login/          # Login page
│   ├── register/       # Registration page
│   └── upload/         # Video upload page
├── lib/                # Utility functions
├── models/             # MongoDB models
├── public/            # Static assets
└── types.d.ts         # TypeScript declarations
```

