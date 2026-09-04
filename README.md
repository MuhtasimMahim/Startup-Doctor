# Startup Doctor — 🚀 2024 e-ICON World Contest 🏆 1st Prize

<div align="center">

![Startup Doctor Banner](Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_01.jpg)

### **Navigate Your Startup to Success**
**1st Prize (Minister of Education Award / 교육부 장관상)**  
**The 14th e-ICON World Contest (2024) — High School Division**  
*Presented by Team G7 — TýrNav (Republic of Korea & Bangladesh)*

<br />

[![Contest](https://img.shields.io/badge/e--ICON%20Contest-2024%201st%20Prize-gold?style=for-the-badge&logo=trophy)](https://e-icon.or.kr/en/2024%eb%85%84-%ec%a0%9c14%ed%9a%8c-%ea%b3%a0%eb%93%b1%eb%b6%80-1%eb%93%b1-%ea%b5%90%ec%9c%a1%eb%b6%80-%ec%9e%a5%ea%b4%80%ec%83%81/)
[![Download APK](https://img.shields.io/badge/Download-Android%20APK-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://drive.google.com/file/d/1D4N8m6HFse-BEZCMGTp21Hzq4doC0Z4M/view)
[![Watch Demo](https://img.shields.io/badge/YouTube-Demonstration%20Video-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/Q-OZVXMgY7s?si=rWkn7szGlKqEbwDT)
[![Expo](https://img.shields.io/badge/Expo-SDK%2051-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev)
[![React Native](https://img.shields.io/badge/React_Native-0.74.5-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactnative.dev)

</div>

---

## 📌 Quick Links

| Resource | Link |
| :--- | :--- |
| 🏆 **Official Contest Winner Page** | [e-ICON World Contest 2024 — 1st Prize](https://e-icon.or.kr/en/2024%eb%85%84-%ec%a0%9c14%ed%9a%8c-%ea%b3%a0%eb%93%b1%eb%b6%80-1%eb%93%b1-%ea%b5%90%ec%9c%a1%eb%b6%80-%ec%9e%a5%ea%b4%80%ec%83%81/) |
| 📱 **Direct APK Download** | [Startup Doctor APK on Google Drive](https://drive.google.com/file/d/1D4N8m6HFse-BEZCMGTp21Hzq4doC0Z4M/view) |
| 🎬 **YouTube Demonstration Video** | [Watch App Demonstration](https://youtu.be/Q-OZVXMgY7s?si=rWkn7szGlKqEbwDT) |
| 📑 **Presentation Document (PDF)** | [Download Presentation PDF](Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29.pdf) |
| 📄 **Project Proposal Document (PDF)** | [Download Project Proposal PDF](Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx.pdf) |

---

## 📖 About The Project

**Startup Doctor** is an all-in-one mobile ecosystem designed to empower early-stage entrepreneurs, students, and small-to-medium enterprises (SMEs) with practical knowledge, community networking, and funding opportunities.

Developed for the **14th e-ICON World Contest (2024)** by **Team G7 (TýrNav)** — an international collaboration between high school students from South Korea and Bangladesh — the project directly addresses **UN Sustainable Development Goal #8: Decent Work and Economic Growth**.

### Key Challenges Solved:
1. **Limited Access to Capital & Funding:** Bridging the gap between early startups and grants, angel investors, and venture capital.
2. **Low Visibility for Early Startups:** A verified business directory allowing entrepreneurs to showcase products, connect, and collaborate.
3. **Lack of Mentorship & Business Foundations:** Step-by-step interactive educational modules with knowledge quizzes covering finance, marketing, legal structures, and operations.

### ✨ Main Features
- **Interactive Onboarding:** Animated multi-step introduction to startup fundamentals powered by Lottie.
- **Structured Learning Modules:** Curated courses across startup stages with interactive module quizzes.
- **Business Directory:** Register and explore startups, discover partnerships, and share business profiles.
- **Funding Hub:** Comprehensive database of grants, seed funds, angel networks, and investor pitching guides.
- **Authentication & Cloud Sync:** Real-time user accounts, bookmarks, and business listings powered by Appwrite Cloud.

---

## 🚀 How to Run Locally

Follow these instructions to set up the development environment and run the project locally without errors.

### 1. Prerequisites

Make sure you have the following installed on your machine:
- **Node.js**: v18.0 or newer (Node.js 20+ LTS recommended). Check with:
  ```bash
  node -v
  ```
- **npm** (comes with Node.js) or **yarn**.
- **Mobile Device or Emulator**:
  - **Android (Recommended):** Install **Expo Go** from Google Play Store on your Android phone.
  - **Android Emulator:** Set up via Android Studio with ADB configured.
  - **iOS:** Install **Expo Go** from the Apple App Store, or run on iOS Simulator (macOS required).

---

### 2. Clone & Install Dependencies

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MuhtasimMahim/Startup-Doctor.git
   cd Startup-Doctor
   ```

2. **Install project dependencies:**
   ```bash
   npm install
   ```

*(Note: The project dependencies have been verified and pinned to official Expo SDK 51 patch releases for smooth out-of-the-box building).*

---

### 3. Start the Development Server

Run the Expo development server:

```bash
npm start
```
*or*
```bash
npx expo start
```

This starts the Metro Bundler and outputs an interactive QR code in your terminal.

---

### 4. Running on Your Device

#### Option A: Physical Android / iOS Device via Expo Go (Fastest & Easiest)
1. Connect your computer and mobile device to the **same local Wi-Fi network**.
2. Run `npm start`.
3. Open **Expo Go** on your device:
   - **Android:** Tap **Scan QR code** inside Expo Go and scan the terminal QR code.
   - **iOS:** Open the default **Camera** app, point at the QR code, and tap the notification banner.

#### Option B: Android Emulator / Connected Device via USB
If you have an Android emulator running or a device connected via USB with ADB debugging enabled:
- Press `a` in the terminal running Expo, or run:
  ```bash
  npm run android
  ```

#### Option C: Web Browser
- Press `w` in the terminal running Expo, or run:
  ```bash
  npm run web
  ```

#### Terminal Shortcuts

| Key | Description |
| :---: | :--- |
| `a` | Open on Android emulator or connected device |
| `i` | Open on iOS simulator |
| `w` | Open in web browser |
| `r` | Reload the app |
| `m` | Toggle developer menu |
| `c` | Show terminal QR code |

---

### 5. Backend Configuration (Appwrite)

The application connects to **Appwrite Cloud** for authentication, user profiles, and directory storage (`lib/appwrite.js`). The public project credentials are preconfigured for local development, so no extra backend configuration is required to test the application.

---

## 📊 Presentation Slides

Below are all **23 presentation slides** from Team G7 (TýrNav) for **Startup Doctor**.

> 📄 **Download PDF:** [G7 TyrNav Presentation File.pdf](Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29.pdf)

<div align="center">

### Slide 01
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_01.jpg" alt="Slide 01" width="850" />

### Slide 02
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_02.jpg" alt="Slide 02" width="850" />

### Slide 03
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_03.jpg" alt="Slide 03" width="850" />

### Slide 04
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_04.jpg" alt="Slide 04" width="850" />

### Slide 05
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_05.jpg" alt="Slide 05" width="850" />

### Slide 06
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_06.jpg" alt="Slide 06" width="850" />

### Slide 07
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_07.jpg" alt="Slide 07" width="850" />

### Slide 08
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_08.jpg" alt="Slide 08" width="850" />

### Slide 09
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_09.jpg" alt="Slide 09" width="850" />

### Slide 10
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_10.jpg" alt="Slide 10" width="850" />

### Slide 11
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_11.jpg" alt="Slide 11" width="850" />

### Slide 12
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_12.jpg" alt="Slide 12" width="850" />

### Slide 13
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_13.jpg" alt="Slide 13" width="850" />

### Slide 14
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_14.jpg" alt="Slide 14" width="850" />

### Slide 15
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_15.jpg" alt="Slide 15" width="850" />

### Slide 16
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_16.jpg" alt="Slide 16" width="850" />

### Slide 17
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_17.jpg" alt="Slide 17" width="850" />

### Slide 18
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_18.jpg" alt="Slide 18" width="850" />

### Slide 19
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_19.jpg" alt="Slide 19" width="850" />

### Slide 20
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_20.jpg" alt="Slide 20" width="850" />

### Slide 21
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_21.jpg" alt="Slide 21" width="850" />

### Slide 22
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_22.jpg" alt="Slide 22" width="850" />

### Slide 23
<img src="Docs/Presentation/G7%20TyrNav%20Presentation%20File%20%28pdf%29_Page_23.jpg" alt="Slide 23" width="850" />

</div>

---

## 📑 Official Project Proposal

Below is the complete **13-page Project Proposal** submitted for the **2024 e-ICON World Contest**.

> 📄 **Download PDF:** [G7 TyrNav PROJECT PROPOSAL.docx.pdf](Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx.pdf)

<div align="center">

### Page 01
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_01.jpg" alt="Proposal Page 01" width="850" />

### Page 02
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_02.jpg" alt="Proposal Page 02" width="850" />

### Page 03
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_03.jpg" alt="Proposal Page 03" width="850" />

### Page 04
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_04.jpg" alt="Proposal Page 04" width="850" />

### Page 05
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_05.jpg" alt="Proposal Page 05" width="850" />

### Page 06
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_06.jpg" alt="Proposal Page 06" width="850" />

### Page 07
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_07.jpg" alt="Proposal Page 07" width="850" />

### Page 08
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_08.jpg" alt="Proposal Page 08" width="850" />

### Page 09
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_09.jpg" alt="Proposal Page 09" width="850" />

### Page 10
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_10.jpg" alt="Proposal Page 10" width="850" />

### Page 11
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_11.jpg" alt="Proposal Page 11" width="850" />

### Page 12
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_12.jpg" alt="Proposal Page 12" width="850" />

### Page 13
<img src="Docs/Proposal/G7%20TyrNav%20PROJECT%20PROPOSAL.docx_Page_13.jpg" alt="Proposal Page 13" width="850" />

</div>

---

## 🛠 Tech Stack & Architecture

- **Application Framework:** [React Native](https://reactnative.dev/) `0.74.5`
- **Platform & Tooling:** [Expo](https://expo.dev/) SDK `51.0.39`
- **Routing:** [Expo Router](https://docs.expo.dev/router/introduction/) `v3.5.24` (File-based navigation)
- **Styling:** [NativeWind](https://www.nativewind.dev/) `v2` (Tailwind CSS for React Native)
- **Backend & Authentication:** [Appwrite](https://appwrite.io/) Cloud SDK (`react-native-appwrite`)
- **Animations:** [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/) `~3.10.1` & [Lottie](https://airbnb.io/lottie/)
- **Typography:** Apple San Francisco Pro (SF Pro Display & Text variable cuts)

---

## 📁 Project Structure

```text
├── app/                        # Expo Router file-based screens and routes
│   ├── (auth)/                 # Authentication screens (Sign In, Sign Up)
│   ├── (tabs)/                 # Main tab navigation
│   │   ├── home.jsx            # Home dashboard
│   │   ├── directory.jsx       # Startup & business directory
│   │   ├── learn.jsx           # Learning modules hub
│   │   ├── fund.jsx            # Funding opportunities & guides
│   │   └── profile.jsx         # User profile & account management
│   ├── course/                 # Course & module views
│   ├── data/                   # Onboarding, course, and quiz datasets
│   ├── directory/              # Business registration & management screens
│   ├── Quiz.js                 # Quiz assessment screen
│   ├── _layout.jsx             # Root layout with custom font loading
│   └── index.jsx               # Entry onboarding flow
├── assets/                     # Fonts, icons, images, and Lottie animations
├── components/                 # Reusable UI components (buttons, cards, headers)
├── constants/                  # Theme colors, icons, and static assets
├── context/                    # Global state & Appwrite auth provider
├── Docs/                       # Presentation slides & proposal documents
│   ├── Presentation/           # Slides (PDF & individual JPG pages)
│   └── Proposal/               # Proposal document (PDF & individual JPG pages)
├── lib/                        # Appwrite client configuration & API helpers
├── app.json                    # Expo project configuration
├── babel.config.js             # Babel compiler presets & plugins
├── package.json                # Project dependencies and npm scripts
└── tailwind.config.js          # Tailwind CSS theme & color palette
```

---

## 🏆 Team & Acknowledgements

### Team G7 — TýrNav

| Member | Role | High School | Country |
| :--- | :--- | :--- | :--- |
| **Muhtasim Zaman Mahim** | Team Lead & App Developer | Dhaka Residential Model College | Bangladesh |
| **Nazmus Sakib Mouin** | App Developer | Dhaka Residential Model College | Bangladesh |
| **Awsaf Onom** | Post Design | Legends International School | Bangladesh |
| **Chimin Choi** | Documentation & Planning | Chungnam Samsung Academy | South Korea |
| **Huiyoung Jeong** | UI/UX Designer | Chungnam Samsung Academy | South Korea |

- **Organizer:** Ministry of Education of the Republic of Korea & Korea Education Frontier Association (KEFA)
- **Contest:** The 14th e-ICON World Contest (2024)
- **Award:** 🏆 **1st Prize — Minister of Education Award (교육부 장관상)**
- **United Nations SDG:** Goal #8 — Decent Work and Economic Growth
