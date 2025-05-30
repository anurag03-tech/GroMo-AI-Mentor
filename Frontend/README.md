# GroMo AI Copilot Frontend

Android application for GroMo AI Copilot, built with Kotlin and Jetpack Compose.

## Local Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/gromo-ai-copilot.git
   cd gromo-ai-copilot/Frontend
   ```

2. Open the project in Android Studio:

   - Launch Android Studio
   - Select "Open an Existing Project"
   - Navigate to the Frontend directory and click "OK"

3. Create a `local.properties` file in the root directory and add your configuration:

   ```
   sdk.dir=path_to_your_android_sdk
   GEMINI_API_KEY=your_gemini_api_key
   BACKEND_API_URL=your_backend_api_url
   ```

4. Build and run the application:

   - Click the "Run" button (green play icon) in Android Studio
   - Or use the command line:
     ```bash
     ./gradlew assembleDebug
     ./gradlew installDebug
     ```

5. Start the Backend server first (see Backend README)

## Features

- Modern UI with Jetpack Compose
- Integration with Gemini AI
- WhatsApp message analysis
- Customer interaction management

## Security

- API keys are stored in `local.properties`
- Sensitive data is not committed to version control
- Secure communication with backend

## Building

```bash
# Build debug APK
./gradlew assembleDebug

# Build release APK
./gradlew assembleRelease

# Install debug APK
./gradlew installDebug
```

## Dependencies

- Jetpack Compose for UI
- Retrofit for network calls
- Gemini AI SDK
- Coroutines for async operations
