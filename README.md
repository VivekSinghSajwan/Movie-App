# Movie App

A modern, responsive movie application built with React and Vite that allows users to discover, search, and explore movies with detailed information.

## 🎬 Features

- **Movie Discovery**: Browse popular, trending, and top-rated movies
- **Search Functionality**: Find movies by title, genre, or keywords
- **Movie Details**: View comprehensive information including cast, crew, ratings, and synopsis
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Fast Performance**: Built with Vite for lightning-fast development and build times
- **Modern UI**: Clean and intuitive user interface

## 🚀 Technologies Used

- **React** - Frontend library for building user interfaces
- **Vite** - Next-generation frontend build tool
- **JavaScript/ES6+** - Modern JavaScript features
- **CSS3** - Styling and responsive design
- **TMDb API** - The Movie Database API for movie data (assumed)

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14.x or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/VivekSinghSajwan/Movie-App.git
   cd Movie-App
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   
   Create a `.env` file in the root directory and add your API keys:
   ```env
   VITE_API_KEY=your_tmdb_api_key_here
   VITE_BASE_URL=https://api.themoviedb.org/3
   ```

4. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` to view the application.

## 🏗️ Build for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

To preview the production build locally:

```bash
npm run preview
# or
yarn preview
```


## 🎯 Usage

1. **Browse Movies**: Explore different categories of movies on the home page
2. **Search**: Use the search bar to find specific movies
3. **View Details**: Click on any movie card to see detailed information
4. **Responsive Navigation**: Navigate seamlessly across different screen sizes

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 🌟 Key Features Implementation

### Movie Search
The app includes a robust search functionality that allows users to find movies by title, with real-time results and suggestions.

### Movie Details
Detailed movie pages display comprehensive information including:
- Movie poster and backdrop images
- Synopsis and plot details
- Cast and crew information
- Release date and runtime
- User ratings and reviews

### Responsive Design
The application is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile devices

## 🚀 Deployment

The app can be deployed to various platforms:

### Vercel
```bash
npm install -g vercel
vercel
```

### Netlify
```bash
npm run build
# Deploy the dist/ folder to Netlify
```

### GitHub Pages
```bash
npm install --save-dev gh-pages
npm run build
npx gh-pages -d dist
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [TMDb](https://www.themoviedb.org/) for providing the movie database API
- [React](https://reactjs.org/) for the amazing frontend library
- [Vite](https://vitejs.dev/) for the fast build tool
- All contributors who help improve this project

## 📧 Contact

**Vivek Singh Sajwan**
- GitHub: [@VivekSinghSajwan](https://github.com/VivekSinghSajwan)

## 🔗 Links

- [Live Demo](https://your-deployed-app-url.com) (Add your deployment URL here)
- [Project Repository](https://github.com/VivekSinghSajwan/Movie-App)

---

⭐ If you found this project helpful, please give it a star on GitHub!
