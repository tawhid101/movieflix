
# 🎬 MovieFinder

MovieFinder is a sleek and responsive web application that allows you to effortlessly search for movies. Built with modern technologies, it provides a seamless user experience for discovering new films and viewing trending searches.

![MovieFinder Screenshot](public/hero-bg.png) 

## ✨ Features

- **Instant Search**: Find movies in real-time as you type.
- **Trending Movies**: See what movies are currently popular among users.
- **Debounced Search**: Optimizes API requests for a smoother experience.
- **Responsive Design**: Enjoy a seamless experience on any device, from desktops to smartphones.
- **Dynamic UI**: A clean and modern interface built with React and Tailwind CSS.

## 🚀 Live Demo

https://moviiefliix.netlify.app/

## 🛠️ Built With

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
- [Vite](https://vitejs.dev/) - A next-generation front-end tooling.
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework.
- [Appwrite](https://appwrite.io/) - An open-source backend platform for building web and mobile applications.
- [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api) - For movie data.

## 📦 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js (v18 or later)
- npm

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username/movie-app.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Create a `.env` file in the root of your project and add the following environment variables:
   ```
    VITE_TMDB_API_KEY="YOUR_TMDB_API_KEY"
    VITE_APPWRITE_ENDPOINT="YOUR_APPWRITE_ENDPOINT"
    VITE_APPWRITE_PROJECT_ID="YOUR_APPWRITE_PROJECT_ID"
    VITE_APPWRITE_DATABASE_ID="YOUR_APPWRITE_DATABASE_ID"
    VITE_APPWRITE_COLLECTION_ID="YOUR_APPWRITE_COLLECTION_ID"
   ```
4. Start the development server
   ```sh
   npm run dev
   ```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
