# Vibe Book - Venue Booking Marketplace

A comprehensive marketplace platform for booking unique venues like private screening rooms, surprise party spaces, and event venues.

## Features

### Customer App
- Browse venues by category (Surprise Rooms, Private Screening, Party Spaces)
- Filter by price, capacity, and occasion
- View venue details with photos and amenities
- Real-time slot selection and booking
- Secure payment processing
- Booking history and reviews
- Dark mode support

### Vendor Portal
- Manage venue listings
- Upload photos and set pricing
- Update availability and slots
- Accept/reject booking requests
- View booking history and earnings
- Manage special offers
- Dark mode support

### Admin Panel
- Vendor approval workflow
- Platform metrics and analytics
- Revenue tracking (10% commission)
- Vendor performance monitoring
- Transaction management
- Dark mode support

## User Roles

### Demo Login

**Customer & Vendor:**
- **Email & Password:** Use any email and password to login
- **Mobile & OTP:** Use any 10-digit mobile number. Demo OTP: `123456`

**Admin:**
- Email: `vibebook@gmail.com`
- Password: `vibebook12345`
- Admin access is restricted to authorized personnel only

The app demonstrates three user roles:

1. **Customer** - Browse and book venues
2. **Vendor** - Manage venues and bookings
3. **Admin** - Platform management and oversight

## Booking Policy

### Platform Fees
- **Platform Fee:** A minimum platform fee of ₹50 is charged on all bookings
- **Non-Refundable:** Platform fees are non-refundable during cancellation
- **Convenience Fee:** Vendor-specific convenience fees for cancellations may vary by venue

## Tech Stack

- React with TypeScript
- React Router for navigation
- Tailwind CSS for styling
- Shadcn UI components
- Mock data for demo purposes

## Note

This is a prototype with mock data. In production, this would connect to:
- Authentication service (Supabase Auth)
- Database (PostgreSQL)
- Payment gateway (Razorpay, Stripe)
- File storage for images
- Email notifications