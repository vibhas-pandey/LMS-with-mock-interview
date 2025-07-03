# 🎓 Academic Harbor

**Academic Harbor** is an AI-powered web platform designed to assist students and professionals with course learning, PDF viewing, face recognition tools, and integrated authentication features. This project is built using React.js with Vite, enhanced with powerful tools like Firebase, Face-API.js, and EmailJS.

---

## 🚀 Features

- 🔐 **User Authentication** with Auth0
- 📧 **Email Integration** via EmailJS
- 📄 **PDF Viewer** with navigation and toolbar using React PDF Viewer
- 🧠 **AI & Face Recognition** using Face API
- 🔥 **Firebase** support for storage or real-time database
- 💬 **Chatbot UI Components**
- 🎓 **Course thumbnails & learning UI**
- 🎨 **Responsive Design** with Bootstrap
- 📂 **Modular React Component Architecture**

---

## 🛠️ Tech Stack

| Technology       | Description                        |
|------------------|------------------------------------|
| React.js         | Frontend library                   |
| Vite             | Lightning-fast dev/build tool      |
| Auth0            | Authentication provider            |
| Firebase         | Cloud backend (Auth, DB, Hosting)  |
| EmailJS          | Email API for contact features     |
| Face-api.js      | Face recognition in-browser        |
| React Hook Form  | Form validation                    |
| Bootstrap        | UI styling                         |
| PDF Viewer       | `@react-pdf-viewer` library        |

---

## 📁 Folder Structure
academic-harbor/
│
├── public/ # Static assets (images, icons)
├── src/
│ ├── assets/ # Images & media
│ ├── components/ # React reusable components
│ ├── pages/ # Different page layouts
│ ├── services/ # API & auth integrations
│ ├── utils/ # Utility functions
│ ├── App.jsx # Root component
│ └── main.jsx # Vite entry file
│
├── index.html # Root HTML template
├── package.json # Project metadata and scripts
├── vite.config.js # Vite configuration
└── .eslintrc.cjs # ESLint config


---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/academic-harbor.git
cd academic-harbor

### 2. Install Dependencies
  npm install

### 3. Set up Environment
Create a .env file in the root folder and add your credentials for:
VITE_AUTH0_DOMAIN=your-auth0-domain
VITE_AUTH0_CLIENT_ID=your-client-id
VITE_FIREBASE_API_KEY=your-firebase-key
VITE_FIREBASE_AUTH_DOMAIN=your-firebase-auth
VITE_EMAILJS_SERVICE_ID=your-service-id
VITE_EMAILJS_TEMPLATE_ID=your-template-id
VITE_EMAILJS_PUBLIC_KEY=your-public-key

🔐 Authentication Setup
This app uses Auth0 for login/signup. You must configure the Auth0 dashboard and set allowed callback/logout URLs to:
http://localhost:5173

✉️ EmailJS Setup
1.Sign up at https://www.emailjs.com
2.Create a service and email template
3.Add the template ID and public key to .env

🧠 Face Recognition
Uses face-api.js for:
Face detection
Landmark recognition
Can be extended to proctoring systems or attendance

📚 PDF Viewer
Implemented using:
@react-pdf-viewer/core
Toolbar, navigation, zoom, and custom layout
Used for rendering course materials and documents inside the app.

🧑‍💻 Contributing
We welcome contributions!

1. Fork the repository
2. Create a feature branch: git checkout -b feature-name
3. Commit your changes: git commit -m "Add feature"
4. Push to branch: git push origin feature-name
5.Create a Pull Request

📝 License
This project is licensed under the MIT License. See the LICENSE file for details.
