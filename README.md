# 🚗⚡ EV Service Center Maintenance Management System

<div align="center">

![EV Service](https://img.shields.io/badge/Vehicle-Electric-green?style=for-the-badge&logo=car)
![Flutter](https://img.shields.io/badge/Flutter-Multi--Platform-blue?style=for-the-badge&logo=flutter)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**Phần mềm quản lý bảo dưỡng xe điện cho trung tâm dịch vụ**

*Comprehensive Electric Vehicle Service Center Management Solution*

</div>

## 📋 Mục lục / Table of Contents

- [🎯 Giới thiệu](#-giới-thiệu--overview)
- [👥 Đối tượng sử dụng](#-đối-tượng-sử-dụng--target-users)
- [✨ Tính năng chính](#-tính-năng-chính--key-features)
  - [🔹 Khách hàng (Customer)](#-khách-hàng-customer)
  - [🔹 Trung tâm dịch vụ (Service Center)](#-trung-tâm-dịch-vụ-service-center)
- [🛠 Công nghệ sử dụng](#-công-nghệ-sử-dụng--technology-stack)
- [🚀 Cài đặt](#-cài-đặt--installation)
- [📱 Sử dụng](#-sử-dụng--usage)
- [🤝 Đóng góp](#-đóng-góp--contributing)
- [📄 Giấy phép](#-giấy-phép--license)

## 🎯 Giới thiệu / Overview

**EV Service Center Maintenance Management System** là một ứng dụng Flutter đa nền tảng được thiết kế để quản lý toàn diện các trung tâm bảo dưỡng xe điện. Ứng dụng chạy mượt mà trên iOS, Android, Web và Desktop, mang lại trải nghiệm nhất quán cho người dùng.

*A comprehensive Flutter multi-platform application for electric vehicle service centers, designed to optimize operations and enhance customer experience across iOS, Android, Web, and Desktop platforms.*

### 🌟 Tại sao chọn hệ thống của chúng tôi?

- ⚡ **Chuyên biệt cho xe điện**: Được thiết kế riêng cho đặc thù bảo dưỡng EV
- 📱 **Flutter Multi-Platform**: Một codebase cho tất cả nền tảng (iOS, Android, Web, Desktop)
- 🚀 **Hiệu năng cao**: Tận dụng sức mạnh của Flutter cho UI mượt mà
- 🔄 **Tự động hóa**: Giảm thiểu công việc thủ công
- 📊 **Báo cáo chi tiết**: Thống kê và phân tích dữ liệu toàn diện

## 👥 Đối tượng sử dụng / Target Users

| Vai trò | Mô tả | Quyền hạn |
|---------|--------|-----------|
| 👤 **Customer** | Khách hàng sở hữu xe điện | Đặt lịch, theo dõi xe, thanh toán |
| 👨‍💼 **Staff** | Nhân viên tiếp nhận | Quản lý lịch hẹn, tiếp nhận dịch vụ |
| 🔧 **Technician** | Kỹ thuật viên | Thực hiện bảo dưỡng, cập nhật tiến độ |
| 👨‍💻 **Admin** | Quản trị viên | Toàn quyền quản lý hệ thống |

## ✨ Tính năng chính / Key Features

### 🔹 Khách hàng (Customer)

#### 📋 **Theo dõi xe & nhắc nhở**
- 🔔 Nhắc nhở bảo dưỡng định kỳ theo km hoặc thời gian
- 💳 Nhắc thanh toán gói bảo dưỡng định kỳ
- 📅 Gia hạn gói dịch vụ tự động

#### 📅 **Đặt lịch dịch vụ**
- 🌐 Đặt lịch bảo dưỡng/sửa chữa trực tuyến
- 🏢 Chọn trung tâm dịch vụ & loại dịch vụ
- 🔄 Nhận xác nhận & thông báo trạng thái realtime:
  - ⏳ Chờ xử lý
  - 🔧 Đang bảo dưỡng  
  - ✅ Hoàn tất

#### 📊 **Quản lý hồ sơ & chi phí**
- 📖 Lưu lịch sử bảo dưỡng xe điện
- 💰 Quản lý chi phí bảo dưỡng & sửa chữa
- 💳 Thanh toán online đa dạng:
  - 📱 E-wallet (Momo, ZaloPay, VNPay)
  - 🏦 Internet Banking
  - 💳 Thẻ tín dụng/ghi nợ

### 🔹 Trung tâm dịch vụ (Service Center)

#### 👥 **Quản lý khách hàng & xe**
- 📝 Hồ sơ khách hàng chi tiết
- 🚗 Thông tin xe (model, VIN, lịch sử dịch vụ)
- 💬 Chat trực tuyến với khách hàng

#### 📅 **Quản lý lịch hẹn & dịch vụ**
- 📥 Tiếp nhận yêu cầu đặt lịch
- 👨‍🔧 Lập lịch cho kỹ thuật viên
- ⏰ Quản lý hàng chờ thông minh
- 📋 Phiếu tiếp nhận & checklist EV

#### 🔄 **Quản lý quy trình bảo dưỡng**
- 📊 Theo dõi tiến độ realtime:
  - ⏳ **Chờ**: Xe đang chờ được xử lý
  - 🔧 **Đang làm**: Đang trong quá trình bảo dưỡng
  - ✅ **Hoàn tất**: Đã hoàn thành dịch vụ
- 📝 Ghi nhận tình trạng xe chi tiết

#### 🔧 **Quản lý phụ tùng**
- 📦 Theo dõi số lượng phụ tùng EV
- ⚠️ Kiểm soát lượng tồn tối thiểu
- 📈 Báo cáo nhu cầu phụ tùng thay thế
- 📊 Đề xuất lượng tồn tối ưu

#### 👨‍💼 **Quản lý nhân sự**
- 📅 Phân công kỹ thuật viên theo ca/lịch
- 📊 Theo dõi hiệu suất & thời gian làm việc
- 🎓 Quản lý chứng chỉ chuyên môn EV
- 📈 Đánh giá năng suất nhân viên

#### 💰 **Quản lý tài chính & báo cáo**
- 💵 Quy trình: Báo giá → Hóa đơn → Thanh toán
- 💳 Hỗ trợ thanh toán online/offline
- 📊 Quản lý doanh thu, chi phí, lợi nhuận
- 📈 Thống kê:
  - 🔥 Loại dịch vụ phổ biến
  - 📉 Xu hướng hỏng hóc EV
  - 💹 Báo cáo tài chính định kỳ

## 🛠 Công nghệ sử dụng / Technology Stack

### 📱 Multi-Platform Framework
- 🎯 **Flutter** - Cross-platform framework chính
- 🎨 **Material Design 3** - UI Design System
- 🌈 **Custom Themes** - Adaptive theming cho từng platform

### 🏗️ Architecture & State Management
- 🏛️ **Clean Architecture** - Layered architecture pattern
- 🔄 **BLoC Pattern** - Business Logic Component
- 📦 **GetIt** - Dependency Injection
- 🗄️ **Repository Pattern** - Data abstraction layer

### 📊 Database & Storage
- 💾 **PostgreSQL** - Local database (PostgreSQL)
- ☁️ **Firebase Firestore** - Cloud database
- 🔐 **Secure Storage** - Encrypted local storage
- 📁 **Shared Preferences** - App settings storage

### 🌐 API & Networking
- 🔗 **HTTP/Dio** - REST API communication
- 🔥 **Firebase** - Backend services
- 📡 **Real-time Updates** - Firebase real-time database
- 🔔 **Push Notifications** - Firebase Cloud Messaging

### 🔐 Authentication & Security
- 🔒 **Firebase Auth** - User authentication
- 👤 **Google Sign-In** - Social authentication
- 🛡️ **Biometric Auth** - Fingerprint/Face ID
- 🔑 **JWT Tokens** - Secure API access

### 📱 Platform-specific Features
- 📷 **Camera Integration** - Photo capture for reports
- 📍 **Location Services** - GPS tracking
- 📞 **Phone Integration** - Direct calling
- 📧 **Email Integration** - Email notifications
- 💳 **Payment Integration** - Multiple payment gateways

### 🧪 Testing & Quality
- ✅ **Unit Testing** - Business logic testing
- 🔧 **Widget Testing** - UI component testing
- 📱 **Integration Testing** - End-to-end testing
- 🔍 **Static Analysis** - Code quality tools

## 🚀 Cài đặt / Installation

### Yêu cầu hệ thống / Prerequisites

```bash
Flutter SDK >= 3.16.0
Dart SDK >= 3.2.0
Android Studio / VS Code
Xcode (for iOS development)
```

### Cài đặt dự án / Project Setup

```bash
# Clone repository
git clone https://github.com/huynhthaitu124/EV-Service-Center-Maintenance-Management-System.git
cd EV-Service-Center-Maintenance-Management-System

# Install dependencies
flutter pub get

# Generate code (if using build_runner)
dart run build_runner build

# Setup Firebase configuration
# Add your google-services.json (Android)
# Add your GoogleService-Info.plist (iOS)
```

### Chạy ứng dụng / Run Application

```bash
# Run on debug mode
flutter run

# Run on specific platform
flutter run -d chrome          # Web
flutter run -d android         # Android
flutter run -d ios             # iOS
flutter run -d windows         # Windows Desktop
flutter run -d macos           # macOS Desktop
flutter run -d linux           # Linux Desktop

# Build for production
flutter build apk              # Android APK
flutter build ios              # iOS
flutter build web              # Web
flutter build windows          # Windows
```

### Cấu hình môi trường / Environment Configuration

```dart
// lib/config/environment.dart
class Environment {
  static const String apiBaseUrl = 'https://your-api-url.com';
  static const String firebaseProjectId = 'your-project-id';
  static const bool isProduction = bool.fromEnvironment('dart.vm.product');
}
```

## 📱 Sử dụng / Usage

### Khách hàng (Customer)

1. **Tải ứng dụng** từ App Store/Google Play hoặc truy cập web
2. **Đăng ký tài khoản** và thêm thông tin xe điện
3. **Đặt lịch bảo dưỡng** qua giao diện thân thiện
4. **Theo dõi tiến độ** dịch vụ realtime
5. **Thanh toán** trực tuyến sau khi hoàn tất

### Nhân viên trung tâm (Staff)

1. **Đăng nhập** với tài khoản được cấp
2. **Sử dụng tablet/desktop** để quản lý hiệu quả
3. **Tiếp nhận** yêu cầu từ khách hàng
4. **Phân công** kỹ thuật viên
5. **Cập nhật** trạng thái dịch vụ

### Kỹ thuật viên (Technician)

1. **Sử dụng mobile app** để nhận nhiệm vụ
2. **Cập nhật tiến độ** làm việc realtime
3. **Chụp ảnh** ghi nhận tình trạng xe
4. **Hoàn tất** và chuyển giao

### Quản trị viên (Admin)

1. **Dashboard web** để quản lý tổng quan
2. **Xem báo cáo** chi tiết và thống kê
3. **Cấu hình** thông số hệ thống
4. **Phân tích** dữ liệu kinh doanh

## 📸 Screenshots

<details>
<summary>🖼️ Xem ảnh minh họa các platform</summary>

### Mobile App (iOS & Android)
![Mobile Dashboard](docs/images/mobile-dashboard.png)
![Mobile Booking](docs/images/mobile-booking.png)

### Web Application
![Web Dashboard](docs/images/web-dashboard.png)
![Web Reports](docs/images/web-reports.png)

### Desktop Application
![Desktop Dashboard](docs/images/desktop-dashboard.png)

</details>

## 🗺️ Roadmap

- [x] **Phase 1**: Core Flutter app development (Q1 2024)
- [x] **Phase 2**: Multi-platform optimization (Q2 2024) 
- [ ] **Phase 3**: Advanced analytics & AI integration (Q3 2024)
- [ ] **Phase 4**: IoT device integration (Q4 2024)
- [ ] **Phase 5**: Multi-language support & accessibility (Q1 2025)

## 🤝 Đóng góp / Contributing

Chúng tôi hoan nghênh mọi đóng góp từ cộng đồng Flutter! 

### Cách đóng góp:

1. 🍴 Fork repository
2. 🌿 Tạo feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to branch (`git push origin feature/AmazingFeature`)
5. 🔀 Tạo Pull Request

### Coding Standards

- 📝 Tuân thủ Flutter/Dart style guide
- ✅ Viết unit tests cho features mới  
- 📚 Cập nhật documentation
- 🌐 Hỗ trợ đa ngôn ngữ (VI/EN)
- 📱 Test trên nhiều platform trước khi submit

### Development Setup

```bash
# Install Flutter analyzer
dart pub global activate dart_code_metrics

# Run code analysis
flutter analyze

# Run tests
flutter test

# Format code
dart format .
```

## 📞 Hỗ trợ / Support

- 📧 **Email**: huynhthaitu124@gmail.com
- 💬 **Discord**: [EV Service Community](https://discord.gg/evservice)
- 📱 **Hotline**: +84 xxx xxx xxx
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/huynhthaitu124/EV-Service-Center-Maintenance-Management-System/issues)
- 📖 **Documentation**: [Wiki](https://github.com/huynhthaitu124/EV-Service-Center-Maintenance-Management-System/wiki)

## 📄 Giấy phép / License

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

```
MIT License

Copyright (c) 2025 Huynh Thai Tu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

<div align="center">

**⭐ Nếu dự án này hữu ích, hãy cho chúng tôi một star! ⭐**

Made with ❤️ and Flutter by [Huynh Thai Tu](https://github.com/huynhthaitu124)

![Flutter](https://img.shields.io/badge/Made%20with-Flutter-blue?style=for-the-badge&logo=flutter)

</div>
