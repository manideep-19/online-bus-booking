# 🚌 Modern Bus Booking Web Application

A modern, responsive, and scalable bus booking platform built using **React**, **TypeScript**, **Tailwind CSS**, and **Vite**. 
It integrates user interface animations, routing, state management, and real-time features to deliver a seamless experience for bus seat reservations.

## 🚀 Features

- Search and book bus tickets
- View available buses by date and destination
- Seat selection interface
- Realtime database support (via [Supabase](https://supabase.io/))
- Animations with Framer Motion
- Modular and reusable UI components
- Environment-based configuration

## 🛠️ Tech Stack

- **React 18**
- **TypeScript**
- **Tailwind CSS**
- **Vite**
- **Supabase** (for authentication and backend)
- **Zustand** (state management)
- **Framer Motion** (animations)
- **React Router DOM** (routing)

## 📦 Project Structure

```
bus/
├── index.html              # Main entry HTML
├── src/                    # React app source files
│   ├── components/         # UI Components
│   ├── pages/              # App pages like Booking, Home, etc.
│   ├── hooks/              # Custom hooks
│   └── lib/                # API & utilities
├── public/                 # Static assets
├── tailwind.config.js      # Tailwind configuration
├── tsconfig.json           # TypeScript configuration
├── vite.config.ts          # Vite bundler config
└── .env                    # Environment variables
```

## ⚙️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/manideep-19/online-bus-booking.git
   cd bus
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Add environment variables**
   - Create a `.env` file and add your Supabase project details.

4. **Run development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 📄 License

This project is licensed under the **MIT License**.
