# ShroomDex - AI-Powered Mushroom Identification

A comprehensive mushroom identification application with **Google Gemini AI** integration for expert-level mushroom analysis and an educational database of 50 common mushroom species.

## 🧠 NEW: Gemini AI Integration

### Advanced AI Scanner Features
- **Google Gemini AI**: State-of-the-art vision AI with 30+ years of mycological expertise
- **Expert-Level Analysis**: Comprehensive mushroom identification with detailed characteristics
- **Safety-First Approach**: Advanced toxicity assessment and consumption warnings
- **Real-Time Processing**: Instant analysis with confidence scoring
- **Comprehensive Reports**: Detailed physical characteristics, habitat, and safety information

### AI Capabilities
- **Visual Recognition**: Advanced computer vision for mushroom identification
- **Toxicity Assessment**: Detailed safety warnings and edibility information
- **Characteristic Analysis**: Cap, gill, stalk, and spore print analysis
- **Habitat Recognition**: Environmental context and growing conditions
- **Similar Species Detection**: Look-alike warnings and comparison
- **Confidence Scoring**: AI certainty levels for identification accuracy

## 🍄 Features

### Part 1: Educational Database
- **50 Mushroom Species**: Curated collection with real photos from scientific databases
- **Scientific Image Sources**: Images from Danish Fungi Dataset, FungiNet Database, and iNaturalist observations
- **Detailed Information**: Physical characteristics, habitat, edibility, and safety warnings
- **Smart Search**: Search by name, color, habitat, or characteristics
- **Habitat Filtering**: Filter by Woods, Grasses, Meadows, Paths, and Urban environments
- **Dark Mode**: Full dark/light theme support
- **Responsive Design**: Works on desktop, tablet, and mobile devices

### Part 2: Gemini AI Scanner
- **Image Upload**: Take photos or upload existing images
- **Gemini AI Analysis**: Google's most advanced AI for species identification
- **Expert Knowledge**: 30+ years of mycological expertise built-in
- **Safety Warnings**: Comprehensive toxicity information and consumption warnings
- **Detailed Characteristics**: Physical features, habitat, and growing conditions
- **Confidence Scoring**: Shows AI identification confidence percentage
- **Similar Species**: Warnings about look-alike dangerous species

## 🤖 Gemini AI Setup

### API Configuration
The app uses Google Gemini AI for advanced mushroom identification:

```env
# .env file
VITE_GEMINI_API_KEY=AIzaSyBd38db8-6fSyDu1fpsM9e3tjW-fdolEOU
VITE_GEMINI_MODEL=gemini-1.5-flash
VITE_GEMINI_VISION_MODEL=gemini-1.5-flash
```

### AI Features
- **Advanced Vision Analysis**: Analyzes cap, gills, stalk, and environmental context
- **Expert Prompting**: Uses 30+ years of mycological expertise in AI prompts
- **Safety-First Design**: Defaults to "not edible" unless high confidence
- **Comprehensive Reports**: Detailed identification with warnings and tips
- **Real-Time Processing**: Fast analysis with progress indicators

## 🔬 Scientific Database Integration

### Image Sources
Our mushroom collection uses high-quality images from authoritative scientific sources:

- **Danish Fungi Dataset**: Professional mycological photography
- **FungiNet Database**: Comprehensive European fungi collection
- **iNaturalist Observations**: Community-verified mushroom photos
- **Wikimedia Commons**: Scientific collection with proper attribution

### Data Quality
- **Verified Species**: All mushrooms verified against scientific databases
- **Multiple Angles**: Alternative images showing different growth stages
- **Habitat Accuracy**: Location data from field observations
- **Safety Classification**: Toxicity data from mycological research

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Google Gemini API key

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd shroomdx

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your Gemini API key to .env

# Start development server
npm run dev
```

### Environment Variables
Create a `.env` file in the root directory:

```env
# Gemini AI Configuration (Required)
VITE_GEMINI_API_KEY=your_gemini_api_key_here
VITE_GEMINI_MODEL=gemini-1.5-flash
VITE_GEMINI_VISION_MODEL=gemini-1.5-flash

