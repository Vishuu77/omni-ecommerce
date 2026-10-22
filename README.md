# 🛍️ Omni-eCommerce — Full-Stack Shopping Platform & Operations CRM
### **Inspired by Amazon & Flipkart &bull; Er. Vishnu Ramachandra (10th VTU Rank)**
*React 19 &bull; TypeScript &bull; Node.js &bull; Express &bull; WebSockets &bull; Google Sheets Persistence Engine*

[![React 19](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://vishuu77.github.io/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://vishuu77.github.io/)
[![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](https://vishuu77.github.io/)
[![Google Sheets Engine](https://img.shields.io/badge/Google_Sheets_Engine-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)](https://vishuu77.github.io/)

---

## 🏛️ Platform Highlights

1. **Customer Retail Storefront (`customer-portal.html` & `src/App.tsx`):**
   - High-fidelity shopping experience inspired by Amazon & Flipkart.
   - Dynamic catalog with categorized search, real-time stock levels, and instant OTP verification (`6361222162 -> 122162`).
   - Shopping cart management, address selection, payment gateway simulator, and live order tracking.
   - Self-service returns with policy validation and automated refund calculation.

2. **Employee Back-Office CRM (`employee-crm.html`):**
   - Live fulfillment queue synchronized via WebSockets (<50ms event latency).
   - Instant return authorization / rejection with automated audit trail logging.
   - Bi-directional customer support chat channel and callback scheduling.
   - Integrated AI support agent (Hexa) for automated inquiry resolution.

3. **Persistence Engine (`db-helper.js` & `data/`):**
   - Local-first Google Sheets CSV synchronization engine with in-memory transactional cache and atomic file flushes.

---

## 🚀 Quick Start (Local Development)

```bash
# Clone the repository
git clone https://github.com/Vishuu77/omni-ecommerce.git
cd omni-ecommerce

# Install dependencies
npm install

# Start full-stack development server
npm run dev
```

Visit `http://localhost:5173` for the React SPA, or open `customer-portal.html` and `employee-crm.html` in any browser.

---

## 🌐 Live Deployments & Portfolio Reference

- **Live Production Portfolio:** [https://vishuu77.github.io/](https://vishuu77.github.io/)
- **Master Platform Hub:** [https://github.com/Vishuu77/omnicommerce-hub](https://github.com/Vishuu77/omnicommerce-hub)

---

&copy; 2026 Er. Vishnu Ramachandra &bull; 10th University Rank, Visvesvaraya Technological University (VTU)
