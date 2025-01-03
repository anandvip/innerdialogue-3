# Inner Dialogue Journal

Inner Dialogue Journal is a modern web application designed to enhance your personal journaling experience through AI-powered writing prompts and secure cloud storage. This application combines the therapeutic benefits of journaling with cutting-edge AI technology to inspire meaningful self-reflection.

## Features

### Authentication and User Management
- Secure Google Sign-In integration
- Personal user profiles with customizable avatars
- Protected user data access
- Seamless authentication state management

### Journal Entry Management
- Create and save journal entries with real-time updates
- Edit existing entries with automatic version tracking
- Delete unwanted entries with confirmation
- Chronological entry organization
- Preview snippets for quick content scanning
- Rich text formatting support
- Automatic save state tracking

### AI-Powered Writing Inspiration
- Integration with multiple AI providers:
  - OpenAI (GPT-3.5)
  - Mistral AI
  - Google Gemini
- Customizable writing prompts based on user-defined topics
- Focus on personal growth and self-reflection themes
- One-click prompt copying to journal
- Smart prompt generation with context awareness

### User Interface
- Clean, modern design with responsive layout
- Sidebar navigation for easy entry access
- Real-time content preview
- Toast notifications for user feedback
- Mobile-friendly interface
- Dark/light mode support
- Intuitive entry management controls

### Data Management
- Firebase Firestore integration for reliable data storage
- Real-time data synchronization
- Secure data encryption
- Automatic backup and recovery
- User data isolation and privacy

### Technical Features
- Built with modern JavaScript (ES6+)
- Firebase Authentication and Firestore integration
- Real-time database updates
- Responsive CSS design with flexbox
- Cross-browser compatibility
- Progressive Web App capabilities
- Modular code architecture

## Getting Started

### Prerequisites
- Google Firebase account
- API keys for chosen AI providers (OpenAI, Mistral, or Gemini)
- Modern web browser
- Node.js (for local development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/inner-dialogue-journal.git
```

2. Configure Firebase:
   - Create a new Firebase project
   - Enable Google Authentication
   - Set up Firestore database
   - Update the Firebase configuration in the code

3. Configure AI Providers:
   - Obtain API keys from chosen providers
   - Update the API keys in the configuration
   - Set up appropriate security measures

4. Install dependencies:
```bash
npm install
```

5. Run the application:
```bash
npm start
```

## Usage

1. Sign in using your Google account
2. Navigate to the journal interface
3. Use the AI prompt generator by:
   - Entering keywords for your desired topic
   - Selecting your preferred AI provider
   - Clicking "Generate Prompt"
4. Write your journal entry
5. Save and manage your entries from the sidebar

## Security

The application implements several security measures:
- Secure authentication through Firebase
- Protected API key handling
- User data isolation
- Encrypted data transmission
- Session management
- Input sanitization

## Contributing

We welcome contributions to improve Inner Dialogue Journal. Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

- Firebase team for the robust backend infrastructure
- OpenAI, Mistral, and Google for their AI APIs
- The open-source community for inspiration and support

## Support

For support, please open an issue in the GitHub repository or contact the maintainers directly.
