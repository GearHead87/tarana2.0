# 📂 Project Folder Structure

## 🔄 **Flow of Folder Structure**
```
Routes > Pages > Containers > Views > Components
```

## 📌 **Folder Breakdown**

### 🚀 Routes
- Handles navigation and routing across the app.
- Defines paths for different pages.

### 📄 Pages
- Contains all the main pages of the application.
- Acts as a bridge between `Routes` and `Containers`.

### 📦 Containers
- Handles all the logic for each page (API calls, state management, event handlers).
- Example: `DashboardContainer` manages logic for the dashboard.

### 🎨 Views
- Handles UI rendering with no business logic.
- Displays buttons, forms, and other visual elements.
- Example: `DashboardView` presents the dashboard layout.

### 🛠 Components
#### 📌 Base
- Simple reusable components like `FormButton`, `FormInput`, `Image`, `Loader`, `Typography`, etc.

#### 🎯 Custom
- Components made for specific tasks that won’t be used elsewhere.

#### 🔄 Shared
- Common UI elements like `AppStyles`, `Forms`, `Header`, `Layout`, etc., used in multiple places.

### 📚 **Lib Folder**
- `common` – Shared utilities and helpers.
- `config` – Stores app-wide configurations.
- `constants` – Holds constant values used throughout the app.
- `restAPI` – API request handlers.
- `utils` – Utility functions.

### 🌍 **Contexts**
- Provides global state via React Context API.
- Examples: `AuthContext`, `ThemeContext`.

### 🏪 **Store**
- Manages state with libraries like Redux or Zustand.

## 📝 **README.md with Flowchart**
```md
# 📂 Project Structure

## 🔄 Flow of Folder Structure
```
Routes > Pages > Containers > Views > Components
```

## 📌 Overview
This project is structured to keep logic, UI, and reusable components separate for better maintainability and scalability.

### 📍 Folder Breakdown
- **Routes** – Manages navigation.
- **Pages** – Contains all page files.
- **Containers** – Handles logic for each page.
- **Views** – Manages UI rendering.
- **Components** – Holds reusable UI elements.
- **Lib** – Stores shared utilities, config, constants, and API handlers.
- **Contexts** – Provides global state management.
- **Store** – Manages state with Redux/Zustand.

### 📊 Flowchart Representation
```
Routes > Pages > Containers > Views > Components
```

## 🎯 Additional Notes
- The `lib` folder organizes shared utilities and API-related logic.
- The `contexts` folder manages React Context API for global state.
- The `store` folder is dedicated to state management using Redux or Zustand.
- The `components` folder is split into `base`, `custom`, and `shared` for better organization and reusability.

By following this structure, we ensure better code separation, maintainability, and scalability. 🚀