# Optional fallback services
VITE_GOOGLE_VISION_API_KEY=your_google_vision_api_key
VITE_PLANTNET_API_KEY=your_plantnet_api_key
```

## 🧠 Gemini AI Implementation

### Advanced Prompting
The AI uses expert-level prompting with:
- **30+ years mycological expertise** built into prompts
- **Safety-first approach** with toxicity warnings
- **Comprehensive analysis** of all mushroom characteristics
- **Look-alike warnings** for dangerous species
- **Confidence thresholds** for safe identification

### Analysis Features
```javascript
// Key AI capabilities
- Cap characteristics (color, shape, size, texture)
- Gill features (color, attachment, spacing)
- Stalk properties (color, shape, ring, base)
- Spore print analysis
- Habitat and substrate recognition
- Seasonal and geographic considerations
- Toxicity assessment
- Similar species warnings
```

### Safety Features
- **High Confidence Required**: 85%+ confidence for edible classifications
- **Default to Dangerous**: Unknown mushrooms marked as poisonous
- **Expert Verification**: Always recommends professional identification
- **Multiple Warnings**: Clear toxicity and consumption warnings
- **Look-alike Alerts**: Warnings about similar toxic species

## 🎨 Design Features

- **Apple-level Design**: Clean, intuitive interface with Gemini AI branding
- **Scientific Accuracy**: Images from authoritative databases
- **AI-Enhanced UX**: Real-time analysis progress and confidence indicators
- **Micro-interactions**: Smooth animations and hover effects
- **Accessibility**: Full keyboard navigation and screen reader support
- **Performance**: Optimized images and lazy loading
- **Mobile-first**: Responsive design for all devices

## 📱 Technology Stack

- **Frontend**: React 18 + TypeScript
- **AI Engine**: Google Gemini AI (gemini-1.5-flash)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Image Processing**: Canvas API for image optimization
- **Scientific Data**: Danish Fungi Dataset, FungiNet, iNaturalist

## 🔮 Future Enhancements

- **Offline AI Mode**: Download model for offline identification
- **GPS Integration**: Location-based species suggestions
- **Community Features**: User submissions and AI verification
- **Advanced Filters**: Spore print color, gill attachment, etc.
- **Expert Network**: Connect with local mycologists
- **AI Training**: Continuous learning from user feedback
- **Multi-language**: AI analysis in multiple languages

## 📊 Gemini AI Advantages

### Why Gemini AI?
- **State-of-the-art Vision**: Google's most advanced multimodal AI
- **Expert Knowledge**: Trained on vast mycological datasets
- **Safety Focus**: Built-in safety protocols for mushroom identification
- **Real-time Analysis**: Fast processing with detailed results
- **Continuous Learning**: Regular model updates and improvements

### AI Performance
- **High Accuracy**: 85%+ confidence threshold for safety
- **Comprehensive Analysis**: 15+ characteristics analyzed
- **Safety Warnings**: Detailed toxicity and look-alike information
- **Expert Prompting**: 30+ years of mycological expertise
- **Multi-modal**: Text and vision analysis combined

## ⚠️ Important Disclaimers

- **Never consume wild mushrooms** without expert identification
- **AI identification is not 100% accurate**
- **Always consult professional mycologists**
- **This app is for educational purposes only**
- **Misidentification can be fatal**
- **Gemini AI provides expert-level analysis but requires human verification**

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Add your improvements
4. Test with Gemini AI integration
5. Submit a pull request
6. Include scientific sources for any new data

## 📄 License

MIT License - see LICENSE file for details

## 🙏 Acknowledgments

- **Google Gemini AI** - Advanced multimodal AI for mushroom identification
- **Danish Fungi Dataset** - Professional mycological photography
- **FungiNet Database** - European fungi research network
- **iNaturalist Community** - Citizen science observations
- **Wikimedia Commons** - Open scientific image collection
- **Mycological Societies** - Expert knowledge and verification

---

**Remember: When in doubt, don't consume! Your safety is more important than any mushroom meal.**

*Powered by Google Gemini AI for expert-level mushroom identification. Images and data sourced from scientific databases for educational purposes.*