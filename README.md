# MERN ThinkBoard - Frontend

A modern note-taking application built with React, TypeScript, and Vite. This is the frontend part of the MERN ThinkBoard project.

## 🚀 Features

- **Modern UI**: Built with React 18 and TypeScript
- **Responsive Design**: Fully responsive using Tailwind CSS
- **Fast Development**: Powered by Vite for lightning-fast HMR
- **Note Management**: Create, read, update, and delete notes
- **Real-time Updates**: Seamless integration with backend API
- **Type Safety**: Full TypeScript support for better development experience

## 🛠️ Tech Stack

- **React 18** - UI Library
- **TypeScript** - Type Safety
- **Vite** - Build Tool & Dev Server
- **Tailwind CSS** - Styling
- **Axios** - HTTP Client
- **React Hot Toast** - Notifications
- **ESLint** - Code Linting

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/TanMinhNgo/mern-thinkboard-frontend.git
   cd mern-thinkboard-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   
   Create a `.env` file in the root directory:
   ```env
   MODE=development
   BACKEND_URL=http://localhost:8080
   ```

4. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173`

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Navbar.tsx
│   ├── NoteCard.tsx
│   ├── NotesNotFound.tsx
│   └── RateLimitedUI.tsx
├── pages/              # Page components
│   └── HomePage.tsx
├── lib/                # Utilities and configurations
│   └── axios.ts
├── App.tsx             # Main App component
└── main.tsx           # Entry point
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌐 Backend Integration

This frontend connects to the MERN ThinkBoard backend API. Make sure to:

1. Start the backend server first
2. Update the `BACKEND_URL` in your `.env` file
3. Ensure CORS is properly configured on the backend

**Backend Repository**: [mern-thinkboard-backend](https://github.com/TanMinhNgo/mern-thinkboard-backend)

## 🚀 Deployment

### Production Build

```bash
npm run build
```

The build files will be generated in the `dist/` directory.

### Deploy to Vercel/Netlify

1. Connect your GitHub repository
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Add environment variables in deployment settings

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Tan Minh Ngo**
- GitHub: [@TanMinhNgo](https://github.com/TanMinhNgo)

## 🙏 Acknowledgments

- React team for the amazing library
- Vite team for the super fast build tool
- Tailwind CSS for the utility-first CSS framework

---

⭐ Star this repo if you find it helpful!
