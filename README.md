# Nodeshare: Peer-to-Peer File Sharing and Conversion Website

## Overview

Nodeshare is a peer-to-peer (P2P) platform for seamless file sharing and file format conversions. The website enables users to upload, share, and convert files with ease while maintaining privacy and speed through advanced technology. Inspired by platforms like Convertio and ToffeeShare, Nodeshare provides an intuitive user experience for all file management needs.

## Features

1. **File Sharing**:
   - Upload files and share them via a secure link.
   - Peer-to-peer sharing with WebRTC and Socket.IO ensures data is not stored on centralized servers.
2. **File Conversion**:
   - Convert files between popular formats (e.g., PDF to Word, PNG to JPEG).
   - High-speed conversion with support for various file types using MULTER.
3. **User Management**:
   - Register and log in securely with Google OAuth.
   - Manage account details and preferences.
4. **Subscription Plans**:
   - Upgrade to premium plans for advanced features like larger file uploads and priority conversions.
   - Implented Stripe Payment Gateway for secure Payments

## Getting Started

1. Clone the repository.
2. Install the required dependencies using `npm install` on both `client` and `server`.
3. Configure the settings in the `.env` file in `client`.
4. Start the server using `npm start`.
5. Start the client using `npm run dev -- --host`.

## Contribution

We welcome contributions! Feel free to fork the repository and submit pull requests for new features or bug fixes.
