# Ride-Sharing API Service 🚗💨

A backend API service for a ride-sharing application built with Node.js and Express.

## Features ✨

### Customer Features
- ✅ User registration and authentication
- ✅ Ride booking and cancellation
- ✅ Payment processing
- ✅ Ride type selection
- ✅ Driver rating system
- ✅ Profile management

### Driver Features
- ✅ Ride acceptance and completion
- ✅ Vehicle registration
- ✅ Earnings tracking

### Admin Features
- ✅ User blacklisting
- ✅ System analytics
- ✅ Complaint handling
- ✅ Driver management

## API Endpoints 🌐

### Customer Routes
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/customer/register` | POST | Register new customer |
| `/api/login` | POST | Login for all user types |
| `/api/customer/book` | POST | Book a ride |
| `/api/customer/cancel` | POST | Cancel a ride |
| `/api/customer/payment` | POST | Process payment |
| `/api/customer/ride-types` | GET | Get available ride types |
| `/api/customer/rate` | POST | Rate a driver |
| `/api/customer/profile` | GET | View customer profile |
| `/api/customer/ride-fare` | GET | View ride fare details |
| `/api/customer/view-rating` | GET | View driver rating |

### Driver Routes
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/driver/accept-ride` | POST | Accept ride request |
| `/api/driver/complete-ride` | POST | Complete a ride |
| `/api/driver/register-vehicle` | POST | Register vehicle |
| `/api/driver/earnings` | GET | View earnings |

### Admin Routes
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/admin/blacklist` | POST | Blacklist a user |
| `/api/admin/analytics` | GET | View system analytics |
| `/api/admin/complaints` | POST | Handle complaints |
| `/api/admin/driver-list` | GET | View driver list |

## Installation ⚙️

1. Clone the repository:
```bash
git clone https://github.com/iman229/ride-sharing-api.git