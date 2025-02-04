Full Stack AI SaaS Application - Text to Image Generator

📌 Project Overview

This is a Full Stack AI SaaS (Software as a Service) application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application allows users to generate images using AI by providing text prompts. It features a credit-based system where users can generate images based on available credits and purchase additional credits through an integrated online payment gateway.

🛠️ Tech Stack

Frontend: React.js

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Token)

Payment Gateway: Integrated for purchasing credits

AI API: ClipDrop API (for generating images)

✨ Features

🔐 User Authentication: Secure sign-up and login system using JWT.

🎨 Text-to-Image Generation: AI-generated images based on user prompts using the ClipDrop API.

💳 Credit System: Users have limited credits to generate images and can purchase more via an online payment gateway.

💰 Payment Integration: Secure and seamless payment gateway integration to buy additional credits.

📊 User Dashboard: View generated images, available credits, and transaction history.

📡 MERN Stack Implementation: Efficient and scalable full-stack web application.

🚀 Installation & Setup

Clone the Repository

git clone https://github.com/your-username/ai-saas-text-to-image.git
cd ai-saas-text-to-image

Backend Setup (Node.js + Express + MongoDB)

Navigate to the backend folder:

cd backend

Install dependencies:

npm install

Create a .env file and add the following environment variables:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLIPDROP_API_KEY=your_clipdrop_api_key
PAYMENT_GATEWAY_KEY=your_payment_gateway_key

Start the backend server:

npm run dev

Frontend Setup (React.js)

Navigate to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the frontend server:

npm start

📌 API Endpoints

Authentication Routes

POST /api/auth/register - User Registration

POST /api/auth/login - User Login

Image Generation

POST /api/image/generate - Generate an AI image based on text input

Credits & Payment

GET /api/credits - Get user credit balance

POST /api/payment - Purchase more credits

📸 Screenshots

![image](https://github.com/user-attachments/assets/5e899346-c351-4669-a949-699463c674ae)

Login/signup

![image](https://github.com/user-attachments/assets/ed8bd541-1ff9-4bc1-9a17-98ba60da68ab)

Image generation 
![image](https://github.com/user-attachments/assets/63b7952f-9f28-4da3-8d02-bfeabe95ae56)

Purchasing credits
![image](https://github.com/user-attachments/assets/aa05486d-5b92-4310-b103-573f9ff13e5c)





📜 License

This project is open-source and available under the MIT License.
