# GoSave Frontend

A modern React application for the GoSave platform - offering exclusive deals and partner management.

## 🚀 Features

- **User Registration & Authentication** with email verification
- **Admin Dashboard** with analytics and user management
- **Partner Portal** with application system and deal management
- **Deal Browsing** with filtering and search capabilities
- **Responsive Design** with Tailwind CSS

## 🛠 Tech Stack

- **React 19** with Vite build system
- **Tailwind CSS** for styling
- **Supabase** for authentication and database
- **React Router** for navigation
- **Lucide React** for icons

## 📦 Installation

```bash
npm install
npm run dev
```

## 🌐 Environment Variables

Copy `.env.example` to `.env` and configure:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_API_URL=https://your-backend-api.vercel.app/api
```

## 🚀 Deployment

This project is optimized for Vercel deployment:

1. Push to GitHub
2. Import project in Vercel
3. Set environment variables
4. Deploy!

## 📱 Pages

- **Home** - Landing page with features
- **Login/Register** - Authentication system
- **Dashboard** - User dashboard with profile management
- **Deals** - Browse and redeem exclusive deals
- **Partners** - Partner registration and management
- **Admin** - Administrative panel for user/partner management

## 🔒 Security Features

- Email verification system
- Protected routes
- Role-based access control
- Secure API communication

## 🎯 Backend API

This frontend connects to the GoSave backend API for:

- User authentication
- Deal management
- Partner operations
- Admin functions

Backend repository: [GoSave-Backend](https://github.com/ibn-e-Muhammad/Gosave2)
