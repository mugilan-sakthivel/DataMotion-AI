# DataMotion-AI: AI-Powered Data Visualization

**Transform Raw Data into Stunning Animated Infographics**

DataMotion-AI is an intelligent platform that automates the transformation of raw data into compelling animated infographics. Using cutting-edge AI and visualization technologies, it enables efficient, scalable, and visually engaging data storytelling.

## Features

- **AI-Powered Data Analysis** - Automatically parse CSV/text data and extract meaningful insights
- **Smart Chart Selection** - AI recommends the best visualization types based on your data  
- **Animated Infographics** - Create professional MP4 videos with smooth animations
- **Multiple Chart Types** - Pie charts, Bar graphs, Line charts, Area charts, and more
- **Real-Time Previews** - Interactive preview before video export
- **Customizable Animations** - Full control over animation speed, duration, and effects
- **High-Quality Export** - Export as MP4 videos in various resolutions
- **User-Friendly Interface** - Intuitive UI for both technical and non-technical users

## Tech Stack

**Frontend:**
- React.js - Modern UI framework
- TailwindCSS - Responsive styling
- File Upload API - Handle CSV and text file inputs

**Backend:**
- Node.js - Server runtime
- Express.js - REST API framework
- MongoDB - Data persistence

**AI & Data Processing:**
- Google Gemini API - LLM for data parsing and chart recommendations
- Remotioon - Video animation and rendering
- MP4 Encoding - High-quality video export

## How It Works

1. **Data Input** - Upload CSV files or paste raw data
2. **AI Analysis** - Gemini AI parses the data structure and identifies patterns
3. **Chart Recommendation** - AI suggests optimal visualization types
4. **Visualization Creation** - Generate interactive charts with custom styling
5. **Animation & Rendering** - Add smooth animations and render as MP4
6. **Export & Share** - Download video or share via link

## Getting Started

### Prerequisites
- Node.js v14+
- npm or yarn
- MongoDB instance
- Google Gemini API key

### Installation

1. Clone Repository
```bash
git clone https://github.com/mugilan-sakthivel/DataMotion-AI.git
cd DataMotion-AI
```

2. Setup Backend
```bash
cd backend
npm install
cp .env.example .env
# Edit .env with your API keys
npm start
```

3. Setup Frontend
```bash
cd ../client
npm install
npm start
```

## Project Structure

```
DataMotion-AI/
- client/              # React frontend
- render-container/    # Video rendering service
- backend/             # API server
- docker-compose.yml   # Docker configuration
```

## Usage Example

### Sample Data
```csv
Month,Revenue,Expenses,Profit
January,50000,30000,20000
February,55000,32000,23000
March,60000,35000,25000
```

### Steps
1. Upload CSV file
2. AI analyzes and suggests visualization
3. Customize colors and animations
4. Preview and export as MP4

## Chart Types Supported

- Pie Charts - Proportions and percentages
- Bar Charts - Compare values across categories
- Line Charts - Show trends over time
- Area Charts - Cumulative trends
- Scatter Plots - Show relationships
- Histograms - Distribution analysis

## Contributors

- **Mugilan Sakthivel** - Lead Developer
- **Alwin Sunil** - Contributor
- **Anam Ashraf** - Contributor

## Project Stats

- GitHub Stars: 1
- Contributors: 4
- License: MIT
- Primary Language: JavaScript

## Roadmap

- Real-time collaboration features
- More chart types (Sankey, Treemap)
- Template library
- AI-powered narrative generation
- Multi-language support
- Export to multiple formats (PNG, GIF, WebM)

## License

MIT License - see LICENSE file for details

## Support

- Issues: [GitHub Issues](https://github.com/mugilan-sakthivel/DataMotion-AI/issues)
- LinkedIn: [mugilansakthivel](https://linkedin.com/in/mugilansakthivel)

---

**Built with love by DataMotion-AI Team**

*Last Updated: November 14, 2025*

[Live Demo](https://data-motion-ai.vercel.app) | [GitHub](https://github.com/mugilan-sakthivel/DataMotion-AI) | [Report Issue](https://github.com/mugilan-sakthivel/DataMotion-AI/issues)
