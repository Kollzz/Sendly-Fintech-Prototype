# Sendly - Requirements Engineering Document

### 1. Requirements Gathering Techniques

To gather accurate and complete requirements for the Sendly app, the following techniques were used:

### 1.1 Interviews
We conducted short interviews among potential users (students, freelancers, mobile money agents) to understand their financial transaction habits, pain points, and expectations from a mobile fintech app.

### 1.2 Brainstorming
The development team held brainstorming sessions to quickly generate a broad list of features that could solve common money transaction problems in Sierra Leone and similar regions.

### 1.3 Questionnaire/Survey
A short survey was distributed to potential users to rank desired features like sending/receiving money, viewing balance, and transaction alerts.

### 1.4 Observation
We observed how people use existing mobile money apps like Orange Money, Africell Money, or PayPal to understand common user flows and frustrations.

### 1.5 Document Analysis
We reviewed documentation and UX flows of other successful fintech apps like Chipper Cash, Paystack, and OPay to learn from best practices and common industry standards.

---

## 2. Functional Requirements

1. The user shall be able to register using their phone number or email.
2. The user shall be able to log in securely using a password.
3. The user shall be able to send money to another user within the app.
4. The user shall be able to receive money from other users.
5. The user shall be able to view their current wallet balance.
6. The user shall be able to view a history of their past transactions.
7. The user shall be able to reset a forgotten password.
8. The admin shall be able to view and manage user accounts.
9. The admin shall be able to block or suspend suspicious accounts.

---

## 3. Non-Functional Requirements

1. The system should respond to user actions within 3 seconds.
2. All sensitive data must be encrypted both in transit and at rest.
3. The app must support 24/7 uptime and ensure transaction reliability.
4. The UI should be responsive and optimized for mobile use.
5. The app should be able to handle up to 10,000 concurrent users.
6. The system should enforce secure login (including optional 2FA).
