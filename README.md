Encrypted VOIP - End-to-End Encrypted Voice Communication
Overview

Encrypted VOIP is a secure real-time voice communication web application that enables users to communicate privately using end-to-end encryption. The application utilizes WebRTC for peer-to-peer audio transmission, Socket.IO for signaling, RSA-2048 for secure key exchange, and AES-GCM for audio encryption.

 Features
Real-time voice communication
End-to-End Encryption (E2EE)
RSA-2048 Key Exchange
AES-GCM Audio Encryption
WebRTC Peer-to-Peer Connection
Secure Signaling with Socket.IO
Low Latency Audio Streaming
Modern Responsive Interface
🛠️ Tech Stack
Frontend
React.js (Vite)
JavaScript
HTML5
CSS3
Backend
Node.js
Express.js
Socket.IO
Security
RSA-2048
AES-GCM
Web Crypto API
Communication
WebRTC
Web Audio API
AudioWorklet
📂 Project Structure
Encrypted-VOIP/
│
├── client/
│   ├── src/
│   ├── public/
│
├── server/
│   ├── server.js
│   ├── middleware/
│   └── signaling/
│
├── README.md
└── package.json
⚙️ Installation
Clone Repository
git clone https://github.com/Gourav22-ja/Encripted-VOIP.git
cd Encripted-VOIP
Install Backend Dependencies
cd server
npm install
Install Frontend Dependencies
cd client
npm install
Run Backend
npm start
Run Frontend
npm run dev
🔒 Encryption Workflow
User joins a voice session.
RSA-2048 public keys are exchanged.
AES session key is securely generated.
Audio packets are encrypted using AES-GCM.
Encrypted audio is transmitted through WebRTC.
Receiver decrypts audio and plays it in real-time.
📸 Screenshots

Add:

Home Page Screenshot
Voice Call Interface Screenshot
Encryption Status Screenshot
🎯 Future Improvements
Video Calling
Group Voice Calls
Chat Messaging
Screen Sharing
Call Recording with Encryption
