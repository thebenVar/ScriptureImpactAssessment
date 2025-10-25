# Scripture Impact Assessment Survey

[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)](https://github.com/thebenVar/ScriptureImpactAssessment/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-stable-brightgreen.svg)]()

A comprehensive web-based survey tool for evaluating Scripture impact in language communities through story-centered interviews and systematic coding.

## 📁 Project Structure

```
ScriptureImpactAssessment/
├── � app/                     # Main Application
│   ├── pages/                  # HTML Pages
│   │   ├── index.html          # Main survey web application
│   │   ├── login.html          # Authentication page
│   │   ├── help.html           # Help and reference page
│   │   └── coming-soon.html    # Coming soon placeholder
│   ├── js/                     # JavaScript Files
│   │   └── app.js              # Survey logic and functionality
│   ├── css/                    # Stylesheets
│   │   └── styles.css          # Web application styles
│   │   └── survey-pdf.html     # Offline PDF version (HTML)
│   ├── js/                     # JavaScript Files
│   │   └── app.js              # Survey logic and functionality
│   ├── css/                    # Stylesheets
│   │   └── styles.css          # Web application styles
│   └── assets/                 # Static Assets
│       └── Scripture Impact Assessment Survey - PDF Version.pdf
│
├── 📂 docs/                    # Documentation
│   └── PDF_Development_Log.md  # Development process documentation
│
└── 📂 .git/                    # Version control
```

## 🚀 Quick Start

### Web Application
1. Open `app/pages/index.html` in a modern web browser
2. Complete the authentication (if required)
3. Use the interactive survey interface

### PDF Version (Offline)
1. Navigate to `app/pages/survey-pdf.html`
2. Open in browser and use Ctrl+P to print/save as PDF
3. Or use the pre-generated PDF file at `app/assets/Scripture Impact Assessment Survey - PDF Version.pdf`

## 📋 Survey Components

### Interview Sections (39 Questions Total)
1. **Warm Up & Rapport** (2 questions)
2. **Personal Scripture Experience** (4 questions)
3. **Community & Church Use** (4 questions)
4. **Translation Experience** (7 questions)
5. **Access & Engagement** (8 questions)
6. **Spiritual Climate** (5 questions)
7. **Language Choices** (6 questions)
8. **Wrap-Up & Reflection** (3 questions)

### Assessment Framework
- **Matrix Coding System**: T, SE, S, M, NI categories
- **Use Levels**: 1-4 scale for vernacular Scripture use
- **Live Guidance**: Contextual interview prompts
- **Badge System**: Gamified completion tracking

## 🎯 Usage Scenarios

### Digital Interview
- Use `index.html` for interactive web-based interviews
- Real-time guidance and tips
- Automatic progress tracking and XP system
- Export functionality for data analysis

### Offline Field Work
- Use `output/survey-pdf.html` or PDF version
- Print-optimized for A4 paper
- Hand-written responses
- Matrix coding assessment included

## 💻 Technical Features

### Web Application
- **Responsive Design**: Works on desktop and mobile
- **Local Storage**: Automatic save functionality
- **Progressive Enhancement**: Works without JavaScript for basic functionality
- **Accessibility**: Keyboard navigation and screen reader support

### PDF Version
- **Print Optimization**: A4-optimized layout with color preservation
- **Professional Design**: Brand colors and typography
- **Compact Layout**: Matrix coding on page 1 for usability
- **Complete Guidance**: All interview tips and category definitions included

## 🎨 Design System

### Brand Colors
- **Primary**: #00ab82 (Scripture Impact Green)
- **Secondary**: #006d54 (Dark Green)
- **Accent**: #f59e0b (Amber for highlights)
- **Purple**: #8b5cf6 (Matrix coding elements)

### Typography
- **Font Family**: Inter (web-safe fallbacks)
- **Hierarchy**: Clear heading levels and consistent spacing
- **Readability**: Optimized for both screen and print

## 📖 Documentation

### Development Log
- Complete interaction history in `docs/PDF_Development_Log.md`
- Technical implementation details
- Design decision rationale
- Future maintenance guidance

### Help System
- Comprehensive help page at `help.html`
- Interview guidelines and best practices
- Category definitions and coding instructions

## 🔧 Development Guidelines

### File Organization Standards
- **Core files**: Root directory for main application
- **Documentation**: `docs/` folder for all documentation
- **Output files**: `output/` folder for generated/exported content
- **Version control**: Standard git practices

### Coding Standards
- **HTML**: Semantic markup with accessibility considerations
- **CSS**: Modern flexbox/grid layouts with print optimization
- **JavaScript**: Vanilla JS with progressive enhancement
- **Documentation**: Comprehensive inline comments and external docs

## 📊 Assessment Categories

### T - Translation Experience
Quality, naturalness, key terms, comprehension, trust in translators

### SE - Scripture Engagement  
Access pathways, formats, distribution, acquisition barriers

### S - Spiritual Climate
Openness, hunger, resistance, social dynamics around faith

### M - Multilingual Dynamics
Language choices, inclusion/exclusion, prestige, leader capability

### NI - No Issues
Status quo adequate, low felt need for change

## 👥 Attribution

**Copyright:** NLCI/PBT (2025)  
**Adapted by:** NLCI Research and Innovation Department  
**Version:** PDF for offline distribution  

## 📄 License

This project is developed for NLCI/PBT research purposes. Please refer to organizational guidelines for usage and distribution.

## 🚀 Changelog

### [1.1.0] - 2025-10-25
#### Fixed
- **Vercel Deployment**: Resolved 404 errors and missing survey questions
- **File Path Resolution**: Fixed CSS, JavaScript, and asset loading issues
- **Root Directory Compatibility**: Added app/index.html for proper Vercel deployment

#### Improved
- **Deployment Configuration**: Optimized vercel.json for clean URL routing
- **File Organization**: Maintained organized structure while ensuring compatibility
- **Production Readiness**: Enhanced deployment reliability and accessibility

#### Technical Changes
- Added root index.html in app/ directory for Vercel compatibility
- Updated file paths to use relative references (./css/, ./js/, ./assets/)
- Simplified Vercel rewrites configuration
- Fixed navigation links and asset references

### [1.0.0] - 2025-10-25
#### Added
- Complete web-based survey interface with 39 questions across 8 sections
- Offline PDF version optimized for A4 printing with matrix coding
- Professional project structure with organized folders (pages/, js/, css/, assets/)
- Interactive features: local storage, progress tracking, badge system
- Comprehensive documentation and development log
- Mobile-responsive design with Tailwind CSS
- Help and reference system with contextual guidance

#### Features
- **Survey Sections**: Warm Up, Personal Experience, Community Use, Translation, Access & Engagement, Spiritual Climate, Language Choices, Wrap-Up
- **PDF Integration**: Both HTML and downloadable PDF versions
- **Data Management**: Local storage persistence and export functionality
- **Professional Organization**: Clean folder structure following industry standards
- **Documentation**: Complete development log and user guidance

#### Technical
- Vanilla JavaScript with modular architecture
- Tailwind CSS for responsive design
- Print-optimized CSS for PDF generation
- Cross-browser compatibility
- Mobile-first responsive design

---

*For detailed development history and technical implementation notes, see `docs/PDF_Development_Log.md`*