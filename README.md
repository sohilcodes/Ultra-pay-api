# UltraPay - Payment Gateway

Same design as ultra-pay.store with Admin Panel.

## Demo Login Credentials

**Admin:**
- Phone: `9999999999`
- Password: `admin123`

**User:**
- Phone: `8888888888`
- Password: `user123`

## Features

**Login Page:** Same as ultra-pay.store - phone + password login, forgot password, register

**Admin Panel:**
- Overview dashboard with stats
- Users management (view, suspend/activate)
- Transactions table with filters
- Settings (site name, maintenance mode, transfer limits)

**User Dashboard:**
- Balance card
- Send money (2-step confirmation)
- Transaction history

---

## Deploy on Vercel (Step-by-Step)

### Option 1: GitHub + Vercel (Recommended)

1. **Upload to GitHub:**
   - Go to github.com → New repository → name it `ultrapay`
   - Upload all these files

2. **Deploy on Vercel:**
   - Go to vercel.com → Sign up/Login
   - Click "Add New Project"
   - Import your GitHub repo
   - Framework: **Create React App** (auto-detected)
   - Click **Deploy** ✅

### Option 2: Vercel CLI

```bash
npm install -g vercel
cd ultrapay
npm install
vercel
```

---

## Add Real Backend (Optional)

Currently uses demo data. To add real backend:

1. **Database:** Use Supabase (free) or Firebase
2. **API:** Replace demo functions in `LoginPage.js` with real API calls
3. **Payments:** Integrate Razorpay/PayU API

Contact your developer to connect real backend.
