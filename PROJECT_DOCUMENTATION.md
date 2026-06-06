# DOANCS3 Project Documentation

## 📱 Project Overview

**DOANCS3** is a full-featured Android e-commerce application built with Kotlin and Firebase. It provides a complete shopping experience including product browsing, cart management, order processing, and real-time chat functionality.

- **Project Name:** DOANCS3
- **Package Name:** com.example.doancs3
- **Min SDK:** 24
- **Target SDK:** 35
- **Compile SDK:** 35
- **Language:** Kotlin & Java
- **Build System:** Gradle Kotlin DSL

---

## 💼 CV Project Summary

### 📋 Project Description (For CV)

**DOANCS3 – Full-Stack Android E-Commerce Application**

Developed a comprehensive mobile e-commerce platform for Android that demonstrates proficiency in modern Android development practices and backend integration. This capstone project encompasses the complete development lifecycle from UI/UX design to backend API integration and payment processing.

**Key Achievements:**
- Architected and implemented a complete e-commerce ecosystem with 11+ screens supporting product discovery, shopping cart management, order processing, and real-time customer communication
- Integrated multiple payment gateways (VNPay, ZaloPay, Cashfree) with secure transaction handling and payment verification
- Implemented real-time cloud synchronization using Firebase services (Authentication, Firestore, Realtime Database, Cloud Storage)
- Designed scalable MVVM architecture with proper separation of concerns using ViewModels and adapters
- Optimized image loading and caching using Glide library with custom configuration
- Built responsive UI with Material Design 3.0 following Android best practices
- Implemented user authentication with email verification and session management
- Developed real-time messaging system for customer-seller communication

**Technical Highlights:**
- Clean architecture with MVVM pattern and proper data binding
- Firebase backend with real-time database synchronization
- RESTful API integration using Retrofit and OkHttp
- Custom payment gateway integration with secure signature validation
- Cloud image hosting via Cloudinary
- RecyclerView optimization with multiple custom adapters
- Unit testing and instrumented testing with JUnit and Espresso

---

## 🎯 Tech Stack Summary

### Frontend Stack
| Category | Technology |
|----------|-----------|
| **Language** | Kotlin 2.1.0, Java 17 |
| **UI Framework** | Android SDK 35, AndroidX |
| **UI Components** | Material Design 3.0, ConstraintLayout, RecyclerView |
| **Architecture** | MVVM Pattern, ViewBinding |
| **Image Loading** | Glide 4.15.1 with custom caching |

### Backend & Cloud
| Category | Technology |
|----------|-----------|
| **Authentication** | Firebase Auth (Email/Password + Verification) |
| **Database** | Firebase Firestore + Realtime Database |
| **File Storage** | Firebase Cloud Storage + Cloudinary |
| **API Client** | Retrofit 2.11.0 + OkHttp 4.12.0 |

### Payment Integration
| Category | Technology |
|----------|-----------|
| **Payment Gateways** | VNPay, ZaloPay, Cashfree |
| **Security** | MAC signature validation, HTTPS |
| **Deep Linking** | Custom URI scheme (doancs3://return) |

### Supporting Libraries
| Category | Technology |
|----------|-----------|
| **Serialization** | GSON 2.10.1 |
| **UI Enhancement** | Dots Indicator 5.1.0 |
| **Security** | Commons Codec 1.14 |
| **Testing** | JUnit 4, Espresso, AndroidTest |

---

## 🏗️ Project Structure

```
DOANCS3/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/doancs3/
│   │   │   │   ├── Activity/           # Screen controllers
│   │   │   │   ├── Adapter/            # RecyclerView adapters
│   │   │   │   ├── Model/              # Data models
│   │   │   │   ├── ViewModel/          # MVVM ViewModels
│   │   │   │   ├── Utilities/          # Helper utilities
│   │   │   │   ├── Helper/             # Database helpers
│   │   │   │   └── Glide/              # Image loading config
│   │   │   ├── res/
│   │   │   │   ├── layout/             # XML layouts
│   │   │   │   ├── drawable/           # Vector drawables
│   │   │   │   ├── values/             # Resources (colors, strings)
│   │   │   │   └── xml/                # Backup & extraction rules
│   │   │   └── AndroidManifest.xml
│   │   ├── test/                       # Unit tests
│   │   └── androidTest/                # Instrumented tests
│   ├── build.gradle.kts
│   └── google-services.json            # Firebase config
├── gradle/
│   └── libs.versions.toml              # Dependency versions
├── build.gradle.kts
├── settings.gradle.kts
└── gradle.properties
```

---

## 🛠️ Technologies & Dependencies

### Core Android Libraries
- **AndroidX Core:** `androidx.core:core-ktx:1.16.0`
- **AppCompat:** `androidx.appcompat:appcompat:1.7.0`
- **Material Design:** `com.google.android.material:material:1.12.0`
- **ConstraintLayout:** `androidx.constraintlayout:constraintlayout:2.2.1`
- **RecyclerView:** `androidx.recyclerview:recyclerview:1.3.2`

### Firebase Integration
- **Firebase BOM:** `33.12.0`
- **Firebase Authentication:** Email/password authentication with verification
- **Firestore:** Cloud database
- **Realtime Database:** Real-time data sync
- **Cloud Storage:** File/image storage

### Image & UI Libraries
- **Glide:** `com.github.bumptech.glide:glide:4.15.1` - Image loading and caching
- **Dots Indicator:** `com.tbuonomo:dotsindicator:5.1.0` - ViewPager indicator

### Networking & Data
- **Retrofit:** `com.squareup.retrofit2:retrofit:2.11.0` - HTTP client
- **OkHttp:** `com.squareup.okhttp3:okhttp:4.12.0` - Network interceptor
- **GSON:** `com.google.code.gson:gson:2.10.1` - JSON serialization
- **Cloudinary:** `com.cloudinary:cloudinary-android:2.3.1` - Cloud image hosting

### Payment & Security
- **VNPay Integration:** `com.cashfree.pg:api:2.1.17` - Payment gateway
- **ZaloPay:** Custom API integration for Vietnamese payment
- **Commons Codec:** `commons-codec:commons-codec:1.14` - Encoding/decoding

### Development
- **Kotlin:** `org.jetbrains.kotlin:kotlin-stdlib:2.1.0`
- **Kotlin KAPT:** Annotation processing
- **JUnit:** Unit testing
- **Espresso:** UI testing

---
