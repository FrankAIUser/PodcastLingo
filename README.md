# PodcastLingo - English Learning Platform

![PodcastLingo](https://images.unsplash.com/photo-1589903308904-1010c2294adc?auto=format&fit=crop&q=80&w=1200&h=300)

PodcastLingo is a modern web application designed to help users learn English through podcast-based education. It combines the power of authentic content with interactive learning features to create an engaging and effective language learning experience.

## Features

### 🎧 Podcast Learning
- **Curated Content**: 
  - Hand-picked podcasts from native English speakers
  - Topics include business, technology, culture, and daily life
  - New content added weekly
  - Downloadable episodes for offline learning
- **Difficulty Levels**: 
  - Beginner: Slower speech rate, basic vocabulary
  - Intermediate: Natural speech with clear pronunciation
  - Advanced: Native-speed conversations, complex topics
- **Interactive Transcripts**: 
  - Word-by-word highlighting during playback
  - Click any word to jump to that timestamp
  - Toggle between full and simplified transcripts
  - Dual language support for selected content
- **Vocabulary Highlights**: 
  - AI-powered identification of key terms
  - Context-based definitions and examples
  - Pronunciation guides with IPA notation
  - Collocation suggestions and usage notes

### 📚 Learning Tools
- **Vocabulary Collection**: 
  - Personal vocabulary lists with spaced repetition
  - Export options for external study tools
  - Custom categorization and tagging
  - Audio pronunciation for each saved word
- **Interactive Quizzes**: 
  - Multiple quiz types (MCQ, fill-in-blanks, listening)
  - Adaptive difficulty based on performance
  - Immediate feedback with explanations
  - Review mode for missed questions
- **Progress Tracking**: 
  - Detailed analytics dashboard
  - Weekly and monthly progress reports
  - Vocabulary retention metrics
  - Time spent learning statistics
- **Study Streaks**: 
  - Daily learning goals and achievements
  - Customizable streak targets
  - Reminder notifications
  - Social sharing of achievements

### 🎯 Personalization
- **Saved Clips**: 
  - Create custom audio snippets
  - Add personal annotations
  - Share clips with other learners
  - Practice mode for clip repetition
- **Personal Notes**: 
  - Rich text editor for note-taking
  - Tag system for organization
  - Search across all notes
  - Export options in multiple formats
- **Favorites**: 
  - Smart playlist creation
  - Custom episode ordering
  - Category-based organization
  - Quick access to frequent content
- **Learning Path**: 
  - AI-powered content suggestions
  - Skill-based progression system
  - Interest-based recommendations
  - Adaptive learning speed

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