# GroMo AI Copilot Backend

This is the backend server for the GroMo AI Copilot application, built with Node.js and Express.

## Local Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/gromo-ai-copilot.git
   cd gromo-ai-copilot/Backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your environment variables:

   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Start MongoDB:

   - Make sure MongoDB is installed and running on your system
   - Or use MongoDB Atlas (cloud version)

5. Start the development server:

   ```bash
   # Development mode with auto-reload
   npm run dev

   # Production mode
   npm start
   ```

6. The server will be running at `http://localhost:5000`

## API Endpoints

- `/api/auth` - Authentication routes
- `/api/users` - User management routes
- `/api/chats` - Chat functionality routes

## Environment Variables

Required environment variables in `.env`:

```
PORT=5000
MONGO_URI=mongodb://localhost:27017/gromo
JWT_SECRET=your_secret_key
```

## Security

- All sensitive data is stored in environment variables
- JWT is used for authentication
- CORS is enabled for frontend communication

## Development

```bash
# Install dependencies
npm install

# Run in development mode
npm run dev

# Run in production mode
npm start

# Run tests
npm test
```
