# GroMo AI Copilot

A comprehensive AI-powered WhatsApp business assistant that helps manage customer interactions, analyze messages, and provide intelligent responses.

## Project Structure

```
gromo-ai-copilot/
├── Frontend/           # Android application
│   ├── app/           # Main application code
│   └── ...
└── Backend/           # Node.js server
    ├── controllers/   # Route controllers
    ├── models/        # Database models
    ├── routes/        # API routes
    └── ...
```

## Features

- 🤖 AI-powered message analysis using Google's Gemini AI
- 💬 WhatsApp message integration
- 🎯 Smart response suggestions

## Quick Start

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/gromo-ai-copilot.git
   cd gromo-ai-copilot
   ```

2. Set up the Backend:

   ```bash
   cd Backend
   npm install
   # Create .env file with required variables
   npm run dev
   ```

3. Set up the Frontend:
   ```bash
   cd Frontend
   # Open in Android Studio
   # Create local.properties with required variables
   # Build and run the application
   ```

## Detailed Setup

For detailed setup instructions, please refer to the individual README files:

- [Frontend Setup](Frontend/README.md)
- [Backend Setup](Backend/README.md)

## Technology Stack

### Frontend

- Kotlin
- Jetpack Compose
- Retrofit
- Gemini AI SDK
- Coroutines

### Backend

- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Socket.IO

## Development

1. Start the Backend server first
2. Run the Android application
3. Ensure WhatsApp accessibility service is enabled
4. Test the integration

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
