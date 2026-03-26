# AI-Powered Tourism Management Portal 🌍✈️

A comprehensive web application for managing travel bookings with AI-powered recommendations, safety checklists, and emergency location mapping.

## Features ✨

### 1. **Animated Landing Page**
- Beautiful gradient animations with floating travel icons
- Cartoon-style animations for enhanced user experience
- Login functionality with smooth transitions

### 2. **Signup & Authentication**
- Email signup with verification code
- Google OAuth integration
- Email verification flow (Demo code: `123456`)
- Animated onboarding experience

### 3. **Home Page**
- Realistic design with smooth animations
- AI-powered package recommendation button
- Global search functionality for tour packages
- Browse packages by destination, category, or keywords
- Responsive grid layout with hover effects

### 4. **AI Package Recommendation System**
- Interactive questionnaire to understand traveler preferences
- AI analyzes 5 key factors:
  - Travel experience type (Beach, Adventure, Cultural, etc.)
  - Climate preference
  - Trip duration
  - Budget range
  - Activity interests
- Personalized package recommendations based on answers
- Real-time analysis animation

### 5. **Package Details Page**
- Comprehensive package information
- Dynamic pricing calculator based on number of travelers
- Beautiful image galleries
- Highlights, inclusions, and sample itinerary
- Favorite and share functionality
- Real-time price calculation

### 6. **Payment Processing**
- Multiple payment methods:
  - **PhonePe** - Mobile payment
  - **Google Pay** - Digital wallet
  - **UPI** - Direct bank transfer with UPI ID input
  - **Cash on Arrival** - Pay later option
- Secure payment flow with animations
- Detailed price breakdown
- Trust badges and security indicators

### 7. **Payment Success Page**
- Confetti animation on successful payment
- Downloadable receipt (text format)
- Complete transaction details
- Next steps guide
- Navigation to dashboard or home

### 8. **Customer Dashboard**
Three main features:

#### a) **Traveler Safety Checklist**
- 10 essential pre-travel safety checks
- Critical vs. non-critical item indicators
- Progress tracking with visual indicators
- Deadline monitoring for time-sensitive items
- **AI Auto-Support**: If critical items are overdue, AI automatically triggers customer support notifications

#### b) **Emergency Location Map**
- Interactive map showing nearby emergency services:
  - 🏥 Hospitals
  - 👮 Police Stations
  - 🏛️ Embassies
  - 🚒 Fire Stations
- Distance and contact information
- One-click call functionality
- Safety tips and emergency guidelines

#### c) **My Bookings**
- View all confirmed bookings
- Transaction history
- Booking details with traveler count
- Quick access to receipts

## Technology Stack 🛠️

- **Frontend**: React 18.3.1 with TypeScript
- **Routing**: React Router 7.13.0 (Data Mode)
- **Animations**: Motion (Framer Motion) 12.23.24
- **Styling**: Tailwind CSS 4.1.12
- **Maps**: React Leaflet 5.0.0 + Leaflet 1.9.4
- **Icons**: Lucide React 0.487.0
- **Notifications**: Sonner 2.0.3
- **Confetti**: Canvas Confetti 1.9.4
- **UI Components**: Radix UI primitives
- **Authentication**: Simulated (localStorage-based)

## Getting Started 🚀

1. The app opens on the landing page with login/signup options
2. Click "Sign Up" to create an account
3. Verify your email with code: `123456`
4. Explore packages on the home page
5. Try AI recommendations by clicking "Get AI-Powered Recommendations"
6. Select a package and customize travelers
7. Proceed to payment and choose your payment method
8. View your receipt and access the dashboard
9. Complete your safety checklist before traveling
10. View emergency locations on the interactive map

## Key User Flows 🔄

### Booking Flow
Landing → Signup → Email Verification → Home → Package Details → Payment → Success → Dashboard

### AI Recommendation Flow
Home → AI Questions (5 steps) → AI Analysis → Personalized Results → Package Selection

### Safety Flow
Dashboard → Checklist Tab → Complete Items → AI Auto-Support (if overdue)

### Emergency Flow
Dashboard → Emergency Map Tab → View Locations → Call Emergency Services

## Important Notes 📝

- **Demo Authentication**: Uses localStorage (not production-ready)
- **Payment Simulation**: No real payment processing
- **Email Verification**: Always use code `123456`
- **AI Support**: Simulated with toast notifications
- **Emergency Map**: Shows demo locations in New York City

## Features Highlights 🌟

1. **Smooth Animations**: Every interaction is animated for better UX
2. **Responsive Design**: Works on all screen sizes
3. **User-Friendly**: Intuitive navigation and clear CTAs
4. **Safety First**: Comprehensive checklist and emergency features
5. **AI-Powered**: Smart recommendations based on preferences
6. **Complete Flow**: From browsing to booking to post-booking support

## Payment Methods Details 💳

- **PhonePe**: Quick mobile payments
- **Google Pay**: Seamless digital wallet integration
- **UPI**: Enter your UPI ID for direct bank transfer
- **Cash**: Pay when you arrive at destination

## Receipt Download 📄

After successful payment:
1. Click "Download" button on receipt
2. Text file with complete transaction details
3. Includes booking info, payment method, and transaction ID
4. Save for your records

---

**Enjoy your journey with AI Tourism Portal!** 🎉
