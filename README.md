🐦 Twitter Clone – MERN Stack

A full-stack social media application inspired by Twitter, built with MongoDB, Express.js, React.js, and Node.js.
It allows users to sign up, post tweets, follow others, like & comment, and explore a dynamic timeline with real-time updates.

🧱 Tech Stack

Frontend: React.js, Tailwind CSS / Bootstrap
Backend: Node.js, Express.js
Database: MongoDB (MongoDB Atlas or Local)
Authentication: JWT (JSON Web Token) + bcrypt for password hashing
Image Uploads: Cloudinary

🎨 UI & General Features

Fully responsive, mobile-friendly design.

Navigation Bar:

Home, Explore, Notifications, Profile, Login/Logout

Modern, clean UI with real-time feedback on actions.

Show success/error messages for user actions.

🔐 Authentication

User Registration & Login

Secure password hashing using bcrypt.

Session management with JWT tokens.

Protected Routes

Only logged-in users can post, like, comment, or follow.

🌟 Core Features
1. Post Tweets

Create text-based tweets.

Optional image upload.

Character limit similar to Twitter (e.g., 280 characters).

Time-stamped posts.

2. Like & Comment

Like/unlike tweets.

Add and view comments on tweets.

Like counter updates in real-time.

3. Follow/Unfollow Users

Follow other users to see their tweets in your feed.

Unfollow to remove their tweets from your feed.

4. Timeline Feed

Home Feed: Shows tweets from followed users.

Explore: Shows all public tweets.

User Profile: Shows user’s tweets, likes, and following count.

5. Notifications

Real-time notifications for likes, comments, and follows.

📧 Optional Features

Hashtags: Clickable tags that show related tweets.

Retweets: Share other users' tweets to your timeline.

Direct Messaging: Real-time chat with other users using Socket.IO.

📦 Deliverables

✅ Fully working React frontend

✅ Fully working Node + Express backend

✅ MongoDB collections:

users

tweets

comments

notifications

✅ Protected API routes with validation
