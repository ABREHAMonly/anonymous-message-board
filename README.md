# anonymous-message-board


#Project Overview

The Anonymous Message Board is a web application that allows users to post and interact with messages without creating an account. 
It promotes free expression, making it useful for students, professionals, and local communities in Ethiopia. The platform ensures anonymity, 
creating a safe space for users to share ideas, ask questions, or discuss sensitive topics.

#Key Features

✅ User Posts Messages Without an AccountUsers can submit messages instantly without logging in. Each post is assigned a random ID (e.g., "User1234") for temporary identification.

📢 Topic-Based Discussion RoomsUsers can select a category when posting (e.g., "University Students", "Job Seekers", "Technology"). Each category has a separate message board.

🔼 Upvote & Downvote SystemUsers can upvote or downvote posts to highlight useful content. Posts with more upvotes move to the top of the board.

🛠 Moderation & Content Filtering

Automatic spam detection (removes repeated or harmful content).

Admin dashboard to delete inappropriate messages.

AI-based filtering to detect and block toxic messages.

🌍 Ethiopian Context-Specific Features

Amharic Language Support: Users can post in Amharic, English, or other local languages.

Local Topics: Categories like "Ethiopian News", "Education in Ethiopia", "Daily Life in Addis Ababa".

Low-Bandwidth Mode: Simplified UI for areas with slow internet.

#Technology Stack (MERN Stack)

Frontend: React.js (React Router, Tailwind CSS for UI)

Backend: Node.js + Express.js (Handles API routes for messages, voting, and moderation)

Database: MongoDB + Mongoose (Stores messages, upvotes/downvotes, and categories)

Authentication: JSON Web Token (JWT) for admin authentication (if needed)

AI Integration: Machine Learning model to detect toxic messages and filter them

#Future Enhancements

🚀 Add comment replies to messages.
🛡 Allow users to report inappropriate content.
