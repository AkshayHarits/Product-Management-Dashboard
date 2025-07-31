# Product Management Dashboard

A full-stack MERN application to manage products — featuring create, update, and delete operations with a modern UI and RESTful backend.

![Demo Screenshot](/frontend/public/screenshot-for-readme.png)

## Tech Stack

- Frontend: React.js (Vite) + Chakra UI  
- Backend: Node.js + Express.js  
- Database: MongoDB  
- API Architecture: RESTful

## Features

- Add, update, and delete products  
- Responsive and clean UI using Chakra UI  
- REST API for CRUD operations  
- MongoDB for persistent data storage  
- Production-ready frontend build with Vite

## Setup Instructions

### 1. Create a `.env` file in the root directory:

```
MONGO_URI=your_mongo_connection_string
PORT=5000
```

### 2. Install dependencies and build the frontend:

```
npm install
cd frontend
npm install
npm run build
```

### 3. Start the server:

```
cd ..
npm run start
```

The server will run on `http://localhost:5000` and serve both the API and the frontend build.

### 4. Run frontend in development mode:

```
cd frontend
npm run dev
```

The frontend will be live at `http://localhost:5173`

## Project Structure

```
Product-Management-Dashboard/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── store/
│       ├── App.jsx
│       └── main.jsx
├── .env
├── package.json
└── README.md
```

## Notes

- Ensure MongoDB is running locally or your cloud URI is valid.
- The server port can be configured via the `.env` file.