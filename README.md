# PodcastLingo - English Learning Platform

![PodcastLingo](https://images.unsplash.com/photo-1589903308904-1010c2294adc?auto=format&fit=crop&q=80&w=1200&h=300)

PodcastLingo is a modern web application designed to help users learn English through podcast-based education. It combines the power of authentic content with interactive learning features to create an engaging and effective language learning experience.

## Features

### 🎧 Podcast Learning
- **Curated Content**: Diverse collection of podcasts across various topics
- **Difficulty Levels**: Content categorized into Beginner, Intermediate, and Advanced
- **Interactive Transcripts**: Real-time synchronized transcripts with audio playback
- **Vocabulary Highlights**: Key terms and phrases highlighted with definitions

### 📚 Learning Tools
- **Vocabulary Collection**: Save and review important words and phrases
- **Interactive Quizzes**: Test comprehension after each podcast
- **Progress Tracking**: Monitor learning progress with detailed statistics
- **Study Streaks**: Maintain motivation with daily study tracking

### 🎯 Personalization
- **Saved Clips**: Create and save important segments from podcasts
- **Personal Notes**: Add notes to saved clips and vocabulary items
- **Favorites**: Bookmark podcasts for later listening
- **Learning Path**: Customized content recommendations based on progress

## Tech Stack

- **Frontend**: React with TypeScript
- **Routing**: React Router v6
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Icons**: Lucide React
- **State Management**: Zustand

## Getting Started

1. **Clone the repository**
```bash
git clone [repository-url]
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the development server**
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── learning/      # Learning-specific components
│   └── me/           # User profile components
├── pages/             # Main route pages
├── data/              # Mock data and constants
├── store/             # State management
└── types/             # TypeScript type definitions
```

## Key Components

### Pages
- **Home**: Featured and categorized podcast listings
- **Explore**: Search and filter podcasts
- **My Learning**: Progress tracking and learning tools
- **Me**: User profile and saved content

### Features
- **Audio Player**: Global audio playback control
- **Transcript View**: Interactive podcast transcripts
- **Vocabulary Tools**: Word definitions and examples
- **Progress Charts**: Visual learning progress tracking

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Podcast content is for demonstration purposes only
- Images sourced from Unsplash
- Icons provided by Lucide React