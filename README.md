# Art Paid Work - Premium Earning Platform

**Art Paid Work** (also known as *ShoppingFree*) is a responsive, web-based digital earning platform built with HTML, CSS, JavaScript, and Firebase. It allows users to register, complete tasks, earn rewards, refer friends, and request withdrawals. It includes a secure Admin Panel for managing withdrawal requests.

## 🚀 Features

### 👤 User Features
- **Secure Authentication:** Sign up and Login using Email/Password (Firebase Auth).
- **Dashboard:** Real-time balance updates, Team counting, and Task access.
- **Profile Management:** View profile details, UID, and Referral Code.
- **Income Tracking:** 
  - View Current Balance.
  - **Realtime Total Income:** Calculates (Current Balance + Total Approved Withdrawals).
- **Withdrawal System:** 
  - Request withdrawals via Bkash/Nagad.
  - View withdrawal history with status (Pending, Approved, Rejected).
- **Referral System:** Earn commissions from referred users (Team count logic included).
- **Dark Premium UI:** Fully responsive dark theme with modern gradients and glassmorphism effects.

### 🛡️ Admin Features
- **Admin Dashboard:** Accessible only to users with `isAdmin: true` permission.
- **Withdrawal Management:** 
  - View all pending withdrawal requests.
  - **Approve:** Marks request as approved.
  - **Reject:** Marks request as rejected and **automatically refunds** the amount to the user's balance.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6).
- **Backend (BaaS):** Firebase (Authentication, Realtime Database).
- **Icons:** FontAwesome 6.
- **Fonts:** Google Fonts (Poppins).

## 📂 File Structure
