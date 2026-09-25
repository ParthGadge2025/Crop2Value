# 🌾 CROP2VALUE

<p align="center">
  <img src="assets/crop2value-harvesting.gif" alt="Crop2Value animated tractor harvesting" width="900"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=28&pause=900&color=2E7D32&center=true&vCenter=true&width=900&lines=Turn+Agricultural+Waste+Into+Rural+Wealth;Sell+Crop+Residue+%7C+Find+Buyers+%7C+Rent+Equipment;Connect+Farmers%2C+Buyers+%26+Rural+Businesses;From+Field+to+Marketplace+%E2%80%94+Smarter+%26+Sustainable" alt="Crop2Value typing animation"/>
</p>

<p align="center"><b>🚜 A multilingual smart marketplace for farmers, buyers, renters, processors and rural businesses.</b></p>

<p align="center">
  <a href="#-features">Features</a> • <a href="#-how-it-works">How It Works</a> • <a href="#-technology">Technology</a> • <a href="#-architecture">Architecture</a> • <a href="#-getting-started">Getting Started</a>
</p>

---

## 🌱 What is Crop2Value?

**Crop2Value** transforms agricultural residue and underused rural resources into economic opportunities.

Instead of letting crop residue become waste, farmers can **list, discover buyers, negotiate, aggregate, arrange pickup and earn**.

> 🌾 **Crop Residue Marketplace** + 🚜 **Equipment Rental** + 🤝 **Buyer/Seller Matching** + 📦 **Aggregation** + 💬 **Real-Time Negotiation** + 🎙️ **Voice Control** + 🌐 **5-Language Experience**

### 🎯 Vision

> **“Turn Agricultural Waste Into Rural Wealth.”**

---

# ✨ Features

### 🌾 Agricultural Residue Marketplace

Rice straw • Wheat straw • Cotton stalk • Sugarcane bagasse • Corn residue • Coconut husk • Coconut shells • Fruit/vegetable waste • Groundnut shells • Biomass products.

### 🤝 Buyer ↔ Seller Connection

Every listing can support **chat, make offer, counter offer, purchase request, contact, save and report** workflows.

```text
Farmer → Listing → Buyer → Offer → Counter Offer → Acceptance → Pickup → Completed Transaction
```

### 📦 Smart Aggregation

```text
Farmer A 500 kg ┐
Farmer B 700 kg ├── 📦 Aggregation Batch ── 🏭 Bulk Buyer
Farmer C 800 kg ┘
```

### 🚜 Equipment Rental

List or rent tractors, rotavators, harvesters, cultivators, sprayers, threshers, pumps and trolleys with availability calendars, rates, booking requests and owner-renter chat.

### 📋 Reverse Marketplace / Request Board

Buyers can post what they need instead of waiting for sellers to list it. Renters can post equipment requirements too.

### 🎙️ Multilingual Voice Control

Supported languages:

**English · हिन्दी · मराठी · മലയാളം · தமிழ்**

Example commands:

```text
“Find rice straw buyers near me”
“मेरे पास के ट्रैक्टर किराए पर दिखाओ”
“माझ्या जवळचे खरेदीदार दाखवा”
“കാർഷിക ഉപകരണങ്ങൾ വാടകയ്ക്ക് കാണിക്കുക”
“என் அருகிலுள்ள வாங்குபவர்களைக் காட்டு”
```

Voice can also pre-fill forms from natural speech.

### 🤖 Crop2Value AI Assistant

Helps users find buyers, discover equipment, create listings, understand categories, navigate the platform and work across supported languages.

### 🌐 Five-Language Interface

🇬🇧 English · 🇮🇳 Hindi · 🇮🇳 Marathi · 🇮🇳 Malayalam · 🇮🇳 Tamil

### 🌙 Dark + Light Mode

Supports **Light / Dark / System** preferences and remembers the user's selection.

### 📍 Smart Location Matching

Search nearby buyers, sellers, equipment, services and collection centers using configurable distance filters.

### ⭐ Trust & Safety

Verified-user badges, ratings, reviews, completed-transaction history, response rate, reporting and blocking.

### 💬 Real-Time Messaging

One-to-one chat, listing context, offers, images, typing indicator, read status and notifications.

---

# 🎬 Animation System

The README and product concept use animation as part of the story:

```text
🌱 Field → 🌾 Growing Crop → 🚜 Harvest → 📦 Collection → 🏭 Buyer → 💰 Farmer Earnings
```

The repository includes a lightweight animated harvesting GIF showing a tractor moving through a crop field and harvesting the crop.

The website itself can extend this with:

- Typing effects
- Scroll reveal
- Animated statistics
- Voice microphone pulse
- Marketplace matching animations
- Notification micro-interactions
- Loading skeletons
- Smooth page transitions
- Harvest-to-market storytelling

---

# 🧭 How It Works

```text
           🌾 FARMER
               │
               ▼
        📱 CREATE LISTING
               │
               ▼
          🔎 SMART MATCH
               │
       ┌───────┴────────┐
       ▼                ▼
    🏭 BUYER         🚜 RENTER
       │                │
       └───────┬────────┘
               ▼
          💬 CONNECT
               │
               ▼
        💰 NEGOTIATE / BOOK
               │
               ▼
          📦 PICKUP / USE
               │
               ▼
          ⭐ COMPLETE
```

