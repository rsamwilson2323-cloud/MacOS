# 🍎 Web Simulation of macOS

Web Simulation of macOS is a fully interactive **macOS-style web simulator** built using **React ⚛️, Vite ⚡, Tailwind CSS 🎨, Framer Motion 🎬, and modern React UI libraries**.

The project recreates the macOS experience directly inside a web browser with a **boot sequence, lock screen, desktop environment, draggable windows, Dock, Finder, Safari, Terminal, Photos, Notes, Music, and System Settings**.

---

# ✨ Features

🔐 **Boot & Lock Screen**

* macOS-style power-on animation

* Interactive lock screen with live clock

* Swipe-to-unlock experience

* Automatic lock after inactivity

👤 **Editable User Profile**

* Upload a custom profile picture

* Change the displayed username

* User information is persisted using **localStorage**

🖥 **Desktop Environment**

* Fully interactive macOS-style desktop

* Draggable and resizable application windows

* Right-click context menu

* Create desktop folders and files

* macOS-inspired visual effects

🚀 **Interactive Dock**

* Animated Dock magnification on hover

* Application open/minimize indicators

* Launch bounce animations

* macOS-style application icons

🍎 **Top Menu Bar**

* Dynamic application title

* Apple menu

* Lock, sleep and shutdown options

* Dropdown menus

* Live system clock

📁 **Finder**

* Simulated macOS file system

* Desktop, Downloads, Documents and Pictures folders

* Grid and list view

* File management interface

🌐 **Safari**

* Built-in browser simulation

* Navigation controls

* macOS-style Safari interface

💻 **Terminal**

* Functional terminal emulator

* macOS-inspired terminal interface

🖼 **Photos / Gallery**

* Image gallery

* Wallpaper management

* Set custom desktop wallpapers

📝 **Notes**

* Apple Notes-style interface

* iCloud-style folders

* Tags and search

* Full note editor

* Automatic localStorage saving

🎵 **Music / Spotify**

* Integrated music-player interface

* Spotify-inspired experience

⚙️ **System Settings**

* macOS System Settings interface

* About This Mac section

* System configuration interface

🎨 **Wallpaper Customization**

* Change desktop wallpaper

* Change lock screen wallpaper

* Select wallpapers through the Gallery application

---

# 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| ⚛️ React 19 | UI framework |
| ⚡ Vite 7 | Build tool & development server |
| 🎨 Tailwind CSS 4 | Styling |
| 🎬 Framer Motion | UI animations |
| ✨ GSAP | Advanced animations |
| 🧩 Radix UI | Accessible UI components |
| 🪟 React RND | Draggable and resizable windows |
| 🌊 React Spring | Spring-based animations |
| 🔷 Lucide React | Icons |

The technology stack and project architecture are based on the uploaded project README.

---

# 📂 Project Structure

```text
MacOS-Web-Simulator
│
├── src/
│   │
│   ├── App.jsx
│   │
│   ├── app/
│   │   ├── Finder.jsx
│   │   ├── Safari.jsx
│   │   ├── Terminal.jsx
│   │   ├── Spotify.jsx
│   │   ├── Gallary.jsx
│   │   ├── Settings.jsx
│   │   ├── Trash.jsx
│   │   └── Blogs/
│   │       └── BlogsSection.jsx
│   │
│   ├── components/
│   │   ├── AppWindow.jsx
│   │   ├── Dock.jsx
│   │   ├── TopBar.jsx
│   │   └── ContextMenu.jsx
│   │
│   ├── layouts/
│   │   ├── DesktopWindow.jsx
│   │   ├── LockScreen.jsx
│   │   └── PowerScreen.jsx
│   │
│   └── store/
│       └── Appstore.js
│
├── package.json
├── README.md
└── LICENSE
```

The structure above follows the application's documented React components, layouts, apps, and window-management store.

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/LikhithSP/MacOS-Web-Simulator.git
cd MacOS-Web-Simulator
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

# 📦 Requirements

Before running the project, make sure you have:

```text
Node.js 18+
npm
```

You can also use **Yarn** as an alternative package manager.

---

# ▶️ Usage

Start the development server using:

```bash
npm run dev
```

The application will normally be available at:

```text
http://localhost:5173
```

Open the address in your browser to launch the macOS simulator.

---

# 🧠 How It Works

🍎 **Boot System**

The application begins with a simulated macOS power-on and boot sequence before transitioning to the lock screen.

🔐 **Lock Screen**

The lock screen provides a macOS-inspired login experience with a live clock, customizable profile and unlock interaction.

🖥 **Desktop Environment**

After unlocking, users enter an interactive desktop containing application icons, folders, windows and the Dock.

🪟 **Window Management**

Applications run inside draggable and resizable windows, allowing multiple simulated applications to operate within the desktop environment.

🚀 **Dock System**

The Dock provides quick access to applications with hover magnification, launch animations and window state indicators.

💾 **Local Storage**

User profile information and application data such as Notes are persisted using browser **localStorage**.

---

# 🖥 Included Applications

```text
📁 Finder
🌐 Safari
💻 Terminal
🎵 Spotify / Music
🖼 Photos / Gallery
📝 Notes
⚙️ Settings
🗑 Trash
```

---

# 🎨 Customization

The simulator supports several personalization features:

* 👤 Custom profile picture
* ✏️ Editable username
* 🖼 Desktop wallpaper
* 🔐 Lock screen wallpaper
* 📁 Desktop files and folders
* 📝 Persistent Notes

---

# 🚀 Future Improvements

🔊 Add system sound effects

🌐 Improve Safari browsing capabilities

📂 Expand the simulated file system

🧠 Add AI-powered macOS assistant

📱 Improve mobile and tablet responsiveness

🖥 Add multiple desktop spaces

🔔 Add macOS-style notification center

🎛 Add Control Center

☁️ Add cloud-based file synchronization

🎮 Add more interactive applications

---

# 🤝 Contributing

Contributions are welcome! 🚀

### 1️⃣ Fork the Repository

### 2️⃣ Create a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 3️⃣ Commit Your Changes

```bash
git commit -m "Add: your-feature-name"
```

### 4️⃣ Push the Branch

```bash
git push origin feature/your-feature-name
```

### 5️⃣ Open a Pull Request

---

# ⚠️ Disclaimer

This project is an **educational and experimental web simulation** inspired by the macOS desktop experience.

It is **not an official Apple product** and does not provide the actual macOS operating system.

---

# 👨‍💻 Author

**Sam Wilson**

🌐 GitHub  
https://github.com/rsamwilson2323-cloud

💼 LinkedIn  
https://www.linkedin.com/in/sam-wilson-14b554385

---

# 📜 License

This project is licensed under the **MIT License**.