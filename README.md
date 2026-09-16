# THC Delivery

Customer: First Name + Surname -> WAITING -> rider accepts -> private room -> chat + customer GPS -> ON THE WAY -> DELIVERED.

Files:
- index.html — customer page
- rider.html — rider dashboard
- firebase-rules.json — Firebase Realtime Database Rules

Firebase setup:
1. Enable Anonymous Authentication.
2. Enable Email/Password Authentication.
3. Create rider account(s) under Authentication -> Users.
4. Replace Realtime Database Rules with firebase-rules.json and Publish.
5. For a clean first test, delete old test data under active_deliveries and deliveries only.

GitHub Pages: upload index.html and rider.html to the repository root and publish the main branch root folder.
