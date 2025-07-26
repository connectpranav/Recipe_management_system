# Recipe_Management_System

A feature-rich and well-structured **Flutter recipe app**. The app allows users to explore recipes, mark favorites, and personalize the experience with theme and language preferences.



## 🚀 Features

- 🔐 **Secure Login** with `flutter_secure_storage`
- 📄 **Home Page** listing SQLite-stored recipes
- ❤️ **Favorites Page** to view saved recipes
- ⚙️ **Settings Page** for:
    - Theme Switching (Light/Dark/System)
    - Language Selection (English, Hindi, Marathi)
    - About, Notifications & Help
    - Logout functionality
- 📱 **Multilingual Support** with `.arb` files and localization



## 🧭 Navigation Pages

- `about_page.dart`
- `favorite_page.dart`
- `home_page.dart`
- `login_page.dart`
- `main_screen.dart`
- `recipe_card.dart`
- `recipe_detail_page.dart`
- `settings_page.dart`



## 🌍 Localization (l10n)

Localization files located in `lib/l10n/`:
- `app_en.arb` (English)
- `app_hi.arb` (Hindi)
- `app_mr.arb` (Marathi)
- `app_localizations.dart`



## 📦 Folder Structure

```
lib/
├── database/
│   └── database_helper.dart
├── l10n/
│   ├── app_en.arb
│   ├── app_hi.arb
│   ├── app_mr.arb
│   └── app_localizations.dart
├── models/
│   ├── recipe.dart
│   └── sample_recipes.dart
├── pages/
│   ├── about_page.dart
│   ├── favorite_page.dart
│   ├── home_page.dart
│   ├── login_page.dart
│   ├── main_screen.dart
│   ├── recipe_card.dart
│   ├── recipe_detail_page.dart
│   └── settings_page.dart
├── providers/
│   └── app_state.dart
├── utils/
│   ├── shared_preferences_helper.dart
│   └── sharedpreferences.dart
├── widgets/
│   ├── category_slider.dart
│   └── recipe_card.dart
├── main.dart
├── scaling_helper.dart
└── secure_storage.dart
```



## 🛠 Tech Stack

- **Flutter** (UI Framework)
- **Provider** (State Management)
- **SQLite** (Recipe Database)
- **Shared Preferences** (Lightweight Storage)
- **flutter_secure_storage** (For secure login credentials)
- **Localization** with `.arb` files

  



## ▶️ How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/flutter-recipe-app.git
   cd flutter-recipe-app
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the app**:
   ```bash
   flutter run
   ```



## 🧠 Contribution

Want to improve the app? Feel free to fork, contribute and submit PRs!



## 👨‍💻 Author

Developed by **[Pranav Gajanan Dighade]**
              Email- dighadepranav@gmil.com
             **[Ajay Bhanwarlal Chaudhary]**
              Email- choudharyajay6969@gmail.com
             **[Shivam Gajanan Burkul]**
             Email- shivamburkul1179@gmail.com
             **[Faiz Ishaque Chauhan]**
             Email- faizchauhan18@gmail.com



## 📷 Screenshots
Login Page
![WhatsApp Image 2025-07-26 at 22 00 37_db56ff71](https://github.com/user-attachments/assets/35d79bc8-8e0c-4d6b-b5f2-d6d773facbf6)
Recipes page 1
![WhatsApp Image 2025-07-26 at 22 00 38_eef9b712](https://github.com/user-attachments/assets/b732d9e9-66d2-4189-b443-3b9c177a59f7)
Recipe page 2
![WhatsApp Image 2025-07-26 at 22 00 39_7a3e1fb1](https://github.com/user-attachments/assets/82d6974f-7394-4ad2-8855-c363469f5d21)
Favorite page
![WhatsApp Image 2025-07-26 at 22 00 39_65d32b76](https://github.com/user-attachments/assets/529aa314-626e-42e9-bead-e76ad1855cf4)
Setting page
![WhatsApp Image 2025-07-26 at 22 00 39_65446a26](https://github.com/user-attachments/assets/f55702b6-8fe6-4451-b76f-0b51878cd5b8)


