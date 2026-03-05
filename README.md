Build a modern FinTech web application called **GoalSplit** that helps users split their salary or money into different savings goals.

The core concept is **goal-based money allocation (digital envelopes)** where users create goals such as shopping, gadgets, travel, emergency funds, etc., and allocate money toward those goals.

Main Features:

1. **User Authentication**

* Users can sign up, log in, and manage their account.
* Store user data securely.

2. **Goal Creation**

* Users can create savings goals.
* Each goal includes:

  * Goal name
  * Target amount
  * Current saved amount
  * Optional deadline
  * Category (shopping, gadget, travel, etc.)

3. **Money Allocation**

* Users can deposit money into a specific goal.
* Users can split their salary into percentages across multiple goals.

Example:
Salary = ₹30,000
Shopping = 10%
PSP Fund = 20%
Emergency = 30%

4. **Progress Tracking**

* Display a visual progress bar for each goal.
* Show percentage completed and remaining amount.

5. **Early Withdrawal with Guilt Note**
   If a user tries to withdraw money before reaching the goal amount, show a confirmation message like:

"You are 72% close to completing your PSP goal. Withdrawing now will delay your purchase by approximately 2 weeks. Are you sure you want to break this goal?"

Allow users to either:

* Continue withdrawal
* Stay committed to the goal

6. **Dashboard**
   The main dashboard should display:

* Total balance
* Active goals
* Goal progress cards
* Recent transactions

7. **Transaction History**
   Track deposits and withdrawals for each goal.

8. **Goal Completion**
   When a goal reaches its target amount, mark it as completed and allow the user to withdraw funds without warnings.

Tech Stack Requirements:

* Frontend: React or Next.js
* Backend: Node.js with Express
* Database: PostgreSQL or MongoDB
* Use clean component-based architecture
* Include API endpoints for goals, transactions, and user management.

UI Requirements:

* Modern fintech-style UI
* Goal cards with progress bars
* Clean dashboard layout
* Mobile responsive

Bonus Features (optional but recommended):

* Notifications when users are close to completing a goal
* Estimated completion date
* Visual "money jars" or "goal cards" UI
* Simple analytics showing savings progress.

Provide:

1. Project folder structure
2. Database schema
3. API endpoints
4. Sample UI components
5. Example code snippets for key features.
