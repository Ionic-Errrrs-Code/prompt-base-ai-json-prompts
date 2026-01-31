<div align="center">
  
<img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/logo.webp?v=1768606683126" alt="Prompt Base Logo" width="200"/>

# Prompt Base - AI Json Prompts

### Premium AI Prompt Marketplace for Creative Professionals

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-4CAF50?style=for-the-badge)](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://play.google.com/store/apps/details?id=com.ionicerrrrscode.promptbase)

[📱 Download on Google Play](https://play.google.com/store/apps/details?id=com.ionicerrrrscode.promptbase)

</div>

---

## 🎯 Overview

**Prompt Base** is a high-performance, cross-platform mobile application designed as a premium marketplace for AI-generated creative prompts. Built with Flutter and adhering to strict Clean Architecture principles, it offers a fluid, gallery-style interface for discovering and analyzing prompt engineering techniques. The app prioritizes user experience with zero-latency navigation, seamless infinite scrolling, and robust offline-first capabilities.

### ⏱️ Project Timeline
- **Duration:** 3 months
- **Status:** ✅ Completed
- **Team:** Ionic Errrrs Code
- **Rating:** ⭐⭐⭐⭐⭐

---

## ✨ Key Features

### 🔄 Infinite Explorer
Seamlessly browse through thousands of AI prompts with butter-smooth infinite scrolling. Our optimized rendering engine ensures 60FPS performance even with high-resolution content.

### 🔍 Smart Search System
Lightning-fast search with intelligent filtering and categorization. Find the perfect prompt in milliseconds with our advanced indexing system.

### 💫 Interactive Details
Rich, immersive detail views with full prompt metadata, usage statistics, and related suggestions. Each prompt comes alive with contextual information.

### ⚡ Performance Optimized
Built from the ground up for speed. Sub-second transition times, aggressive caching strategies, and memory-efficient image loading ensure a premium experience.

### 🛡️ Robust Error Handling
Comprehensive error handling with graceful degradation. Users always know what's happening with clear, actionable feedback.

---

## 🏗️ Technology Stack

<div align="center">

| Category | Technologies |
|----------|-------------|
| **Framework** | Flutter, Dart |
| **State Management** | BLoC (Business Logic Component) |
| **Architecture** | Clean Architecture |
| **Routing** | GoRouter |
| **Networking** | Dio with interceptors |
| **Dependency Injection** | GetIt |
| **Image Caching** | cached_network_image |

</div>

---

## 📸 Gallery

<div align="center">

### App Screenshots

<table>
  <tr>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/0.webp?v=1768607001968" alt="Screenshot 1" width="250"/></td>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/1.webp?v=1768607003318" alt="Screenshot 2" width="250"/></td>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/2.webp?v=1768607004521" alt="Screenshot 3" width="250"/></td>
  </tr>
  <tr>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/3.webp?v=1768607005831" alt="Screenshot 4" width="250"/></td>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/4.webp?v=1768607007136" alt="Screenshot 5" width="250"/></td>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/5.webp?v=1768607008327" alt="Screenshot 6" width="250"/></td>
  </tr>
  <tr>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/6.webp?v=1768607009632" alt="Screenshot 7" width="250"/></td>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/7.webp?v=1768607010890" alt="Screenshot 8" width="250"/></td>
    <td><img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-ai-json-prompts/8.webp?v=1768607012061" alt="Screenshot 9" width="250"/></td>
  </tr>
</table>

</div>

---

## 🏛️ Architecture

Prompt Base follows **Clean Architecture** principles, ensuring:

- 📦 **Separation of Concerns:** Clear boundaries between UI, business logic, and data layers
- 🧪 **Testability:** Highly modular codebase with dependency injection
- 🔧 **Maintainability:** Easy to understand, modify, and extend
- 🔄 **Scalability:** Decoupled architecture allows for easy feature adaptability

### Architecture Layers

```
┌─────────────────────────────────────┐
│         Presentation Layer          │
│         (BLoC + UI Widgets)         │
├─────────────────────────────────────┤
│          Domain Layer               │
│      (Use Cases + Entities)         │
├─────────────────────────────────────┤
│           Data Layer                │
│   (Repositories + Data Sources)     │
└─────────────────────────────────────┘
```

---

## 🎯 Challenges & Solutions

### Challenge 1: Complex State Management
**Problem:** Orchestrating multiple asynchronous data streams (Feeds, Search, User Auth) without race conditions.

**Solution:** Implemented a reactive, event-driven state machine using the **BLoC Pattern** for every feature, ensuring predictable state transitions and easy debugging.

### Challenge 2: Media Performance
**Problem:** Rendering grids of high-resolution images and autoplaying videos without memory leaks or jank.

**Solution:** Utilized **layered caching** with Dio interceptors for API caching and cached_network_image for media assets to minimize bandwidth usage and memory footprint.

### Challenge 3: Feature Isolation
**Problem:** Maintaining strict separation of concerns while allowing inter-feature communication (e.g., Search triggering Explorer updates).

**Solution:** Used **GetIt** for dependency injection to decouple data repositories from UI logic, making the codebase highly testable and modular.

---

## 📊 Results & Achievements

### 🌐 Cross-Platform Delivery
Successfully unified the experience across Android and iOS with a single codebase, reducing development time and maintenance overhead.

### ⚡ Performance Excellence
Achieved consistent **60FPS scrolling** and **sub-second transition times**, delivering a premium user experience that rivals native applications.

### 🚀 Scalability & Maintainability
Decoupled architecture allows for easy feature adaptability and testing, with comprehensive test coverage and clear separation of concerns.

---

## 🛠️ Development

### Prerequisites
- Flutter SDK (3.0+)
- Dart SDK (3.0+)
- Android Studio / VS Code
- Xcode (for iOS development)

### Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/Ionic-Errrrs-Code/prompt-base-ai-json-prompts.git
cd prompt-base-ai-json-prompts
```

2. **Install dependencies**
```bash
flutter pub get
```

3. **Run the app**
```bash
flutter run
```

### Building for Production

**Android:**
```bash
flutter build apk --release
```

**iOS:**
```bash
flutter build ios --release
```

---

## 📱 Download

<div align="center">

[<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="80">](https://play.google.com/store/apps/details?id=com.ionicerrrrscode.promptbase)

</div>

---

## 👨‍💻 About

**Developed by:** [Ionic Errrrs Code](https://ionicerrrrscode.com)

A showcase of modern mobile development practices, demonstrating expertise in:
- Cross-platform mobile development
- Clean Architecture implementation
- Advanced state management with BLoC
- Performance optimization
- UI/UX excellence

---

## 📄 License

This project is proprietary software developed by Ionic Errrrs Code.

---

<div align="center">

**Built with ❤️ using Flutter**

⭐ If you found this project interesting, please star it!

</div>