# ArtistryByTalha
# 🎨 Creative Kids Academy

An interactive educational platform designed for children to learn through engaging activities in art, writing, and creativity.

## 🚀 Features

- **Interactive Learning Modules**: Art, Writing, Science, and more
- **User Authentication**: Secure login/logout with session management
- **Progress Tracking**: Monitor learning progress and achievements
- **Gamified Experience**: Badges, certificates, and reward system
- **AI Learning Assistant**: Personalized learning tips and suggestions
- **Responsive Design**: Works on all devices
- **Video Lessons**: Step-by-step guided tutorials
- **Interactive Games**: Hands-on learning activities
- **Portfolio System**: Showcase creative work

## 🛠️ Tech Stack

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **Passport.js** - Authentication middleware
- **Express Session** - Session management

### Frontend
- **React** - UI components (with Babel)
- **Tailwind CSS** - Utility-first CSS framework
- **EJS** - Embedded JavaScript templates

### Security & Authentication
- **Passport.js** - Local authentication strategy
- **Express Session** - Session-based authentication
- **Password hashing** - Secure password storage

## 📁 Project Structure

```
loginform/
├── app.js                 # Main application file
├── package.json           # Dependencies and scripts
├── bin/
│   └── www               # Server startup script
├── public/               # Static assets
│   ├── images/
│   ├── javascripts/
│   └── stylesheets/
├── routes/               # Express routes
│   ├── index.js
│   └── users.js
└── views/                # EJS templates
    ├── profilee.ejs      # Main dashboard (React SPA)
    ├── login.ejs         # Login page
    ├── index.ejs         # Home page
    └── error.ejs         # Error page
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/creative-kids-academy.git
cd creative-kids-academy
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
# Create .env file
cp .env.example .env
```

4. Configure your MongoDB connection in the appropriate config file

5. Start the development server:
```bash
npm start
```

6. Open your browser and navigate to `http://localhost:3000`

## 🎯 Usage

1. **Register/Login**: Create an account or login to access the platform
2. **Explore Academy**: Browse through different learning modules
3. **Start Learning**: Choose from Art, Writing, or Science courses
4. **Track Progress**: Monitor your learning journey in the Profile section
5. **Earn Achievements**: Complete lessons to earn badges and certificates
6. **Use AI Assistant**: Get personalized learning tips and suggestions

## 📸 Screenshots

### Main Dashboard
![Dashboard](screenshots/dashboard.png)

### Course Selection
![Courses](screenshots/courses.png)

### Interactive Learning
![Learning](screenshots/learning.png)

## 🎨 Key Features in Detail

### 🎭 Interactive Learning Modules
- **Creative Sculpting**: Clay modeling and 3D creation
- **Visual Arts**: Color theory, pattern making, digital drawing
- **Creative Writing**: Story creation, character building, poetry
- **Drama & Theater**: Performance arts and confidence building
- **Music & Songs**: Melody creation and rhythm
- **Science Fun**: Safe experiments and STEM learning

### 🏆 Achievement System
- Progress tracking with detailed analytics
- Badge and certificate rewards
- Gamified learning experience
- Portfolio showcase for creative work

### 🤖 AI Learning Assistant
- Personalized learning recommendations
- Interactive Q&A for creative projects
- Adaptive learning paths based on progress

## 🔧 Development

### Available Scripts
```bash
npm start          # Start the production server
npm run dev        # Start development server with nodemon
npm test           # Run tests
npm run lint       # Run ESLint
```

### Environment Variables
```env
NODE_ENV=development
PORT=3000
MONGODB_URI=mongodb://localhost:27017/creative-kids-academy
SESSION_SECRET=your-secret-key
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Talha** - [Your GitHub Profile](https://github.com/yourusername)

## 🙏 Acknowledgments

- Built with love for children's education
- Inspired by modern educational psychology
- Designed with accessibility and fun in mind

## 📞 Support

For support, email hello@artistrybytalha.com or create an issue in this repository.

---

⭐ **Star this repository if you found it helpful!** ⭐
