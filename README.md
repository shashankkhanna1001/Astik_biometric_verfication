# 🛡️ Astik Biometric Verification System

Astik Biometric Verification is a secure web-based authentication platform that uses fingerprint-based identity verification along with traditional user credentials. Built for modern applications needing robust, scalable, and user-friendly biometric authentication.

## 🚀 Features

- 🔐 **Secure Login & Signup**
- 🖼️ **Profile Picture Upload**
- 📇 **User Info Dashboard** with welcome message
- ✅ **Fingerprint Registration Status Badge**
- 🌐 **Multi-language Support (English & Hindi)**
- 📱 **Mobile-Optimized UI**
- 🧩 **Modular Codebase** for easy extension

## 📸 Screenshots

| Signup Page | Profile Page |
|-------------|--------------|
| ![signup](screenshots/signup.png) | ![profile](screenshots/profile.png) |

## 🧑‍💻 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js / Express (assumed, update if different)
- **Authentication:** Username, Password, Fingerprint
- **Languages:** English, Hindi (i18n ready)

## 📂 Project Structure

Astik_biometric_verfication/
├── public/
│ ├── css/
│ ├── js/
│ └── images/
├── views/
│ └── *.html
├── routes/
│ └── *.js
├── app.js
└── README.md


## 🛠️ Setup Instructions

1. **Clone the repo**

```bash
git clone https://github.com/shashankkhanna1001/Astik_biometric_verfication.git
cd Astik_biometric_verfication

```

Install dependencies

bash
Copy
Edit
npm install
Run the application

bash
Copy
Edit
npm start
Open in Browser

arduino
Copy
Edit
http://localhost:3000
⚠️ Ensure you have a fingerprint device or compatible emulator for full biometric testing.

🌍 Language Support
English (default)

हिंदी (Hindi)

Language is automatically detected or can be switched via the dropdown in the UI.

🔒 Security Notes
Passwords are securely hashed.

Fingerprint data is securely handled.

Sessions/tokens protected against common vulnerabilities (CSRF, XSS, etc.)

✅ To Do
 Add OAuth / Passkey integration

 Deploy to cloud (e.g., Vercel / Heroku / AWS)

 Add unit & integration tests

 Admin dashboard for verification stats

📜 License
MIT License (or specify your own)

🤝 Contributing
Contributions, bug reports, and feature requests are welcome!

Fork the repository

Create your branch: git checkout -b feature-name

Commit your changes: git commit -m 'Add feature'

Push to the branch: git push origin feature-name

Submit a pull request

📧 Contact
Shashank Khanna
📫 Email: shashankkhanna98@gmail.com
🔗 GitHub: @shashankkhanna1001
