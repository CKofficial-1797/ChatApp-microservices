# 🚀 Real-Time Chat Application with Microservices Architecture

This project is a **scalable, production-ready real-time chat application** built using a **MERN stack** combined with **microservices**.  
It integrates **RabbitMQ**, **Socket.IO**, **Redis caching**, **Dockerized services**, and **AWS deployment**, following best practices for modular, distributed systems.

## 🛠 Tech Stack

**Frontend:**
- React.js  
- Tailwind CSS  
- Responsive UI Design  

**Backend:**
- Node.js & Express.js  
- Socket.IO for real-time communication  
- RabbitMQ for asynchronous microservice communication  
- Redis for caching and session storage  
- MongoDB for NoSQL data persistence  

**Infrastructure:**
- Docker & Docker Compose  
- AWS (EC2) for deployment  

## 🔑 Key Features
- **Real-time Chat:** Powered by Socket.IO for instant messaging.  
- **OTP-based Email Authentication:** Secure user sign-up & login.  
- **Microservices Architecture:** Independent, scalable services communicating via RabbitMQ.  
- **Caching Layer:** Redis improves performance and reduces DB load.  
- **Scalable Backend:** Modular codebase ready for high traffic.  
- **Cloud-Ready:** Deployed and tested on AWS.  
- **Responsive Design:** Seamless experience across devices.
- 




 ⚠ **Note:** Due to AWS free tier expiration, the live demo is now shown on **localhost** during presentations. The architecture remains identical to the deployed version.



## 🧑‍💻 How to Run Locally
```bash
# Clone the repo
git clone https://github.com/yourusername/realtime-chat-app.git

# Navigate to project folder
cd realtime-chat-app

# Start all services
docker-compose up --build
