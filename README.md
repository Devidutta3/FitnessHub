# 🏋️‍♂️ Fitness Measurement Hub  
A modern, responsive **Fitness Measurement Web App** built using **pure HTML, CSS, and JavaScript** — NO React, NO frameworks.  
Includes a clean UI, local user login system, fitness calculators, body-fat estimation, TDEE, BMI tracking, and a progress chart saved per user.

---

## 🌟 Features

### 🔐 **Login System (Client-Side)**
- Register/Login using a simple username & password  
- Passwords are hashed using **SHA-256** before storage  
- Users stored in browser **localStorage**  
- Each user gets their own profile and fitness progress data

---

### 📏 **Fitness Measurements**
- BMI Calculation  
- BMR (Mifflin–St Jeor formula)  
- Body Fat % (U.S. Navy Method)  
- TDEE (Daily Calorie Maintenance)  
- Macro suggestion (Proteins, Carbs, Fats)

---

### 📊 **Progress Tracker**
- Save entries (Date, Weight, BMI)  
- Visual chart using Canvas API  
- Remove entries  
- Copy profile + entries as JSON  
- Clear all data button  

---

## 🧮 **Tools Used**
- **HTML** – Structure  
- **CSS** – Styling + layout  
- **Vanilla JavaScript** – Logic, authentication, calculations  
- **Canvas API** – Chart rendering  
- **LocalStorage** – User profiles and progress saving  

---

## 🚀 Deployment Guide

### Option 1 — Deploy on **GitHub Pages**
1. Push the project folder to GitHub  
2. Go to **Settings → Pages**  
3. Under “Build and deployment” set:  
   - Branch: `main`  
   - Folder: `/ (root)`  
4. Save → Wait 30–60 seconds  
5. Your site is live at:  
