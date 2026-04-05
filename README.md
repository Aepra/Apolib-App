# Apolib: Personal Medication Intelligence Assistant

![logoApolib](https://github.com/user-attachments/assets/508e3fae-f970-4ebc-8ee3-925dda1b5b0c)

[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen.svg)](https://developer.android.com)
[![Language](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.oracle.com/java/)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-yellow.svg)](https://firebase.google.com/)

Apolib is a sophisticated Android-based pharmaceutical information assistant designed for healthcare professionals, medical students, and health-conscious individuals. It simplifies medical data complexity by providing structured, real-time drug information through a modern and responsive mobile interface.

---

## 🚀 Core Value Proposition
* **Comprehensive Data Source:** Instant access to an extensive and continuously updated drug database.
* **High-Performance Search:** Optimized search engine supporting generic names, brand names, and compositions with real-time filtering.
* **Offline Persistence:** Ability to save medications to a local favorites list for critical access without an internet connection.
* **Optimized Performance:** All heavy database and API operations are executed on background threads, ensuring a lag-free UI experience.

---

## 📸 App Interface
<p align="center">
  <img src="[https://github.com/user-attachments/assets/e3e9afb2-facd-4b68-8581-4112171e5992](https://github.com/user-attachments/assets/e3e9afb2-facd-4b68-8581-4112171e5992)" width="160"/>
  <img src="[https://github.com/user-attachments/assets/14456267-6dd8-4afd-825b-d4f9e26ccacc](https://github.com/user-attachments/assets/14456267-6dd8-4afd-825b-d4f9e26ccacc)" width="160"/>
  <img src="[https://github.com/user-attachments/assets/0835617c-e3ee-4d27-ae51-83591c558b06](https://github.com/user-attachments/assets/0835617c-e3ee-4d27-ae51-83591c558b06)" width="160"/>
  <img src="[https://github.com/user-attachments/assets/6361a231-2b33-466c-81e7-f6789a9916c1](https://github.com/user-attachments/assets/6361a231-2b33-466c-81e7-f6789a9916c1)" width="160"/>
  <img src="[https://github.com/user-attachments/assets/e41f85ec-2965-4246-b3a5-89ae04b6aa57](https://github.com/user-attachments/assets/e41f85ec-2965-4246-b3a5-89ae04b6aa57)" width="160"/>
  <img src="[https://github.com/user-attachments/assets/8a186e96-bcc5-42a0-a22a-318ca612aa87](https://github.com/user-attachments/assets/8a186e96-bcc5-42a0-a22a-318ca612aa87)" width="160"/>
</p>

---

## 🛠 Technical Stack
Apolib is built with a focus on modern Android development standards and robust architecture:

* **Architecture:** ViewPager2 & Fragment-based navigation with Material Design 3.
* **Networking:** `Retrofit 2` & `OkHttp 3` for robust integration with OpenFDA API.
* **Asynchronous Processing:** Multi-threading managed via `ExecutorService` and `Handler` for UI synchronization.
* **Local Storage:** `SQLite` handled via custom `FavoriteManager` for reliable offline data persistence.
* **Cloud Backend:** `Firebase Firestore` for real-time user profile synchronization.
* **Authentication:** Secure `Firebase Authentication` (Google Sign-In & Anonymous).
* **Data Parsing:** `Gson` for efficient JSON serialization/deserialization.

---

## ⚙️ Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Aepra/Apolib.git
   ```
2. **Firebase Setup (Required):**
   - Create a new project in the [Firebase Console](https://console.firebase.google.com/).
   - Download `google-services.json` and place it in the `app/` directory.
   - Enable **Firestore** and **Authentication** (Anonymous & Google provider).
3. **Build:** Open in Android Studio and sync with Gradle files.

---

## 🤝 Contribution
Contributions are welcome. We follow **Semantic Commits** to maintain a clean and professional project history.

**Format:** `<type>[optional scope]: <description>`  
*Example:* `feat(auth): add Google Sign-In support`

---

## 📧 Contact & Support
- **Lead Developer:** Abel Eka Putra (**Aepra**)
- **GitHub:** [@Aepra](https://github.com/Aepra)
- **Email:** [abelekaputra05@gmail.com](mailto:abelekaputra05@gmail.com)

---
*Apolib - Empowering medical knowledge through technology.*