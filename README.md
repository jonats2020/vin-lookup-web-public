# 🚗 VIN Report Web App

A web application built with **React.js**, **Firebase**, and **Stripe** that allows users to enter a **VIN (Vehicle Identification Number)** to retrieve a car's ownership and maintenance history. After payment, a full report is generated and delivered to the user's email as a downloadable **PDF**.

![kaaromi](https://github.com/user-attachments/assets/dbbf81d2-ad61-45d0-b0f6-62afbcce4d55)

---

## 🔧 Tech Stack

- **Frontend:** React.js
- **Backend:** Firebase Functions
- **Database & Auth:** Firebase Firestore & Firebase Authentication
- **Payments:** Stripe
- **PDF Generation & Delivery:** Node.js + Email Service (e.g., SendGrid)

---

## ✨ Features

- VIN input form to fetch vehicle data
- Stripe-powered secure payment flow
- PDF report generation
- Automated email delivery with report
- Firebase-authenticated user flow

---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/vin-report-app.git
cd vin-report-app
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Set Up Environment Variables
Create a .env file in the root directory and add the following:
```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_bucket
VITE_FIREBASE_APP_ID=your_app_id
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### 4. Run the App Locally
```bash
npm run dev
```

---

## 📁 Project Structure
```pgsql
vin-report-app/
├── functions/         # Firebase functions (Stripe, PDF, email logic)
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   └── services/
├── .env
├── package.json
└── README.md
```

---

## 📫 Contact
📧 nats@natsdevstudio.com

---

## 📝 License
This project is licensed under the MIT License.
```pgsql
Let me know if you want a version customized with your actual project name, contact info, or specific API services.
```

