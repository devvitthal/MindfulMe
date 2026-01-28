# 🧘 MindfulMe - Mental Health & Wellness Platform

A comprehensive web application designed to support mental wellness through personalized assessments, meditation, music therapy, and ancient wisdom. MindfulMe provides users with a holistic approach to mental health by combining modern therapeutic techniques with traditional practices.

## 🌟 Features

### 🔐 User Authentication

- Secure authentication powered by **Clerk**
- Protected routes for personalized user experiences
- Sign-in/Sign-up with multiple providers

### 📊 Mental Health Assessment

- Interactive questionnaire with 10+ comprehensive questions
- Real-time progress tracking
- Personalized mental health scoring (1-10 scale)
- Assessment covers:
  - Overall mental health status
  - Overthinking patterns
  - Stress levels
  - Anxiety and worry frequency
  - Social anxiety
  - Emotional state
  - Duration of symptoms

### 🎯 Personalized Dashboard

Access to specialized resources based on your needs:

- **Anxiety Management** - Techniques and exercises for anxiety relief
- **Depression Support** - Resources and coping strategies
- **Stress Relief** - Stress management tools and practices
- **Overthinking Control** - Methods to reduce excessive thinking
- **Affirmations** - Daily positive affirmations for mental strength
- **Meditation** - Guided meditation and breathing exercises
- **Music Therapy** - Therapeutic music for mental peace
- **Shlokas** - Ancient Sanskrit verses for spiritual wellness

### 🎵 Music Therapy

- Built-in audio player with therapeutic music tracks
- Collection includes:
  - Morning Peace
  - Afternoon Peace
  - Mild Music
  - Droplets of Calm
  - Stream of Serenity
  - Relaxation Sound
- Full playback controls (Play, Pause, Skip, Progress bar)
- Auto-play next track functionality

### 🧘 Meditation & Mindfulness

- Guided breathing exercises
- Mental calmness techniques
- Daily practice recommendations

### 📖 Ancient Wisdom

- Collection of traditional Shlokas (Sanskrit verses)
- Integration of spiritual practices with modern wellness

## 🛠️ Technologies Used

### Frontend Framework & Libraries

- **React 18.3.1** - UI library
- **TypeScript** - Type-safe development
- **React Router DOM 6.22.3** - Client-side routing
- **Vite 5.4.2** - Fast build tool and dev server

### Styling

- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **PostCSS 8.4.35** - CSS transformations
- **Autoprefixer 10.4.18** - CSS vendor prefixing

### Authentication

- **Clerk React 5.27.0** - Complete authentication solution

### Icons & UI Elements

- **Lucide React 0.344.0** - Beautiful & consistent icons

### Code Quality & Linting

- **ESLint 9.9.1** - Code linting
- **TypeScript ESLint 8.3.0** - TypeScript-specific linting rules
- **ESLint Plugin React Hooks** - React Hooks linting
- **ESLint Plugin React Refresh** - Fast Refresh support

### Build Tools

- **Vite Plugin React 4.3.1** - React support for Vite
- **TypeScript 5.5.3** - TypeScript compiler

### Deployment

- **Vercel** - Hosting and deployment platform

## 📁 Project Structure

```
mindfulme/
├── public/
│   └── music/              # Therapeutic music files
│       ├── morning-peace.mp3
│       ├── afternoon-peace.mp3
│       ├── mild-music.mp3
│       ├── droplets-of-calm.mp3
│       ├── stream-of-serenity.mp3
│       └── relaxation-sound.mp3
├── src/
│   ├── components/
│   │   ├── Navbar.tsx      # Navigation bar component
│   │   └── PrivateRoute.tsx # Protected route wrapper
│   ├── pages/
│   │   ├── Home.tsx        # Landing page
│   │   ├── Questionnaire.tsx # Mental health assessment
│   │   ├── Result.tsx      # Assessment results
│   │   ├── Dashboard.tsx   # Main dashboard
│   │   └── dashboard/      # Dashboard sub-pages
│   │       ├── Affirmation.tsx
│   │       ├── Anxiety.tsx
│   │       ├── Depression.tsx
│   │       ├── Meditation.tsx
│   │       ├── MusicTherapy.tsx
│   │       ├── Overthinking.tsx
│   │       ├── Shlokas.tsx
│   │       └── Stress.tsx
│   ├── utils/
│   │   ├── Music.ts        # Music tracks data
│   │   ├── Questions.ts    # Assessment questions
│   │   ├── Result.ts       # Result calculation logic
│   │   └── Shlokas.ts      # Ancient verses data
│   ├── App.tsx             # Main app component with routing
│   ├── main.tsx            # App entry point
│   └── index.css           # Global styles
├── eslint.config.js        # ESLint configuration
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
├── vite.config.ts          # Vite configuration
└── vercel.json             # Vercel deployment config
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/mindfulme.git
cd mindfulme
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:
   Create a `.env` file in the root directory and add your Clerk credentials:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

4. Start the development server:

```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 🎯 Usage

1. **Sign In/Sign Up** - Create an account or sign in using Clerk authentication
2. **Take Assessment** - Complete the mental health questionnaire
3. **View Results** - Get personalized recommendations based on your score
4. **Explore Dashboard** - Access various wellness resources:
   - Practice meditation techniques
   - Listen to therapeutic music
   - Read daily affirmations
   - Learn coping strategies for anxiety, stress, and depression
   - Explore ancient wisdom through Shlokas

## 🔒 Privacy & Security

- User authentication handled securely by Clerk
- No sensitive mental health data stored permanently
- All user sessions are protected with private routes

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 👥 Contributors

- **Vitthal Biradar**
- **Mayur Aghao**

## 📄 License

This project is open source and available under the MIT License.

## 🌐 Deployment

This application is configured for deployment on Vercel. Simply connect your repository to Vercel for automatic deployments.

## 💡 Future Enhancements

- AI-powered chatbot for mental health support
- Progress tracking and mood journaling
- Community support forums
- Integration with wearable devices
- More meditation guides and exercises
- Expanded music therapy library
- Mobile application (React Native)

## 📞 Support

For support, please open an issue in the GitHub repository or contact the contributors.

---

**Note**: This application is designed to support mental wellness and is not a replacement for professional mental health care. If you're experiencing a mental health crisis, please contact a mental health professional or emergency services immediately.
