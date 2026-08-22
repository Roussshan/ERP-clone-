# AccSoft 2.0 — College ERP Clone
 
A front-end clone of my college's ERP (AccSoft) system, built to recreate the login, dashboard, fee, and result modules using plain HTML, CSS, and JavaScript.
 
> ⚠️ This is a personal/educational project made for practice purposes. It is **not affiliated with or endorsed by** the original ERP provider or my college, and it is not intended for production or real academic use.
 
## 📖 About
 
This project recreates the look and feel of a typical college ERP portal — the kind students use to log in, check attendance, view fee status, and see exam results. It was built to practice front-end development (HTML/CSS/JS) by rebuilding a real-world, multi-page interface from scratch.
 
## ✨ Features
 
- 🔐 Login page with a Parent/Student toggle and an "Online Test Portal" switch
- 🏠 Home/dashboard page after login
- 💰 Fee details page
- 📄 Result page
- 🗂️ Records page
- 🎨 Custom styling built with plain CSS (no frameworks)

## 🛠️ Tech Stack
 
- **HTML5** — page structure
- **CSS3** — styling and layout
- **JavaScript (Vanilla)** — login validation and page interactions
No backend, database, or build tools are used — this is a static, front-end-only clone.

## 📂 Project Structure

```
ERP-clone-/
├── index.html      # Login page
├── home.html        # Dashboard / home page
├── fee.html          # Fee details page
├── result.html      # Result page
├── 0record.html    # Records page
├── NIU_Logo.png                  # College logo asset
├── Logo-login-window.png   # Login window logo asset
└── *.png / *.jpg                    # Other image assets/screenshots
```
 
## 🚀 Getting Started
 
Since this is a static site with no dependencies, you can run it locally in seconds.
 
1. **Clone the repository**
```bash
   git clone https://github.com/Roussshan/ERP-clone-.git
   cd ERP-clone-
```

2. **Open it in a browser**
   Simply open `index.html` in your browser, or serve it locally:
```bash
   # Using Python
   python -m http.server 8000
```
   Then visit `http://localhost:8000` in your browser.

 3. **Login**
   Use the credentials configured in `index.html` to log in and navigate through the dashboard, fee, and result pages.


## 📸 Screenshots
 
*(Add screenshots of the login page, dashboard, fee page, and result page here to give visitors a preview.)*
 
## ⚠️ Disclaimer
 
- This project was created purely for **learning and portfolio purposes**.
- Login credentials are currently **hardcoded in the source code** for demo purposes — this is not secure and should never be done in a real/production application. Consider moving credentials out of the codebase (e.g., into environment variables or a backend) before sharing this project publicly.
- All logos and branding used belong to their respective owners and are included only for visual reference.

## 🗺️ Roadmap / Ideas for Improvement
 
- [ ] Move login validation to a backend with proper authentication
- [ ] Add responsive design for mobile devices
- [ ] Add more ERP modules (attendance, timetable, notices)
- [ ] Replace hardcoded credentials with a secure auth flow
## 👤 Author
 
**Roussshan**
GitHub: [@Roussshan](https://github.com/Roussshan)
