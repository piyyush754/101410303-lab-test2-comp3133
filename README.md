# 🚀 COMP 3133 | Lab Test 2 – SpaceX Mission Explorer

Welcome to **SpaceX Mission Explorer**, a modern Angular application built for the COMP 3133 Lab Test. This app fetches real-time SpaceX launch data from the public [SpaceX API](https://api.spacexdata.com/) and lets users explore, filter, and view detailed mission information with a clean, responsive, and fully themed UI.

---

## ✨ Features

- 🔍 **Filter missions** by:
  - Launch Year
  - Launch Success (Success/Failed)
  - Landing Success (Success/Failed)

- 📦 **Fetches real-time data** from SpaceX REST API (`https://api.spacexdata.com/v3/launches`)
- 🎨 **Dark UI with gradient themes** across all components (cards, filters, buttons)
- 📱 **Responsive design** for all screen sizes
- 🔗 View full **mission details**: rocket info, launch success, related articles, videos, and Wikipedia

---

## 🛠️ Tech Stack

- **Framework:** Angular 17
- **UI Library:** Angular Material
- **Language:** TypeScript
- **Styling:** SCSS (custom theming + responsive layout)
- **Deployment:** Vercel (link below)

---

## 🔧 How to Run the App Locally

> **Prerequisites:**
> - Node.js & npm installed
> - Angular CLI installed globally: `npm install -g @angular/cli`

### 1. Clone the repository

```bash
git clone https://github.com/helly373/101414910-lab-test2-comp3133.git
cd SpaceX-Angular-App
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the app

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.



## Concepts Covered

- Angular components, services, and routing
- Angular Material UI and theming
- Reactive API data fetching via HttpClient
- Dynamic routing with :id
- Custom CSS and SCSS theming with gradients
- Responsive layout with Flexbox

## Author Name: Helly Chauhan
