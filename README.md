
# MongoDB-ADS

A Node.js + MongoDB project with basic backend APIs and a simple frontend interface.

## Project Structure
- `frontend/` — Contains the HTML/CSS frontend files.
- `models/` — MongoDB (Mongoose) data models.
- `routes/` — Express route handlers.
- `index.js` — Main server setup.
- `k.js` — Additional backend logic.
- `package.json` — Project dependencies and scripts.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/RONALDMASLOG2024-2025/MongoDB-ADS.git
cd MongoDB-ADS
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Create a `.env` File
Inside the project root, create a file named `.env` and add the following:

```
PORT=5000
MONGO_URI=your-mongodb-atlas-uri-here
```
> Replace `your-mongodb-atlas-uri-here` with your actual MongoDB Atlas connection string.

Example:
```
MONGO_URI=mongodb+srv://yourusername:yourpassword@cluster.mongodb.net/?retryWrites=true&w=majority
```

### 4. Start the Backend Server
```bash
npm run dev
```
> This uses **nodemon** for live reloading.

---

## Running the Frontend

The frontend is located in the `frontend/` folder.

To run it:
1. Open the `frontend/signup.html` file.
2. Use **Live Server** (Visual Studio Code extension) or any static server to view it.

> In VS Code: Right-click `signup.html` → **Open with Live Server**.

---

## Notes
- Make sure MongoDB Atlas is properly configured (IP whitelisting, cluster running).
- Keep your `.env` file secure — never commit it publicly.
- Feel free to extend the project by adding new models, routes, and UI features.

---

## Built With
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
```

---
