# ita-city
iTA-City: Intelligent Urban Development Platform

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![iTA](https://img.shields.io/badge/iTA-v2.0-ff6b6b.svg)
![Persian](https://img.shields.io/badge/language-Farsi%20%7C%20English%20%7C%20Arabic-yellow.svg)

**iTA-City** is an innovative urban development platform that enables citizens to suggest city improvement projects and evaluates them using the iTA v2 algorithm (Unity, Balance, Governance indicators) with gamification elements.

## ✨ Features

### 🎯 Core Features
- **Citizen Registration**: Secure registration for Iranians (10-digit national code) and foreign visitors
- **iTA v2 Algorithm**: Automatic evaluation of suggestions using Unity, Balance, Governance indicators
- **Multi-Map Integration**: Google Maps, Neshan Map, Balad Map support
- **Gamification System**: Points, badges, leaderboards for citizen engagement
- **Multi-language**: Persian, English, Arabic interface
- **Real-time Evaluation**: Instant iTA scoring for suggestions

### 📊 iTA v2 Indicators
- **Unity**: Social cohesion, equitable access, cultural integration
- **Balance**: Environmental equilibrium, regional development, economic-social balance
- **Governance**: Transparency, urban management efficiency, participatory governance

### 🎮 Gamification Elements
- Citizen points system
- Achievement badges
- City-wide leaderboards
- Special rewards for foreign visitors
- Level progression system

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ and npm
- Python 3.8+ (for backend)
- PostgreSQL 12+ with PostGIS
- Redis (for caching)

### Installation

```bash
# Clone repository
git clone https://github.com/yourusername/ita-city.git
cd ita-city

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Initialize database
npm run db:init

# Start development server
npm run dev
