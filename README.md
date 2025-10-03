# Employee Management Web App

This is a simple **Employee Management** web application built with **ReactJS**.  
The app demonstrates how to use **React state** for dynamic UI updates without reloading the page. It uses **static employee data** and provides department-based filtering. Styling is done with **CSS** and **Bootstrap**, while logic is handled in **JavaScript (ES6)**.

---

## 🚀 Features
- 📌 Display a list of employees with details (ID, Name, Age, Department, Designation, Salary, Location).  
- 📌 Filter employees by department (All, HR, IT, Finance, Marketing, Manager).  
- 📌 Uses **React state** to update UI instantly without page reloads.  
- 📌 Responsive design using Bootstrap grid and custom CSS.  
- 📌 Pill-shaped, responsive buttons with media queries for smaller screens.  

---

## 🛠️ Tech Stack
- **ReactJS** (class components with state)
- **JavaScript (ES6+)**
- **Bootstrap 5**
- **CSS3**

---

## 📂 Project Structure
employee-management/
├─ public/
│ └─ index.html # Base HTML file (Bootstrap CDN + React bundle)
├─ src/
│ ├─ components/
│ │ └─ Employee.jsx # Employee card component
│ ├─ data/
│ │ └─ EmployeeData.js # Static employee arrays (employees, HR, IT, etc.)
│ ├─ App.jsx # Main app component (buttons + rendering employees)
│ ├─ index.js # React entry point
│ └─ styles.css # Custom styles & media queries
├─ package.json
└─ README.md

yaml
Copy code

---

## ⚡ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14+ recommended)
- npm or yarn

### Installation
```bash
# Clone the repo
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# Install dependencies
npm install
Run Development Server
bash
Copy code
npm run dev   # (if using Vite)
# or
npm start     # (if using Create React App)
Build for Production
bash
Copy code
npm run build
📱 Responsiveness
Buttons are pill-shaped and responsive.

Media queries shrink button size on smaller screens (<576px, <400px).

On very small devices, a single toggle button can be used to show/hide department buttons.

🐞 Common Issues & Fixes
✅ Use this.setState() (correct case) instead of this.setstate.

✅ Add key prop when rendering lists with .map().

✅ Avoid duplicate id attributes; use className instead.

✅ Ensure Bootstrap JS is loaded (for Collapse functionality).

📤 Deployment
You can deploy this app easily on:

GitHub Pages

Netlify

Vercel

Any static hosting service

📜 License
This project is open-source. You can use and modify it for learning or personal projects.

✍️ Author
Developed as a React learning project.

yaml
Copy code

---

👉 This `README.md` is formatted for GitHub, with emojis, sections, and code blocks.  
Do you want me to also include **screenshots placeholders** (like `![App Screenshot]
