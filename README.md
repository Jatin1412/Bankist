# Bankist App
Bankist is a modern banking application that allows users to manage their accounts, transfer money, request loans, and track their transactions. The app features a clean and responsive interface with user-friendly functionalities, including auto-logout after 5 minutes of inactivity.

Features
Login System: Users can log in using their unique username and PIN.
Account Summary: Display account balance, income, and outgoing transactions in real-time.
Transfer Funds: Easily transfer money between accounts.
Loan Requests: Users can request loans, subject to certain conditions.
Transaction History: Displays a complete list of transactions with formatted dates and currency.
Auto Logout: Users are automatically logged out after 5 minutes of inactivity for security reasons.
Table of Contents
Technologies Used
Installation
How to Use
Project Structure
Key Functionalities
Screenshots
License
Technologies Used
HTML5: For structuring the content.
CSS3: For styling the application interface.
JavaScript (ES6): For implementing logic and interactivity.
Date and Currency Formatting: Using Intl.DateTimeFormat and Intl.NumberFormat.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Jatin1412/bankist
Navigate to the project directory:

bash
Copy code
cd bankist-app
Open the index.html file in your browser.

No additional setup or installation is required as this is a frontend project.

How to Use
Log In:

You can log in using one of the two demo accounts:
Username: jk | PIN: 1111
Username: jd | PIN: 2222
View Transactions: After logging in, you will see all the past transactions with their respective dates.

Transfer Funds:

Enter a valid recipient's username and the amount to transfer.
Request a Loan:

Enter the desired loan amount. Loans are granted if any of the past deposits are at least 10% of the requested loan amount.
Close Account:

Enter your username and PIN to close your account.
Auto Logout:

If the user is inactive for 5 minutes, they will automatically be logged out.
Project Structure
bash
Copy code
├── index.html           # Main HTML file
├── style.css            # Styling for the application
└── script.js            # Main JavaScript file that handles the logic
Key Functionalities
Auto Logout Timer:

If there is no interaction for 5 minutes, the user is logged out.
Date Formatting:

Transaction dates are formatted dynamically based on how far the date is from the current date (e.g., "Today", "Yesterday", or "5 days ago").
Currency Formatting:

All financial amounts are formatted according to the user's locale and currency.
Transfer and Loan Features:

Users can send money to other accounts, and request loans based on deposit history.
Screenshots

License
This project is licensed under the MIT License. See the LICENSE file for details.
