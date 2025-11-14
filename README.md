# 🎓 EduLinkAI - Modern AI-Powered Networking Platform

**A stunning, deployment-ready platform connecting students and alumni through AI-powered matching, real-time messaging, and professional mentorship.**

[![Next.js](https://img.shields.io/badge/Next.js-16.0-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-5.0-2D3748?style=for-the-badge&logo=prisma)](https://www.prisma.io/)

## ✨ **Modern UI Transformation**

EduLinkAI features a **revolutionary modern design** with:
- 🎨 **Glass Morphism** - Advanced backdrop blur and transparency effects
- 🌈 **Gradient System** - Sophisticated color gradients and animations
- ⚡ **Advanced Animations** - Smooth micro-interactions and transitions
- 📱 **Mobile-First** - Responsive design optimized for all devices
- 🎯 **Professional Grade** - Enterprise-quality visual design

## 🚀 **Deployment Ready**

This is a **production-ready application** with:
- ✅ Complete feature implementation
- ✅ Modern, attractive UI/UX
- ✅ Performance optimizations
- ✅ Security configurations
- ✅ Comprehensive documentation

## ✨ Features

### 🔐 Authentication & User Management
- **Role-based authentication** (Student, Alumni, Admin)
- **OAuth integration** with Google
- **Profile verification** system for alumni
- **Secure session management**

### 🤖 AI-Powered Matching
- **Smart mentor-student matching** based on skills, interests, and career goals
- **Match scoring algorithm** with detailed explanations
- **Personalized recommendations** using AI insights
- **Skills and interests alignment**

### 👥 Mentorship System
- **Structured mentorship programs**
- **Session scheduling and management**
- **Progress tracking and feedback**
- **Rating and review system**

### 💼 Job Referral Network
- **Alumni job posting system**
- **Student referral requests**
- **Application tracking**
- **Success rate analytics**

### 🏆 Gamification & Engagement
- **Points and leveling system**
- **Achievement badges**
- **Leaderboards**
- **Weekly challenges**
- **Impact tracking**

### 📊 Role-Based Dashboards
- **Student Dashboard**: Mentor suggestions, upcoming sessions, referral tracker
- **Alumni Dashboard**: Active mentorships, referral management, impact metrics
- **Admin Dashboard**: User verification, platform analytics, system management

## 🛠️ Tech Stack

### Frontend
- **Next.js 16** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Shadcn/UI** - Modern component library
- **Lucide React** - Beautiful icons

### Backend & Database
- **Prisma** - Type-safe database ORM
- **PostgreSQL** - Relational database
- **NextAuth.js** - Authentication solution
- **Socket.io** - Real-time communication (planned)

### Additional Tools
- **Recharts** - Data visualization (planned)
- **Class Variance Authority** - Component styling
- **Clsx & Tailwind Merge** - Conditional styling

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- PostgreSQL database
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/guruprasadreddyk/EduLinkAI
   cd edulinkai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp env.example .env
   ```
   
   Update `.env` with your configuration:
   ```env
   DATABASE_URL="postgresql://username:password@localhost:5432/edulinkai"
   NEXTAUTH_SECRET="your-secret-key"
   NEXTAUTH_URL="http://localhost:3000"
   GOOGLE_CLIENT_ID="your-google-client-id"
   GOOGLE_CLIENT_SECRET="your-google-client-secret"
   ```

4. **Set up the database**
   ```bash
   npx prisma generate
   npx prisma db push
   npx prisma db seed # (optional - if seed file exists)
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router pages
│   ├── (auth)/            # Authentication pages
│   ├── student/           # Student-specific pages
│   ├── alumni/            # Alumni-specific pages
│   ├── admin/             # Admin-specific pages
│   └── page.tsx           # Landing page
├── components/            # Reusable components
│   ├── ui/               # Shadcn/UI components
│   ├── layout/           # Layout components
│   ├── auth/             # Authentication components
│   ├── dashboard/        # Dashboard components
│   ├── mentorship/       # Mentorship components
│   ├── chat/             # Chat components
│   ├── referrals/        # Referral components
│   ├── gamification/     # Gamification components
│   └── analytics/        # Analytics components
├── lib/                   # Utility libraries
│   ├── auth/             # Authentication config
│   ├── db/               # Database connection
│   ├── ai/               # AI matching logic
│   └── utils.ts          # General utilities
├── types/                # TypeScript type definitions
├── hooks/                # Custom React hooks
└── utils/                # Additional utilities
```

## 🎯 Key Pages & Features

### Landing Page (`/`)
- Hero section with platform overview
- Feature highlights
- User testimonials
- Call-to-action for registration

### Authentication (`/auth/`)
- **Login** (`/auth/login`) - User authentication
- **Signup** (`/auth/signup`) - Role-based registration
- **Forgot Password** (`/auth/forgot-password`) - Password recovery

### Student Portal (`/student/`)
- **Dashboard** (`/student/dashboard`) - Overview, mentor suggestions, sessions
- **Find Mentors** (`/student/mentors`) - AI-powered mentor discovery
- **Leaderboard** (`/student/leaderboard`) - Gamification and achievements
- **Chat** (`/student/chat`) - Real-time messaging
- **Referrals** (`/student/referrals`) - Job opportunity tracking

### Alumni Portal (`/alumni/`)
- **Dashboard** (`/alumni/dashboard`) - Impact metrics, active mentorships
- **Manage Referrals** (`/alumni/referrals/manage`) - Job posting and request management
- **Chat** (`/alumni/chat`) - Communication with mentees

### Admin Portal (`/admin/`)
- **Dashboard** (`/admin/dashboard`) - Platform analytics
- **User Verification** (`/admin/verify`) - Alumni verification queue
- **Analytics** (`/admin/analytics`) - Detailed platform insights

## 🔧 Development

### Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint
npm run type-check   # Run TypeScript checks
```

### Database Management

```bash
npx prisma studio    # Open Prisma Studio
npx prisma generate  # Generate Prisma client
npx prisma db push   # Push schema changes
npx prisma migrate   # Create and run migrations
```

## 🎨 UI Components

The platform uses a comprehensive set of reusable components:

- **Layout**: Navbar, Footer, Sidebar
- **Forms**: Input, Label, Button, Select, Textarea
- **Display**: Card, Badge, Avatar, Toast
- **Navigation**: Tabs, Dropdown, Dialog
- **Data**: Table, Charts, Progress bars

## 🔒 Security Features

- **JWT-based authentication**
- **Role-based access control**
- **Input validation and sanitization**
- **CSRF protection**
- **Secure password handling**
- **Alumni verification system**

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Configure environment variables
4. Deploy automatically

### Manual Deployment
```bash
npm run build
npm run start
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Shadcn/UI** for the beautiful component library
- **Lucide** for the comprehensive icon set
- **Prisma** for the excellent database toolkit
- **Next.js** team for the amazing framework

## 📞 Support

For support, email support@edulinkai.com or join our community Discord.

---

**Built with ❤️ for the education community**
