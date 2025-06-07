# 🏦 Banker's Desk

**Banker's Desk** is a modern, interactive banking interface built with **HTML, CSS, and JavaScript**. It simulates a digital banking experience where users can log in, view their account activity, transfer money, request loans, and close their accounts — all through a clean, single-page interface.

---

## 🔐 Login Section

The app begins with a login form. Users must enter a valid **username** and **PIN**. If correct, the user's account dashboard is revealed.

![Login Page](images/login.png)

---

## 📊 Account Dashboard

Once logged in, users are presented with an overview of their account:

- **Last 8 Transactions** are displayed in the center panel.
- The interface dynamically updates based on the logged-in user's data.

![Account Info](images/account-info.png)

---

## 💸 Transfer Money Section

Located on the **right panel**, the first feature allows users to transfer money to another user's account.

- Users must enter the **recipient username** and **amount**.
- Transfers reflect immediately in both accounts.

![Transfer Money](images/transfer.png)

---

## 🏦 Request Loan Section

Just below the transfer section, users can request a **loan from the bank**.

- If eligible (e.g., if a deposit meets certain criteria), the loan is approved and added to the account.
- No backend — logic is simulated in JavaScript.

![Request Loan](images/loan.png)

---

## ❌ Close Account Section

The third section on the right allows users to **close their account**.

- Requires valid **username** and **PIN**.
- On confirmation, the account is removed from the session.

![Close Account](images/close-account.png)

---

## 📉 Bottom Summary Section

At the bottom of the app, a detailed **summary section** shows:

- **IN** – Total deposits
- **OUT** – Total withdrawals
- **INTEREST** – Interest earned on deposits

To the right, there's an **auto-logout timer** that logs the user out after **5 minutes of inactivity**.

![Bottom Summary](images/summary.png)

---

## ⚙️ Technologies Used

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**

---

## 🚀 Getting Started

To try the app locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bankers-desk.git
