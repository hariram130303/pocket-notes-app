# Pocket Notes 📝

Pocket Notes is a simple and responsive note-taking web app built with **React**.  
It allows users to create groups, add notes, and organize them effectively.  

---

## 🚀 Features
- Create and manage groups for notes
- Display group icons with the **first two letters** of the group name
- Responsive UI:
  - **Desktop view** with sidebar and notes area
  - **Mobile view** with collapsible sidebar
- Notes stored in **localStorage** for persistence
- End-to-end encrypted messaging simulation UI

---

## 📂 Project Structure
```
pocket-notes-app/
├── build/
├── node_modules/
├── public/
│   ├── Screenshots/
├── src/
│   ├── assets/
│   ├── component/
│   │   ├── ModalWeb/
│   │   ├── NoteAreaWeb/
│   │   └── SidePanelAndMessageAreaWeb/
│   ├── pages/
│   │   └── Home.js
│   ├── App.css
│   ├── App.js
│   ├── index.css
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
├── package-lock.json
└── README.md

```

---

## 🛠️ Tech Stack
- **React 19**
- **React Scripts (CRA)**
- **CSS Modules**
- **LocalStorage** for persistence

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hariram130303/pocket-notes-app.git
   cd pocket-notes-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm start
   ```

4. Build for production:
   ```bash
   npm run build
   ```

---

## 📸 Screenshots
1. Home Page
(https://raw.githubusercontent.com/hariram130303/pocket-notes-app/main/public/screenshots/1.png)

![Notes Page] (https://raw.githubusercontent.com/hariram130303/pocket-notes-app/main/public/screenshots/2.png)

---

## 🌐 Deployment
You can deploy the `build/` folder to:
- **Netlify**
- **Vercel**
- **GitHub Pages**
- **Render**

---

## 🤝 Contributing
1. Fork the repo
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📜 License
This project is licensed under the MIT License.
