# onlinemarketplace
Online Classified Marketplace Using Firebase
This is a fully functional online classified marketplace, similar to OLX or eBay, where users can buy and sell products. It is built using HTML, CSS, JavaScript, and Firebase for backend support. The project includes user management, real-time chat, product uploads, safe transactions, and more.

Features

User Profile & Authentication Management
User registration and login using Firebase Authentication.

Email and password verification.

Password reset functionality.

Profile updates stored in Firebase.

Product Uploading & Searching
Users can upload products by filling out a form with product details like name, category, and description.

Search functionality allows users to find products by keywords, seller email, or product category.

Buyer & Seller Interaction
Real-time chat for buyers and sellers to discuss products and negotiate.

Availability status of users updated in the database.

Secure Transactions
Transactions facilitated through an admin-mediated process to ensure customer protection.

Admin verifies each transaction using UPI payments, and sellers are prompted to confirm delivery.

Review & Complaints
After a transaction, buyers and sellers can rate each other and submit reviews.

Users can report complaints or give feedback, which is stored in a dedicated collection.

Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Firebase (Authentication, Firestore Database)

Payment Integration: UPI (via admin verification)

Setup Firebase

Create a Firebase project in the Firebase Console.

Configure Firebase Authentication and Firestore Database.

Update Firebase config in main.js with your Firebase project credentials.

Usage

Register as a user and verify email.

List Products by filling in the product upload form.

Search Products using the search bar or category filters.

Chat with sellers directly from the product page.

Buy products by initiating secure transactions through the admin.

Additional Information

Feedback & Reports: Users can submit feedback or report users via the settings page. This information is saved for admin review.

Settings: Allows users to update their profile, log out, and view app policies.

Contributing

Contributions are welcome! Feel free to fork the project and submit a pull request.
