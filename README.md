# 🛡️ CamGuard AI

### Your Privacy. Your Protection.

**CamGuard AI** is an AI-assisted mobile privacy protection application designed to help users inspect hotel rooms, cabanas, private rooms, apartments, and indoor environments for potential hidden camera risks.

The application combines optical lens inspection, local network device discovery, infrared inspection (where supported), and AI-powered object recognition to identify suspicious devices and potential privacy threats.

> Our mission is to make personal privacy inspection more accessible through intelligent mobile technology.

---

## 🚀 Features

### 🔍 Lens Inspection
- Optical reflection analysis.
- Camera lens-like object inspection.
- Suspicious object highlighting.
- Guided physical inspection.

### 📡 Wi-Fi Network Scanner
- Local network device discovery.
- Device information inspection.
- IP address identification.
- Potential camera device indicators.

### 🌙 Infrared Inspection
- Infrared light detection where hardware supports it.
- Night vision LED inspection assistance.
- Device compatibility checking.

### 🤖 AI Object Detection
- AI-assisted object recognition.
- Suspicious device identification.
- Object classification.
- Detection confidence analysis.

### 📊 Security Reports
- Inspection summaries.
- Risk assessment.
- Evidence management.
- Scan history.
- Report generation.

---

## 📱 Supported Platforms

- Android
- iOS

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform development |
| Dart | Application programming |
| Python | AI model development |
| OpenCV | Computer vision |
| TensorFlow Lite / LiteRT | On-device AI inference |
| Kotlin | Android native integration |
| Swift | iOS native integration |
| SQLite | Local data storage |
| Riverpod | State management |
| GoRouter | Navigation |

---

## 📂 Project Structure

```text
camguard_ai/
├── android/
├── ios/
├── assets/
│   ├── images/
│   ├── icons/
│   ├── fonts/
│   └── models/
├── lib/
│   ├── core/
│   ├── features/
│   ├── routing/
│   ├── shared/
│   ├── theme/
│   └── main.dart
├── test/
├── integration_test/
├── docs/
├── pubspec.yaml
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

- Flutter SDK
- Dart SDK
- Android Studio or VS Code
- Android SDK
- Git

### Clone Repository

```bash
git clone https://github.com/koshada368/camguard_ai.git
```

### Navigate to Project

```bash
cd camguard_ai
```

### Install Dependencies

```bash
flutter pub get
```

### Check Flutter Environment

```bash
flutter doctor
```

### Run Application

```bash
flutter run
```

---

## 🌿 Git Branch Strategy

| Branch | Purpose |
|---|---|
| main | Stable production code |
| dev | Active development |
| feature/* | Individual feature development |
| hotfix/* | Urgent production fixes |

All new features should be developed in separate feature branches and merged into `dev` through Pull Requests.

Stable releases will be merged into `main` after testing.

---

## 🔐 Privacy & Security

CamGuard AI is designed with a privacy-first approach.

- Prefer on-device processing.
- Minimize collection of personal data.
- Secure local evidence storage.
- Request only necessary permissions.
- Provide transparent detection results.

---

## ⚠️ Important Disclaimer

CamGuard AI is an inspection assistance tool, not a guaranteed hidden camera detector.

Not all hidden cameras can be detected using smartphone hardware or software.

Network scanning cannot identify every camera, and optical or infrared analysis may produce false positives or miss devices.

A result showing no suspicious evidence does not guarantee that an environment is free of cameras.

---

## 📈 Development Status

**Current Stage:** Initial Development

Planned milestones:

- [x] Project concept and architecture
- [x] Initial Flutter application foundation
- [ ] Complete UI implementation
- [ ] Camera integration
- [ ] Optical lens inspection
- [ ] Local network scanner
- [ ] AI object detection
- [ ] Infrared inspection compatibility
- [ ] Risk assessment engine
- [ ] Scan history and reports
- [ ] Android testing
- [ ] iOS testing
- [ ] Production release

---

## 👨‍💻 Developer

**Project:** CamGuard AI

**GitHub:** [@koshada368](https://github.com/koshada368)

---

## 📄 License

License information will be added before public distribution.

---

### Your Privacy. Your Protection. 🛡️
