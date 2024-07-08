# An AI SaaS Platform

![image](https://github.com/AbhijitKhyade/Imaginify/assets/129264746/a4159767-6ae9-4496-991e-1e9bb4e7c511)


📋 Table of Contents
🤖 Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start


🤖 Introduction
Build an AI image SaaS platform that excels in image processing capabilities, integrates a secure payment infrastructure, offers advanced image search functionalities, and supports multiple AI features, including image restoration, recoloring, object removal, generative filling, and background removal.


⚙️ Tech Stack
Next.js
TypeScript
MongoDB
Clerk
Cloudinary
Stripe
Shadcn
TailwindCSS

🔋 Features
👉 Authentication and Authorization: Secure user access with registration, login, and route protection.

👉 Community Image Showcase: Explore user transformations with easy navigation using pagination

👉 Advanced Image Search: Find images by content or objects present inside the image quickly and accurately

👉 Image Restoration: Revive old or damaged images effortlessly

👉 Image Recoloring: Customize images by replacing objects with desired colors easily

👉 Image Generative Fill: Fill in missing areas of images seamlessly

👉 Object Removal: Clean up images by removing unwanted objects with precision

👉 Background Removal: Extract objects from backgrounds with ease

👉 Download Transformed Images: Save and share AI-transformed images conveniently

👉 Transformed Image Details: View details of transformations for each image

👉 Transformation Management: Control over deletion and updates of transformations

👉 Credits System: Earn or purchase credits for image transformations

👉 Profile Page: Access transformed images and credit information personally

👉 Credits Purchase: Securely buy credits via Stripe for uninterrupted use

👉 Responsive UI/UX: A seamless experience across devices with a user-friendly interface


🤸 Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/adrianhajdin/imaginify.git
cd imaginify
Installation

Install the project dependencies using npm:

npm run dev
Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:

#NEXT
NEXT_PUBLIC_SERVER_URL=

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the Clerk, MongoDB, Cloudinary and Stripe

Running the Project

npm run dev
Open http://localhost:3000 in your browser to view the project.