---

# 🏗️ Architecture

```text
                     ┌──────────────────┐
                     │  Next.js / React │
                     │  Mobile-first UI │
                     └────────┬─────────┘
                              │
              ┌───────────────┼────────────────┐
              ▼               ▼                ▼
        🎙️ Voice Layer   🤖 AI Layer        🗺️ Maps
              └───────────────┼────────────────┘
                              ▼
                     ┌──────────────────┐
                     │ API / Server     │
                     │ Next.js Backend  │
                     └────────┬─────────┘
                              ▼
                     ┌──────────────────┐
                     │    Supabase      │
                     │ PostgreSQL/Auth  │
                     │ Storage/Realtime │
                     └────────┬─────────┘
                              ▼
             ┌────────────────┼─────────────────┐
             ▼                ▼                 ▼
         👨‍🌾 Farmers       🏭 Buyers         🚜 Renters
                              │
                              ▼
                       📦 Rural Value Chain
```

---

# 🛠️ Technology

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Frontend:** Next.js, React, TypeScript, Tailwind CSS, shadcn/ui, Lucide

**Backend:** Next.js API/server actions

**Database:** Supabase PostgreSQL

**Realtime:** Supabase Realtime

**Auth & Storage:** Supabase Auth + Storage

**Voice:** Web Speech API with provider abstraction

**AI:** Secure server-side AI integration

**Payments:** Razorpay-ready architecture

---

# 🗂️ Core Modules

```text
Crop2Value
├── 🏠 Home
├── 🌾 Marketplace
│   ├── Crop Residue
│   ├── By-products
│   ├── Processed Products
│   └── Services
├── 🚜 Equipment Rental
├── 📋 Request Board
├── 📦 Aggregation
├── 💬 Messages
├── 🔔 Notifications
├── 🤖 AI Assistant
├── 🎙️ Voice Control
├── 📊 Analytics
├── ♻️ Impact Dashboard
├── 👤 Profile
└── 🛡️ Admin
```

---

# 📊 Impact Dashboard

Track platform-level metrics such as:

```text
🌾 Residue Listed
♻️ Material Diverted
💰 Farmer Earnings
🤝 Farmers Connected
🏭 Buyers Connected
🚜 Equipment Rentals
📦 Successful Transactions
```

---

# 🔐 Security

- Authentication and authorization
- Role-based access control
- Protected admin routes
- Server-side validation
- Secure database queries
- Private messaging authorization
- File upload validation
- Environment-variable secrets
- Approximate public locations
- Reporting / blocking / moderation architecture

---

# 📱 PWA & Low-Bandwidth Design

Designed for real-world connectivity:

- Installable PWA
- Optimized assets
- Image optimization
- Cached application shell
- Reconnection/sync architecture
- Push notification architecture
- Mobile-first, low-bandwidth UI

---

# ⚙️ Getting Started

```bash
git clone https://github.com/YOUR_USERNAME/crop2value.git
cd crop2value
npm install
npm run dev
```

Create `.env.local`:

```env
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=
AI_API_KEY=
NEXT_PUBLIC_MAPS_API_KEY=
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=
```

Then open:

```text
http://localhost:3000
```

---

# 🧪 Main User Journeys

### 👨‍🌾 Farmer

`Register → Language → List → Upload → Quantity → Location → Publish → Offers → Chat → Accept → Pickup → Complete`

### 🏭 Buyer

`Register → Search → Filter → Listing → Offer → Negotiate → Confirm → Pickup`

### 🚜 Renter

`Search → Equipment → Availability → Dates → Request → Owner Accepts → Rental Confirmed`

### 🎙️ Voice

`Microphone → Speech → Intent → Action → Results`

---

# 🌍 Roadmap

- [ ] Advanced AI material recognition
- [ ] Multilingual AI voice assistant
- [ ] WhatsApp integration
- [ ] UPI payments
- [ ] Advanced logistics optimization
- [ ] Digital weighing integration
- [ ] IoT-enabled collection centers
- [ ] Regional buyer networks
- [ ] Carbon / impact reporting
- [ ] Enterprise procurement portal
- [ ] Native mobile application
- [ ] Advanced offline-first workflows
- [ ] More Indian languages

---

# 🌾 From Waste to Value

Traditional flow:

```text
CROP → HARVEST → RESIDUE → ❌ WASTE
```

Crop2Value flow:

```text
CROP
 ↓
🚜 HARVEST
 ↓
🌾 RESIDUE
 ↓
📱 LIST
 ↓
🔎 MATCH
 ↓
🤝 CONNECT
 ↓
📦 AGGREGATE
 ↓
🚚 COLLECT
 ↓
🏭 PROCESS
 ↓
💰 EARN
```

> **What looks like waste to one person can become a resource for another.**

---

# 👨‍💻 Developer

**Parth Gajanan Gadge**  
B.Tech — Computer Science & Engineering

`Python` • `Full-Stack Development` • `AI/ML` • `Data Analytics` • `Problem Solving`

---

<p align="center">
  <b>🌾 CROP2VALUE</b><br/>
  <i>Waste Less. Earn More. Grow Together.</i>
</p>

<p align="center">
  <img src="assets/crop2value-harvesting.gif" alt="Crop2Value harvesting animation" width="700"/>
</p>

<p align="center">⭐ Star the repository if you like the concept.</p>
