# Bankist Application

#### Video Demo: https://www.youtube.com/watch?v=W2JTOxgZGtU

#### Description:

The **Bankist Application** is a functional banking web application built with HTML, CSS, and JavaScript. It is designed to simulate banking features, allowing users to view account balances, make transfers, and interact with various account details. The project integrates modern JavaScript techniques such as DOM manipulation, event handling, and object-oriented programming to create a realistic and interactive experience. The app is aimed at improving user engagement through dynamic features like a real-time transaction history and an intuitive UI.

## Features:

- **User Authentication:** Users can log into their accounts using their credentials, which are stored in the application as hardcoded data. The application allows a simulated login process.
- **Account Balance & Transaction History:** Once logged in, users can view their current balance and a history of transactions, including deposits and withdrawals.
- **Transfer Between Accounts:** Users can transfer money between different accounts within the system. If a user attempts to transfer more money than they have in their balance, the application shows a warning.
- **Loan Request Simulation:** Users can request a loan within a certain limit. The loan is granted if the user’s balance meets the necessary conditions.
- **Sort Transactions:** Users can sort their transaction history by date or amount to get a better overview of their financial activities.
- **Interactive Features:** The app includes features like input validation, form handling, and an alert system for user actions like invalid logins or unsuccessful transfers.

## Technologies Used:

- **HTML5:** Used for structuring the content of the web page, including forms, buttons, and data displays.
- **CSS3:** Applied to create a clean, responsive design that ensures the application looks great on both desktop and mobile devices. Flexbox and Grid are used for layout management.
- **JavaScript (ES6+):** Used for all the dynamic functionality of the app, including DOM manipulation, event handling, and logic for transactions, user authentication, and account management. This includes the use of functions, objects, arrays, and conditional statements.
- **Local Storage (Optional for future versions):** In future iterations, the app could be extended to save user data in the browser’s local storage, allowing users to persist their session between page refreshes.

## How to Use:

1. **Login:** Open the application in a browser. You will be prompted to enter a username and PIN (the default username is “js” and the PIN is “1111”). This allows you to access the main features of the app.
2. **Account Overview:** After logging in, you will see the account balance, transaction history, and available actions such as transferring money or applying for a loan.
3. **Making a Transfer:** To transfer money, select the recipient’s account and enter the amount. The application will check if the user has sufficient funds and notify them if the transaction is successful.
4. **Loan Application:** You can request a loan if you meet the app’s criteria. Loans are simulated, and the request process includes checks for account eligibility.
5. **Transaction Sorting:** The app allows you to sort transactions by various criteria, including date or amount, by clicking on the relevant buttons.
6. **Logging Out:** Users can log out at any time, which resets the session and returns them to the login screen.

## Future Enhancements:

The Bankist application is intended to be a base for more advanced banking features. Some possible future enhancements include:

- **Real User Authentication:** Implementing a back-end service that allows for actual user registration, authentication, and session management using databases and server-side languages like Node.js.
- **Database Integration:** Integrating the app with a database to store user data, account balances, and transactions, making it a fully dynamic system that can handle large datasets.
- **Mobile App Version:** Creating a mobile-first version or even a mobile app using frameworks like React Native to allow users to manage their finances on the go.
- **Security Improvements:** Adding security features such as data encryption, password hashing, and HTTPS for secure data transmission.

## Challenges Faced:

One of the challenges faced while building the Bankist application was simulating the user interactions in a way that feels realistic. Since this project relies on hardcoded data, there are limitations on how dynamic the user experience can be. However, the use of JavaScript allowed for sophisticated manipulation of the DOM to display messages, update transaction histories, and provide feedback to users during their interaction with the app.
Another challenge was ensuring that the various features, such as sorting transactions and handling loan requests, were integrated seamlessly into the app’s workflow. This required a good understanding of JavaScript functions, conditionals, and the DOM API.

## Conclusion:

The Bankist application serves as a demonstration of front-end development capabilities using JavaScript, HTML, and CSS. By simulating basic banking functionalities, it provides a user-friendly and interactive experience that can be extended and improved in the future. The project showcases the power of JavaScript in building dynamic applications and has laid the foundation for more complex
