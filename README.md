# Hotel Management Dashboard

<!--! its a clone for original TailAdmin created by Musharof Chowdhury https://www.linkedin.com/company/pimjo  -->

A modern, responsive hotel management dashboard built with React, Vite, and Tailwind CSS. This project provides a comprehensive admin interface for managing hotel operations.

## 🚀 Features

- **Modern UI/UX** - Clean and intuitive interface built with Tailwind CSS
- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **Dashboard Analytics** - Visualize key metrics with interactive charts (ApexCharts)
- **Dark Mode** - Toggle between light and dark themes
- **Calendar Integration** - Manage bookings and events with FullCalendar
- **Data Tables** - Advanced tables with sorting, filtering, and pagination
- **File Management** - Drag-and-drop file uploads with React Dropzone
- **Maps Integration** - Interactive world maps with JVectorMap
- **Forms & Validation** - Comprehensive form components with Flatpickr date picker
- **Modular Components** - Reusable UI components for rapid development

## 🛠️ Tech Stack

### Frontend

- **React 19** - Latest version of React
- **Vite 6** - Lightning-fast build tool
- **Tailwind CSS 4** - Utility-first CSS framework
- **React Router 7** - Client-side routing

### UI Components & Libraries

- **ApexCharts** - Modern charting library
- **FullCalendar** - Feature-rich calendar component
- **Swiper** - Modern touch slider
- **React DnD** - Drag and drop functionality
- **Flatpickr** - Lightweight date picker

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18 or higher)
- **npm** (v9 or higher)

## ⚡ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/hotel-management-dashboard.git
cd hotel-management-dashboard
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start development server

```bash
npm run dev
```

The application will open at [http://localhost:5173](http://localhost:5173)

## 📜 Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run ESLint
npm run lint
```

## 📁 Project Structure

```
hotel-management-dashboard/
├── public/              # Static assets
├── src/
│   ├── assets/         # Images, icons, SVGs
│   ├── components/     # Reusable UI components
│   │   ├── Charts/     # Chart components
│   │   ├── Forms/      # Form components
│   │   ├── Tables/     # Table components
│   │   └── ui/         # Base UI components
│   ├── layouts/        # Layout components
│   ├── pages/          # Page components
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   ├── App.jsx         # Main App component
│   └── main.jsx        # Entry point
├── .eslintrc.json      # ESLint configuration
├── package.json        # Dependencies and scripts
├── postcss.config.js   # PostCSS configuration
├── tailwind.config.js  # Tailwind CSS configuration
└── vite.config.js      # Vite configuration
```

## 🎨 Customization

### Tailwind Configuration

Customize your theme in `tailwind.config.js`:

```javascript
export default {
  theme: {
    extend: {
      colors: {
        // Add your custom colors
      },
    },
  },
};
```

## 📦 Build & Deployment

### Build for production

```bash
npm run build
```

The build output will be in the `dist/` folder.

### Deploy to Netlify

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

### Deploy to Vercel

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

## 👨‍💻 Author

**Your Name**

- GitHub: [@AdityaSangwan0011](https://github.com/AdityaSangwan0011)
- LinkedIn: [Your Name](www.linkedin.com/in/aditya-sangwan-b37831370)
