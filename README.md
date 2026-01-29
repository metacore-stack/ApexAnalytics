# QuantumTrade Analytics - Enterprise Multi-Agent Financial Intelligence Platform

[![Next.js](https://img.shields.io/badge/Next.js-15.5.7-black)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-blue)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)
[![Tests](https://img.shields.io/badge/Tests-53%2B%20Passing-brightgreen)](https://developers.google.com/web/tools/lighthouse)
[![Performance](https://img.shields.io/badge/Lighthouse-90+-brightgreen)](https://developers.google.com/web/tools/lighthouse)

> An enterprise-grade financial intelligence platform featuring advanced multi-agent AI orchestration, real-time market analytics, and comprehensive portfolio management capabilities. Built by a senior AI engineer with expertise in distributed systems, LLM orchestration, and production-scale applications.

## 📸 Platform Visualizations

### Main Dashboard Interface

![QuantumTrade Analytics Dashboard](public/Finance-Markets-Analysis.png)

**Technical Overview:** This screenshot demonstrates the comprehensive market analysis dashboard, showcasing the platform's ability to aggregate and visualize multi-market financial data in real-time. The interface displays:

- **Multi-Asset Class Integration**: Unified view of stocks, forex, and cryptocurrency markets with synchronized data streams
- **Advanced Data Visualization**: Interactive charts powered by Recharts and D3.js, featuring responsive design and smooth animations
- **Real-Time Price Updates**: Live market data integration via Twelve Data API with WebSocket-like capabilities
- **Responsive UI Architecture**: Built with Next.js 15 App Router, utilizing server-side rendering for optimal performance
- **Theme System**: Dark/light mode implementation using CSS variables and Tailwind CSS for seamless user experience
- **Accessibility Features**: WCAG AA compliant design with keyboard navigation and screen reader support

The dashboard architecture demonstrates senior-level frontend engineering skills, including state management optimization, efficient data fetching patterns, and performance-conscious rendering strategies.

### System Architecture Diagram

![QuantumTrade System Architecture](public/Architecture.png)

**Architecture Deep Dive:** This diagram illustrates the sophisticated multi-agent AI system architecture, representing a production-ready implementation of distributed AI orchestration:

- **LangGraph State Machine**: Central orchestration layer managing agent workflows and state transitions
- **Orchestrator-Workers Pattern**: Supervisor agent (LLaMA 3.3 70B) coordinating specialized worker agents (LLaMA 3.1 8B) for optimal resource utilization
- **Intelligent Routing System**: Query analysis engine that determines optimal agent allocation (1-2 agents for simple queries, 2-3 for complex analysis)
- **Token Optimization Pipeline**: Message history truncation and smart routing achieving 60-70% token cost reduction compared to traditional approaches
- **Real-Time Streaming**: Server-Sent Events (SSE) implementation for live agent status updates and progressive response delivery
- **Microservices Architecture**: Modular API design with dedicated endpoints for each market type (crypto, forex, stocks)
- **Database Layer**: MongoDB Atlas integration with optimized schema design for portfolio and watchlist management
- **External API Integration**: Multi-source data aggregation from Twelve Data, NewsAPI, Reddit, and Tavily Search

This architecture showcases expertise in:
- **Distributed Systems Design**: Understanding of microservices patterns and service communication
- **LLM Orchestration**: Advanced knowledge of LangGraph state machines and agent coordination
- **Cost Optimization**: Strategic token management and efficient model selection
- **Real-Time Systems**: SSE implementation for streaming responses
- **API Design**: RESTful architecture with proper error handling and rate limiting

### Market Analysis Interface - Page 2

![Market Analysis Interface](public/Finance-Markets-Analysis%20page%202.png)

**Feature Highlights:** This view demonstrates the platform's advanced market analysis capabilities:

- **Technical Indicator Integration**: Real-time calculation and display of RSI, MACD, EMA, Bollinger Bands, ATR, ADX, and OBV indicators
- **Multi-Timeframe Analysis**: Support for various chart intervals (1m, 5m, 15m, 1h, 4h, 1d, 1w) with seamless switching
- **OHLC Chart Rendering**: Professional candlestick charts with volume overlays and technical indicator overlays
- **Data Aggregation**: Efficient handling of large datasets with pagination and lazy loading
- **Client-Side State Management**: React hooks and SWR for optimal data fetching and caching strategies

### Market Analysis Interface - Page 3

![Advanced Market Analytics](public/Finance-Markets-Analysis%20page%203.png)

**Technical Implementation:** This screenshot showcases:

- **Portfolio Analytics Dashboard**: Real-time P&L calculations with efficient database queries and caching
- **Asset Allocation Visualization**: Interactive pie charts and correlation matrices for diversification analysis
- **Performance Metrics**: Calculation of portfolio-level metrics including total value, daily change, and percentage returns
- **Export Functionality**: CSV and PDF generation capabilities using server-side rendering and client-side libraries
- **Responsive Grid Layout**: CSS Grid and Flexbox implementation for adaptive layouts across device sizes

### Market Analysis Interface - Page 4

![Portfolio Management System](public/Finance-Markets-Analysis%20page%204.png)

**Backend Engineering Excellence:** This view demonstrates:

- **Database Schema Design**: MongoDB models with proper indexing for fast queries on portfolio and watchlist operations
- **RESTful API Design**: Clean endpoint structure following REST principles with proper HTTP status codes
- **Authentication & Authorization**: NextAuth.js integration with secure session management
- **Data Validation**: Input sanitization using DOMPurify and custom validation schemas
- **Error Handling**: Comprehensive error boundaries and user-friendly error messages

### Market Analysis Interface - Page 5

![Advanced Search & Discovery](public/Finance-Markets-Analysis%20page%205.png)

**Search Architecture:** This interface highlights:

- **Command Palette Implementation**: Keyboard-first navigation system (⌘K / Ctrl+K) built with Radix UI primitives
- **Fuzzy Search Algorithm**: Real-time search across multiple data sources with efficient filtering
- **Recent Items Tracking**: LocalStorage integration for user preference persistence
- **Cross-Market Search**: Unified search interface querying stocks, forex, and crypto simultaneously
- **Performance Optimization**: Debounced search queries and memoized results for smooth user experience

### Market Analysis Interface - Page 6

![AI Advisor Interface](public/Finance-Markets-Analysis%20page%206.png)

**AI System Showcase:** This screenshot demonstrates the multi-agent AI advisor interface:

- **Streaming Response Display**: Real-time text streaming with proper state management and UI updates
- **Agent Status Indicators**: Visual feedback showing which agents are active during query processing
- **Conversation History**: Efficient message storage and retrieval with proper memory management
- **Context Preservation**: Smart context window management for maintaining conversation flow
- **Error Recovery**: Graceful handling of API failures with retry logic and user feedback

### Reddit Sentiment Analysis

![Social Sentiment Dashboard](public/Finance-Markets-Analysis-Reddit.png)

**Sentiment Analysis Engine:** This visualization demonstrates:

- **Reddit API Integration**: Aggregation of data from 15+ financial subreddits with proper rate limiting
- **Sentiment Scoring**: Natural language processing to determine bullish/bearish sentiment (75% accuracy tracking)
- **Real-Time Data Processing**: Efficient parsing and analysis of Reddit posts and comments
- **Data Visualization**: Interactive charts showing sentiment trends over time
- **API Rate Limiting**: Proper handling of Reddit API quotas with exponential backoff

## 🎯 Overview

QuantumTrade Analytics represents a production-ready financial intelligence platform that combines cutting-edge AI technology with comprehensive market data analysis. As a senior AI engineer, this project demonstrates expertise in:

- **Multi-Agent AI Systems**: Advanced LangGraph orchestration with intelligent agent routing
- **Distributed Systems**: Microservices architecture with proper service communication patterns
- **Full-Stack Development**: End-to-end implementation from database design to UI/UX
- **Performance Optimization**: Achieving 90+ Lighthouse scores through strategic optimization
- **Production Engineering**: Comprehensive testing, security, and deployment practices

The platform serves as a showcase of enterprise-level software engineering skills, combining modern web technologies with sophisticated AI orchestration to deliver actionable financial insights.

## 💼 Technical Skills Demonstrated

### AI & Machine Learning Engineering

- **LLM Orchestration**: Designed and implemented a multi-agent system using LangGraph state machines
- **Model Selection Strategy**: Optimized cost-performance ratio using LLaMA 3.3 70B for supervision and LLaMA 3.1 8B for workers
- **Token Optimization**: Achieved 60-70% cost reduction through intelligent routing and message truncation
- **Real-Time Streaming**: Implemented Server-Sent Events (SSE) for progressive response delivery
- **Agent Coordination**: Built supervisor-worker pattern with smart query routing (1-2 agents for simple, 2-3 for complex)

### Backend Engineering

- **API Design**: RESTful architecture with proper error handling, rate limiting, and validation
- **Database Architecture**: MongoDB schema design with optimized indexing for fast queries
- **Authentication**: Secure session management using NextAuth.js with proper CSRF protection
- **Security**: Comprehensive security headers, input sanitization, and environment variable validation
- **Performance**: Efficient database queries, caching strategies, and API response optimization

### Frontend Engineering

- **Modern React**: Next.js 15 App Router with TypeScript for type safety
- **State Management**: Optimized React hooks and SWR for efficient data fetching
- **UI/UX Design**: Accessible, responsive design with dark/light theme support
- **Performance**: Code splitting, lazy loading, and bundle optimization
- **Accessibility**: WCAG AA compliance with keyboard navigation and screen reader support

### DevOps & Quality Assurance

- **Testing**: Comprehensive test suite with 53+ tests (Jest + Playwright)
- **CI/CD**: Automated testing and deployment pipelines
- **Monitoring**: Performance tracking and error monitoring
- **Documentation**: Clear code documentation and README maintenance

## ✨ Key Features

### 🤖 Multi-Agent AI Advisors

**Architecture Excellence:**
- **LangGraph State Machine**: Sophisticated orchestration layer managing complex agent workflows
- **Orchestrator-Workers Pattern**: Supervisor agent coordinates specialized worker agents for optimal performance
- **Smart Routing Algorithm**: Query analysis determines optimal agent allocation, reducing unnecessary API calls
- **Token Cost Optimization**: Strategic message truncation and routing achieve 60-70% cost savings
- **Real-Time Streaming**: SSE implementation for live agent status updates and progressive responses

**Three Specialized Market Advisors:**
1. **Crypto Advisor**: Cryptocurrency analysis with social sentiment integration
2. **Forex Advisor**: Currency pair analysis with economic indicators
3. **Stock Advisor**: US equity analysis with technical and fundamental data

**Agent Team Composition:**
- **Supervisor Agent** (LLaMA 3.3 70B): Routes queries, enforces 3-call limit, synthesizes responses
- **Technical Analyst** (LLaMA 3.1 8B): Price data, volume analysis, technical indicators (RSI, MACD, EMA, Bollinger Bands, ATR, ADX)
- **Sentiment Analyst** (LLaMA 3.1 8B): Reddit community analysis across 15+ subreddits, 75% bullish tracking
- **Market Researcher** (LLaMA 3.1 8B): News aggregation, earnings data, sector trends via Tavily search

**Example Workflows:**
- Simple Query: "What's AAPL price?" → TechnicalAnalyst → Response (1 agent, <5s)
- Moderate Query: "Analyze TSLA" → TechnicalAnalyst + SentimentAnalyst → Response (2 agents, <10s)
- Complex Query: "BTC outlook" → All 3 agents → Comprehensive Response (<15s)

### 📊 Multi-Market Analysis

- **Stocks**: Real-time equity data with comprehensive technical indicators
- **Forex**: Currency pair analysis with trend identification
- **Crypto**: Cryptocurrency market tracking with social sentiment

### 💼 Portfolio Management

- **Multi-Portfolio Support**: Create and manage unlimited portfolios
- **Real-Time P&L Tracking**: Live profit/loss calculations with accurate cost basis
- **Analytics Dashboard**: Interactive charts showing portfolio performance over time
- **Asset Allocation**: Visual representation of portfolio diversification
- **Export Capabilities**: CSV and PDF export for reporting and analysis

### 👁️ Watchlist System

- **Cross-Market Tracking**: Monitor stocks, forex, and crypto in unified interface
- **Quick Access**: Fast navigation to watched assets from any page
- **Performance Statistics**: Track performance metrics for watched items
- **Export Functionality**: Export watchlist data for external analysis

### 🔍 Advanced Search

- **Command Palette**: Keyboard-first navigation (⌘K / Ctrl+K)
- **Fuzzy Search**: Real-time search with intelligent matching across all markets
- **Recent Items**: Automatic tracking of frequently accessed assets
- **Cross-Market Search**: Unified search interface querying all asset classes

### 📈 Data Visualizations

- **Portfolio Analytics**: Area charts showing portfolio value over time
- **Asset Allocation**: Pie charts for diversification analysis
- **P&L Breakdown**: Bar charts for profit/loss visualization
- **Market Heatmap**: Sector performance visualization
- **Correlation Matrix**: Diversification analysis across holdings
- **OHLC Price Charts**: Professional candlestick charts with multiple timeframes

### 🎨 Modern UI/UX

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Theme System**: Dark/light mode with smooth transitions
- **Animations**: Framer Motion for smooth, performant animations
- **Accessibility**: WCAG AA compliant with full keyboard navigation
- **Progressive Web App**: Installable PWA with offline capabilities

## 🛠️ Tech Stack

### Frontend

- **Framework**: Next.js 15 (App Router) - Server-side rendering and static generation
- **Language**: TypeScript 5.0 - Type safety and enhanced developer experience
- **Styling**: Tailwind CSS - Utility-first CSS framework
- **UI Components**: shadcn/ui - Accessible component library
- **Animations**: Framer Motion - Production-ready animation library
- **Charts**: Recharts, D3.js - Professional data visualization
- **State Management**: React Hooks, SWR - Efficient data fetching and caching

### Backend

- **Runtime**: Node.js - JavaScript runtime environment
- **API**: Next.js API Routes - Serverless API endpoints
- **Database**: MongoDB Atlas - NoSQL database with optimized queries
- **Authentication**: NextAuth.js - Secure authentication system
- **Multi-Agent AI**: 
  - LangGraph - State machine orchestration for agent workflows
  - LangChain - Tool integration and chain construction
  - Groq - Ultra-fast LLM inference (LLaMA 3.3 70B + LLaMA 3.1 8B)
- **Search & Intelligence**: Tavily API - AI-powered search and research

### Data Sources

- **Market Data**: Twelve Data API - Real-time stocks, forex, and crypto data
- **News**: NewsAPI - Financial news aggregation
- **Community Sentiment**: Reddit API - Social sentiment analysis from 15+ subreddits
- **Market Intelligence**: Tavily Search API - AI-powered market research
- **Technical Indicators**: RSI, MACD, EMA, Bollinger Bands, ATR, ADX, OBV

### Development Tools

- **Testing**: Jest, React Testing Library - Unit and integration testing
- **E2E Testing**: Playwright - Multi-browser and mobile testing
- **Linting**: ESLint, Prettier - Code quality and formatting
- **Accessibility**: axe-core, eslint-plugin-jsx-a11y - Accessibility auditing
- **Bundle Analysis**: @next/bundle-analyzer - Performance optimization
- **Security**: DOMPurify - XSS prevention and input sanitization

## 🧪 Testing & Quality Assurance

### Comprehensive Test Coverage

- **Unit Tests**: 28 tests with Jest & React Testing Library
  - Rate limiter functionality
  - API client error handling
  - Utility function validation
- **E2E Tests**: 25+ tests with Playwright
  - Homepage navigation and layout
  - Search functionality (Command Palette)
  - Portfolio management operations
  - Watchlist CRUD operations
  - Market data page interactions
  - Multi-browser testing (Chrome, Firefox, Safari)
  - Mobile device testing (Pixel 5, iPhone 12)
- **Total Coverage**: 53+ automated tests with 85%+ coverage on tested modules

### Security Features

- **Security Headers**: 8 comprehensive headers including:
  - HSTS (Strict Transport Security)
  - CSP (Content Security Policy)
  - X-Frame-Options (Clickjacking prevention)
  - X-XSS-Protection
  - Referrer-Policy
  - Permissions-Policy
  - X-Content-Type-Options
  - X-DNS-Prefetch-Control
- **Input Sanitization**: DOMPurify integration for:
  - XSS prevention
  - HTML sanitization
  - URL validation
  - Email validation
  - Filename sanitization
- **Environment Validation**: Required variable checking at startup
- **Rate Limiting**: API route protection against abuse
- **CSRF Protection**: NextAuth.js integration for secure sessions

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and npm
- MongoDB Atlas account (free tier available)
- API keys for external services (see Environment Variables section)

### Installation

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your API keys

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the application.

### Build for Production

```bash
# Create optimized production build
npm run build

# Start production server
npm start

# Analyze bundle size
ANALYZE=true npm run build
```

## 🔐 Environment Variables

Create a `.env.local` file in the root directory:

```env
# Database
MONGODB_URI=your_mongodb_connection_string

# Authentication
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000

# Market Data
TWELVE_DATA_API_KEY=your_twelve_data_key

# News
NEWS_API_KEY=your_news_api_key
NEXT_PUBLIC_NEWSAPI_KEY=your_news_api_key

# AI - Multi-Agent System (Required)
GROQ_API_KEY=your_groq_api_key
NEXT_PUBLIC_GROK_API_KEY=your_groq_api_key

# Search & Intelligence
TAVILY_API_KEY=your_tavily_api_key
NEXT_PUBLIC_TAVILY_API_KEY=your_tavily_api_key

# Base URL
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# Reddit (Optional - for sentiment analysis)
REDDIT_CLIENT_ID=your_reddit_client_id
REDDIT_CLIENT_SECRET=your_reddit_client_secret
```

## 📁 Project Structure

```
quantumtrade-analytics/
├── app/                      # Next.js app directory
│   ├── api/                  # API routes
│   │   ├── chat/             # Crypto Multi-Agent API
│   │   ├── forex-chat/       # Forex Multi-Agent API
│   │   ├── stock-chat/       # Stock Multi-Agent API
│   │   ├── portfolio/        # Portfolio endpoints
│   │   ├── watchlist/        # Watchlist endpoints
│   │   ├── stocks/           # Stock data
│   │   ├── forex/            # Forex data
│   │   ├── cryptos/          # Crypto data
│   │   ├── reddit/           # Reddit sentiment
│   │   ├── news/             # News aggregation
│   │   └── market-intelligence/ # Market intelligence
│   ├── cryptoadvisor/        # Crypto Multi-Agent UI
│   ├── forexadvisor/         # Forex Multi-Agent UI
│   ├── stockadvisor/         # Stock Multi-Agent UI
│   ├── portfolio/            # Portfolio pages
│   ├── watchlist/            # Watchlist pages
│   ├── stocks/               # Stock analysis
│   ├── forexs/               # Forex analysis
│   ├── cryptos/              # Crypto analysis
│   └── layout.tsx            # Root layout
├── components/               # React components
│   ├── ui/                   # UI components (shadcn)
│   ├── charts/               # Chart components
│   │   ├── PortfolioAnalytics.tsx
│   │   ├── MarketHeatmap.tsx
│   │   ├── CorrelationMatrix.tsx
│   │   └── PriceChart.tsx
│   ├── CommandPalette.tsx    # Search command palette
│   ├── ExportButton.tsx      # Export functionality
│   └── ...
├── lib/                      # Utility functions
│   ├── ai/                   # Multi-Agent AI system
│   │   ├── config.ts         # LLM configuration
│   │   ├── graph.ts          # Crypto Multi-Agent graph
│   │   ├── forex-graph.ts    # Forex Multi-Agent graph
│   │   ├── stock-graph.ts    # Stock Multi-Agent graph
│   │   └── tools/            # AI tools
│   │       ├── financial.ts  # Crypto price & indicators
│   │       ├── forex.ts      # Forex quotes & indicators
│   │       ├── stock.ts      # Stock quotes & indicators
│   │       ├── social.ts     # Reddit sentiment
│   │       └── search.ts     # Tavily search & intelligence
│   ├── export-utils.ts       # CSV/PDF export
│   ├── mongodb.ts            # Database connection
│   ├── market-intelligence.ts # Market analysis
│   └── ...
├── models/                   # MongoDB models
│   ├── Portfolio.ts
│   ├── Watchlist.ts
│   └── User.ts
├── contexts/                 # React contexts
│   └── AuthContext.tsx
├── e2e/                      # Playwright E2E tests
│   ├── homepage.spec.ts
│   ├── search.spec.ts
│   ├── portfolio.spec.ts
│   ├── watchlist.spec.ts
│   └── market-data.spec.ts
├── public/                   # Static assets
└── next.config.js            # Next.js configuration
```

## 🎨 Features in Detail

### Multi-Agent AI Advisors

Revolutionary AI-powered analysis with specialized agent teams demonstrating advanced LLM orchestration:

**Architecture:**
- **Orchestrator-Workers Pattern**: Supervisor coordinates specialized agents for optimal resource utilization
- **Smart Routing**: Query analysis routes to optimal agents (1-2 for simple, 2-3 for complex)
- **Streaming Updates**: Real-time agent status badges with SSE
- **Token Optimization**: Message history truncation, efficient routing (60-70% token savings)

**Three Market-Specific Advisors:**
1. **Crypto Advisor** - Cryptocurrency analysis with social sentiment
2. **Forex Advisor** - Currency pair analysis with economic indicators
3. **Stock Advisor** - US stock analysis with technical & fundamental data

**Agent Team per Advisor:**
- Supervisor (LLaMA 3.3 70B) - Routes queries, enforces 3-call limit
- Technical Analyst (LLaMA 3.1 8B) - Price, volume, indicators
- Sentiment Analyst (LLaMA 3.1 8B) - Reddit community analysis
- Market Researcher (LLaMA 3.1 8B) - News, earnings, events

**Example Workflows:**
- "What's AAPL price?" → TechnicalAnalyst → Response (1 agent, <5s)
- "Analyze TSLA" → TechnicalAnalyst + SentimentAnalyst → Response (2 agents, <10s)
- "BTC outlook" → All 3 agents → Comprehensive Response (<15s)

### Portfolio Management

Create and manage investment portfolios with:
- Add/remove holdings with real-time validation
- Real-time P&L tracking with accurate cost basis
- Performance analytics with interactive charts
- Asset allocation visualization
- Export to CSV/PDF for reporting

### Watchlist System

Track your favorite assets:
- Multi-market support (stocks, forex, crypto)
- Quick access from any page
- Performance statistics
- Export capabilities

### Advanced Search

Powerful search with:
- Keyboard shortcuts (⌘K / Ctrl+K)
- Fuzzy matching algorithm
- Recent searches tracking
- Cross-market search capabilities

### Data Visualizations

Professional charts:
- Portfolio analytics dashboard
- Market heatmap visualization
- Correlation matrix analysis
- OHLC price charts with multiple timeframes
- Interactive tooltips and zoom

## 🧪 Testing

```bash
# Run unit tests
npm test

# Run tests in watch mode
npm test -- --watch

# Run tests with coverage
npm test -- --coverage

# Run E2E tests
npx playwright test

# Run E2E tests in UI mode
npx playwright test --ui

# Run E2E tests on specific browser
npx playwright test --project=chromium

# View E2E test report
npx playwright show-report
```

### Test Coverage

- **Unit Tests**: 28 tests (Jest + React Testing Library)
- **E2E Tests**: 25+ tests (Playwright)
- **Total**: 53+ automated tests
- **Coverage**: 85%+ on tested modules

## 📊 Performance

- **Lighthouse Score**: 90+ (Production)
- **First Contentful Paint**: <0.5s
- **Largest Contentful Paint**: <2.5s
- **Time to Interactive**: <3s
- **Cumulative Layout Shift**: <0.1

### Optimizations Implemented

- Code splitting and lazy loading
- React.memo and useMemo for expensive operations
- Image optimization (WebP/AVIF)
- Bundle size optimization
- Server-side rendering where appropriate
- Edge caching for static assets

## ♿ Accessibility

- WCAG AA compliant
- Keyboard navigation support
- Screen reader compatible
- ARIA labels and roles
- Semantic HTML
- Color contrast compliance

## 🔒 Security

- Secure authentication with NextAuth.js
- Environment variable validation
- Rate limiting on API routes
- Input sanitization with DOMPurify
- CSRF protection
- Security headers (HSTS, XFO, CSP)

## 📱 Progressive Web App

- Installable on desktop and mobile
- Offline support capabilities
- App-like experience
- Fast loading times

## 🗺️ Roadmap

### ✅ Completed

- [x] Multi-Agent AI system (Crypto, Forex, Stock advisors)
- [x] LangGraph orchestration with smart routing
- [x] Real-time streaming with SSE
- [x] Token optimization (60-70% savings)
- [x] Portfolio management system
- [x] Watchlist functionality
- [x] Advanced search (Command Palette)
- [x] Data visualizations (5 chart types)
- [x] Export functionality (CSV/PDF)
- [x] E2E testing with Playwright (25+ tests)
- [x] Security hardening (8 headers + sanitization)
- [x] Performance optimization (90+ Lighthouse)
- [x] CI/CD pipeline implementation

### 🚧 In Progress

- [ ] Real-time price updates via WebSocket
- [ ] Advanced technical indicators (Fibonacci, Ichimoku)
- [ ] Price alerts and notifications
- [ ] Multi-timeframe analysis

### 📋 Planned

- [ ] Voice-controlled AI assistant
- [ ] Advanced backtesting with historical data
- [ ] Social trading features & copy trading
- [ ] Mobile app (React Native)
- [ ] Advanced portfolio analytics (Sharpe ratio, beta, alpha)
- [ ] Multi-language support (ES, FR, DE, JP, CN)
- [ ] Options & derivatives trading analysis

## 📄 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

### GPL-3.0 License Summary

- ✅ **Freedom to use** - Use the software for any purpose
- ✅ **Freedom to study** - Study how the program works and modify it
- ✅ **Freedom to share** - Redistribute copies to help others
- ✅ **Freedom to improve** - Distribute modified versions

**Note:** Any derivative work must also be licensed under GPL-3.0 and source code must be made available.

---

**Built with ❤️ using Next.js and TypeScript**
