# 📸 FlashMedia – ASP.NET Core Razor App

**FlashMedia** is a modern ASP.NET Core web application for user authentication and media interaction. It includes a user-friendly interface for registration, login, and account management using Razor Pages and Identity.

## 🔐 Features

- 🧑‍💻 User registration, login, logout
- 📨 Password reset & confirmation via Identity
- 👤 Profile management: change email, password, delete account
- 📂 Modular architecture with Razor Pages & Areas

## 🛠️ Tech Stack

- ASP.NET Core 6 / Razor Pages
- Entity Framework Core
- Identity (Authentication)
- C#
- SQL Server (via `appsettings.json`)

## 🚀 How to Run

1. Clone the repo
2. Open in **Visual Studio 2022+**
3. Restore NuGet packages
4. Update DB connection string in `appsettings.json`
5. Run the project (`Ctrl + F5`)

## 📁 Project Structure

```
FlashMedia/
├── Areas/Identity/         # Identity scaffolded pages
├── Pages/                  # Razor pages for UI
├── wwwroot/                # Static files (CSS, JS, etc.)
├── Program.cs              # App entry point
├── appsettings.json        # Configuration
├── FlashMedia.sln          # Solution file
```

## 📌 Notes

- All identity-related logic is located under `Areas/Identity/Pages/Account`
- Can be extended to support image uploading or social features
- Built as a modular, extendable ASP.NET Core application

---

*Clean, scalable, and authentication-ready — FlashMedia is a great base for any media-based ASP.NET Core web app.*

---

### 🤝 Collaboration  
This project was developed in collaboration with [Maria Adina](https://github.com/mariaxadina) and [Alexandru Gabriel]().



