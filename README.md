# 🎨 Imagify - AI Text to Image Generator

Imagify is a Full Stack AI SaaS application built using **MongoDB, Express, React, and Node.js** (MERN stack). The app allows users to generate images using AI by providing a **text prompt**. Users can purchase credits to generate images, and the application integrates a secure **payment gateway** to handle purchases.

This project utilizes **Clipdrop API** to generate high-quality images based on text inputs.

## Table of Contents 

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [Demo](#demo)
- [Future Improvements](#future-improvements)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

## Project Overview

Imagify is an AI-powered application that generates images from text inputs. Users can create an account, log in, and generate images using credits, which can be purchased through the integrated payment gateway. The generated images are powered by the **Clipdrop API**, which provides advanced image generation capabilities.

### Key Features:
- **Text to Image Generation**: Users can input a text prompt, and the app will generate an image using **Clipdrop API**.
- **Credit System**: Users receive credits upon sign-up and can purchase additional credits to generate more images.
- **User Authentication**: Secure login and registration using **MongoDB** and **Express** for handling user details.
- **Payment Integration**: Secure payment system integrated to purchase credits using **Razorpay** or other payment gateways.

## Tech Stack

- **Frontend**:
  - **React.js** (for building the user interface)
  - **Axios** (for API calls)
  - **React Router** (for navigation)
  - **Clipdrop API** (for image generation)
  - **Razorpay** (for payment processing)
  
- **Backend**:
  - **Node.js** (for server-side logic)
  - **Express.js** (for building the REST API)
  - **MongoDB** (for user authentication and credit storage)
  - **Mongoose** (for object modeling with MongoDB)

## Usage

- **As a User**:
  1. Sign up or log in to your account.
  2. Use the credits provided or purchase more credits.
  3. Enter a text prompt to generate images.
  4. Download the generated image.

## Demo

You can view the live demo of the project here:  
[Live Demo](https://imagify-frontend-five.vercel.app/)

## Future Improvements

Here are some features that could be added in the future to make this project even more powerful:

- **Image Editing**: Allow users to make edits to the generated images, such as cropping, resizing, and applying filters.
- **Multiple AI Models**: Integrate multiple AI models for different styles of image generation (e.g., photorealistic, cartoonish, abstract).
- **Social Media Sharing**: Allow users to directly share their generated images on platforms like Instagram, Twitter, or Facebook.

## Screenshots

Here are some screenshots of the project in action:

### 1. **Homepage**:  
![Homepage](https://i.imgur.com/MRHjeBu.png)  

### 2. **Credit Plans**:  
![Credit Plans](https://i.imgur.com/lhjXqEj.png)  

### 3. **Payment Gateway**:  
![Payment Gateway](https://i.imgur.com/wKfhr5L.png)  

### 4. **Image Generation**:  
![Image Generation](https://i.imgur.com/pzzcGiN.png)  


## Contributing

Contributions are welcome! 

Thank you for checking out Imagify! If you have any questions or would like the setup instructions to run the project locally, feel free to reach out to me directly.
