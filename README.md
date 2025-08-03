# Lucid Eye 👁️

> **AI-Powered Visual Assistance App for the Visually Impaired**

[![Flutter](https://img.shields.io/badge/Flutter-3.7.6-blue.svg)](https://flutter.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-lightgrey.svg)](https://flutter.dev/)

## 📱 Overview

Lucid Eye is an innovative Flutter application designed to assist visually impaired individuals by leveraging AI and Machine Learning technologies. The app provides real-time object detection, text recognition, currency identification, navigation assistance, and AI-powered chatbot support.

## ✨ Features

### 🔍 **Object Detection & Recognition**
- **Real-time Object Detection**: Identify objects in the environment using AI models
- **Text Recognition (OCR)**: Read and interpret text from images and documents
- **Currency Detection**: Identify and read currency denominations
- **Person Detection**: Detect people in the vicinity

### 🗺️ **Smart Navigation**
- **Maps Integration**: Search and navigate to places efficiently
- **Route Optimization**: Find the fastest routes to destinations
- **Voice-guided Navigation**: Audio cues for navigation assistance

### 🤖 **AI Chatbot Assistant**
- **Natural Language Processing**: Interactive conversations with AI
- **Context-aware Responses**: Intelligent assistance based on user needs
- **Voice Commands**: Hands-free interaction capabilities

### 🆘 **Emergency SOS System**
- **Emergency Contacts**: Quick access to emergency services
- **Assistant Network**: Connect with nearby volunteers for assistance
- **Location Sharing**: Share real-time location with trusted contacts

### 👥 **Assistant App Integration**
- **Volunteer Network**: Assistants can see and respond to help requests
- **Real-time Communication**: Direct communication between users and assistants
- **Location-based Matching**: Connect users with nearby assistants

## 🛠️ Technology Stack

### Frontend
- **Flutter 3.7.6** - Cross-platform mobile development
- **Dart** - Programming language
- **TensorFlow Lite** - AI model integration
- **Google Maps API** - Navigation services

### Backend Services
- **Node.js** - Maps navigation and assistance APIs
- **Flask (Python)** - Chatbot and AI processing APIs
- **Firebase** - Real-time database and authentication

### AI/ML Models
- **MobileNet V1** - Object detection
- **Custom OCR Models** - Text recognition
- **Currency Detection Models** - Money identification

## 📋 Prerequisites

- **Flutter SDK**: 3.7.6 or higher
- **Dart SDK**: 3.0.0 or higher
- **Android Studio** / **VS Code**
- **Android SDK** (for Android development)
- **Xcode** (for iOS development, macOS only)

## 🚀 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/nashe01/lucid-eye.git
cd lucid-eye
```

### 2. Install Dependencies
```bash
flutter pub get
```

### 3. Configure Environment
- Copy `.env.example` to `.env` (if available)
- Add your API keys for Google Maps and other services

### 4. Run the Application
```bash
# For Android
flutter run

# For iOS (macOS only)
flutter run -d ios
```

## 📱 Usage Guide

### For Visually Impaired Users

1. **Object Detection**
   - Point your camera at objects
   - The app will identify and describe what it sees
   - Use voice commands for hands-free operation

2. **Navigation**
   - Search for destinations using voice or text
   - Follow audio cues for navigation
   - Get real-time updates about your surroundings

3. **Chatbot Assistance**
   - Ask questions about your environment
   - Get help with daily tasks
   - Receive contextual information

4. **Emergency SOS**
   - Activate SOS mode for immediate assistance
   - Connect with nearby volunteers
   - Share your location with trusted contacts

### For Assistants

1. **View Help Requests**
   - See nearby users requesting assistance
   - View their location and needs

2. **Provide Support**
   - Accept assistance requests
   - Communicate directly with users
   - Navigate to their location

## 🔧 Configuration

### API Keys Setup
```dart
// Add your API keys in lib/config/api_config.dart
class ApiConfig {
  static const String googleMapsApiKey = 'YOUR_GOOGLE_MAPS_API_KEY';
  static const String openAiApiKey = 'YOUR_OPENAI_API_KEY';
  // Add other API keys as needed
}
```

### Model Configuration
- AI models are stored in `assets/aimodels/`
- Update model paths in `lib/config/model_config.dart`

## 📁 Project Structure

```
lucid-eye/
├── android/                 # Android-specific files
├── ios/                    # iOS-specific files
├── lib/
│   ├── config/            # Configuration files
│   ├── constants/         # App constants
│   ├── features/          # Feature modules
│   │   └── view/         # UI screens
│   ├── shared_components/ # Reusable components
│   └── main.dart         # App entry point
├── assets/
│   ├── aimodels/         # AI model files
│   └── images/           # App images
└── test/                 # Test files
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow Flutter best practices
- Write clean, documented code
- Add tests for new features
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Flutter Team** - For the amazing framework
- **Google Maps API** - For navigation services
- **TensorFlow Team** - For AI/ML capabilities
- **OpenAI** - For chatbot functionality
- **Contributors** - For their valuable contributions

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/nashe01/lucid-eye/issues)
- **Email**: [Your Email]
- **Documentation**: [Wiki Link]

## 🔮 Roadmap

- [ ] Voice command improvements
- [ ] Offline mode support
- [ ] Multi-language support
- [ ] Advanced AI models integration
- [ ] Wearable device support
- [ ] Community features enhancement

---

**Note**: This app is designed with accessibility in mind. Please ensure your device's accessibility features are enabled for the best experience.

**⚠️ Safety Notice**: Please run the app under no sound safety conditions when testing audio features.

