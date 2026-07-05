# Travel Memory - AWS EC2 Deployment

## Overview

This project demonstrates the deployment of the **Travel Memory** MERN Stack application on **Amazon Web Services (AWS)** using production best practices. The application is deployed on Amazon EC2 with Nginx as a reverse proxy, PM2 for process management, MongoDB Atlas as the database, AWS Application Load Balancer for scalability, and Cloudflare for custom domain and DNS management.

## Technology Stack

- React.js (Frontend)
- Node.js & Express.js (Backend)
- MongoDB Atlas
- Amazon EC2
- Nginx
- PM2
- AWS Application Load Balancer (ALB)
- Cloudflare DNS

## Features

- Deploy MERN application on AWS EC2
- Configure Nginx reverse proxy
- Process management using PM2
- MongoDB Atlas database integration
- Frontend and backend communication
- Load balancing using AWS ALB
- Custom domain configuration with Cloudflare
- Production-ready deployment

## Project Structure

```
TravelMemory/
├── frontend/
├── backend/
├── docs/
└── README.md
```

## Deployment Workflow

1. Launch an Amazon EC2 instance.
2. Install Node.js, Git, Nginx, and PM2.
3. Clone the GitHub repository.
4. Configure backend environment variables.
5. Install backend and frontend dependencies.
6. Build the React frontend.
7. Configure Nginx as a reverse proxy.
8. Start the backend using PM2.
9. Configure AWS Application Load Balancer.
10. Connect the custom domain using Cloudflare.
11. Verify the application deployment.

## Architecture

```
User
   │
Cloudflare
   │
Application Load Balancer
   │
┌───
│               
EC2 Instance 1  
│               │
React + Node.js + Nginx + PM2
        │
MongoDB Atlas
```

## Prerequisites

- AWS Account
- EC2 Instance (Ubuntu 22.04)
- MongoDB Atlas Cluster
- Cloudflare Account
- GitHub Repository
- Node.js 20+

## Installation

Clone the repository:

```bash
git clone https://github.com/UnpredictablePrashant/TravelMemory.git
cd TravelMemory
```

Install backend dependencies:

```bash
cd backend
npm install
```

Install frontend dependencies:

```bash
cd ../frontend
npm install
npm run build
```

## Backend Environment Variables

Create a `.env` file inside the `backend` folder.

```env
PORT=3000
MONGO_URI=<MongoDB Atlas Connection String>
JWT_SECRET=<Your Secret Key>
CLIENT_URL=https://your-domain.com
```

## Run Application

Start the backend using PM2:

```bash
pm2 start index.js --name travel-memory
pm2 save
```

Restart Nginx:

```bash
sudo systemctl restart nginx
