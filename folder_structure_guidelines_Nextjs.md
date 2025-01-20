# 📂 Next.js 14 (App Router) Project Folder Structure

## 🔄 **Flow of Folder Structure**
```
app > containers > views > components > lib > contexts > store
```

## 📌 **Folder Breakdown**

### 🚀 app (Replaces Routes & Pages)
- The main folder for Next.js 14 App Router.
- Contains all route segments as folders (`app/dashboard`, `app/profile`, etc.).
- Each route segment can have `page.tsx` (renders UI), `layout.tsx` (shared layouts), and `loading.tsx` (skeleton loaders).

### 📦 Containers
- Handles logic for each route (API calls, state management, event handlers).
- Example: `DashboardContainer.tsx` manages logic for the dashboard.

### 🎨 Views
- Responsible for UI presentation without logic.
- Example: `DashboardView.tsx` renders buttons, forms, and visual elements.

### 🛠 Components
#### 📌 Base
- Simple, reusable components like `FormButton`, `FormInput`, `Image`, `Loader`, `Typography`, etc.

#### 🎯 Custom
- Components built for specific tasks that aren’t used elsewhere.

#### 🔄 Shared
- Common UI elements like `AppStyles`, `Forms`, `Header`, `Layout`, etc., used across multiple areas.

### 📚 **Lib Folder**
- `common` – Shared utilities and helpers.
- `config` – Stores app-wide configurations.
- `constants` – Holds constant values used throughout the app.
- `restAPI` – API request handlers using Next.js server actions.
- `utils` – Utility functions.

### 🌍 **Contexts**
- Provides global state using React Context API.
- Examples: `AuthContext`, `ThemeContext`.

### 🏪 **Store**
- Manages state using Redux, Zustand, or React Server Actions.

## 📝 **README.md with Flowchart**
```md
# 📂 Next.js 14 (App Router) Project Structure

## 🔄 Flow of Folder Structure
```
app > containers > views > components > lib > contexts > store
```

## 📌 Overview
This project follows Next.js 14's App Router structure, ensuring better organization, scalability, and maintainability.

### 📍 Folder Breakdown
- **app** – Manages routing, layouts, and pages.
- **containers** – Handles logic for each page.
- **views** – Manages UI rendering.
- **components** – Holds reusable UI elements.
- **lib** – Stores shared utilities, config, constants, and API handlers.
- **contexts** – Provides global state management.
- **store** – Manages state using Redux/Zustand.

### 📊 Flowchart Representation
```
app > containers > views > components > lib > contexts > store
```

## 🎯 Additional Notes
- The `app` folder is the root for routing in Next.js 14.
- The `lib` folder organizes utilities and API-related logic.
- The `contexts` folder manages React Context API for global state.
- The `store` folder is used for managing state with Redux, Zustand, or React Server Actions.
- The `components` folder is split into `base`, `custom`, and `shared` for better structure.

This structure optimizes development for Next.js 14 by keeping logic and UI separate, ensuring cleaner and more scalable code. 🚀

