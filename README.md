# Sportsbook Syndicate Tycoon

**A management simulation game where you build and run an underground sports betting empire.**

[![GitHub](https://img.shields.io/badge/GitHub-ftmedia22-blue)](https://github.com/ftmedia22/sportsbook-tycoon)
[![Documentation](https://img.shields.io/badge/docs-comprehensive-green)](#documentation-structure)

## Overview

Sportsbook Syndicate Tycoon is a management simulation game that puts you in control of an underground sportsbook operation. Make critical decisions about odds, manage risk exposure, hire analysts, and grow your betting empire while navigating the challenges of the sports betting world.

## Key Features

- **Dynamic Sports Betting Simulation**: Real-time odds management across MLB, NBA, NFL, and NHL
- **AI-Driven Bettor Behavior**: Sophisticated bettor personas with unique betting patterns and risk profiles
- **Risk Management Systems**: Advanced exposure calculations and hedge strategies
- **Analyst & Staff Management**: Hire and develop analysts to improve your odds and predictions
- **Meta Progression**: Long-term progression systems with unlockables and upgrades
- **Narrative Arcs**: Engaging storylines featuring rivals, analysts, and high-stakes scenarios

## Project Status

**Current Phase**: Documentation & Design
**Type**: Game Design Documentation
**Format**: Markdown-based developer documentation

This repository contains comprehensive design documentation structured for AI-assisted development and implementation.

## Documentation Structure

The project is organized into 7 main documentation categories:

### 📊 High-Level Design (`high_level/`)
Core concept, gameplay loop, and product requirements
- `concept_pitch.md` - Game concept and pitch overview
- `core_loop.md` - Core gameplay loop mechanics
- `meta_progression.md` - Long-term progression systems
- `product_requirements.md` - MVP and feature requirements

### 🎮 Systems Design (`systems/`)
Detailed gameplay systems and mechanics (11 documents)
- Sports-specific systems (MLB, NBA, NFL, NHL)
- Analyst and bettor management
- Economy and monetization design
- Risk management systems
- Missions and live operations
- Predictive models overview

### 🧮 AI & Mathematics (`ai_math/`)
Odds calculation, AI behavior, and mathematical models
- `math_overview.md` - Mathematical framework
- `odds_pricing.md` - Odds calculation systems
- `exposure_calcs.md` - Risk exposure calculations
- `bettor_ai_behavior.md` - AI decision-making logic
- `bettor_personas.md` - Bettor personality types

### 🎨 UI/UX Design (`ui_ux/`)
Screen designs, user flows, and interface principles
- Screen specifications (Dashboard, Lines, Risk Room, HQ, Analyst Room, Model Lab)
- `ux_principles.md` - Design principles and guidelines
- `wireflows.md` - User flow diagrams

### 🏗️ Backend Architecture (`backend/`)
Technical architecture, APIs, and data models
- `architecture_overview.md` - System architecture
- `services_overview.md` - Service layer design
- `data_models.md` - Database schema and models
- API specifications (Auth, Gameplay, Progression)

### 📖 Narrative Design (`narrative/`)
Story arcs and character development
- `narrative_overview.md` - Narrative framework
- Character arcs (Analysts, Bettors, HQ, Rivals)

### 🚀 Production (`production/`)
Roadmap, QA, branding, and competitive analysis
- `roadmap.md` - Development roadmap
- `qa_telemetry.md` - Testing and analytics strategy
- `branding.md` - Brand identity and guidelines
- `competitive_analysis.md` - Market analysis
- `pitch_outline.md` - Pitch deck structure

## Technology Stack

### Planned Architecture
- **Frontend**: TBD (React/Next.js recommended for web)
- **Backend**: TBD (Node.js/Python recommended)
- **Database**: TBD (PostgreSQL for relational data, Redis for caching)
- **APIs**: RESTful or GraphQL architecture
- **Real-time**: WebSocket support for live odds updates

## Getting Started

### For Developers

This project is currently in the documentation phase. To get started:

1. **Clone the repository**
   ```bash
   git clone https://github.com/ftmedia22/sportsbook-tycoon.git
   cd sportsbook-tycoon
   ```

2. **Explore the documentation**
   Start with `index.md` for an overview, then dive into specific areas based on your focus:
   - Game designers: Start with `high_level/` and `systems/`
   - Engineers: Review `backend/` and `ai_math/`
   - UI/UX designers: Explore `ui_ux/`
   - Writers: Check out `narrative/`

3. **AI-Assisted Development**
   Documentation is structured for AI tools (Claude, GPT-4, etc.) to load 1-3 files at a time and generate implementation code without being overwhelmed.

### For AI Assistants

When implementing features:
1. Load relevant documentation files from the appropriate category
2. Reference cross-category files as needed (e.g., backend + systems)
3. Each file is scoped to be consumed independently
4. Follow the architecture patterns outlined in `backend/architecture_overview.md`

## Project Metrics

- **Total Documentation Files**: 45 markdown files
- **Documentation Categories**: 7 major sections
- **Sports Covered**: 4 (MLB, NBA, NFL, NHL)
- **Lines of Documentation**: ~147 lines (structured headers + content)
- **Architecture**: Modular, AI-friendly documentation structure

## Documentation Philosophy

Each documentation file is:
- **Focused**: Single-topic scope for clarity
- **Modular**: Can be read independently or combined
- **AI-Optimized**: Structured for AI-assisted code generation
- **Implementation-Ready**: Contains actionable technical specifications

## Roadmap

### Phase 1: Foundation (Current)
- Comprehensive design documentation
- Technical architecture planning
- System design specifications

### Phase 2: Core Implementation
- Backend infrastructure setup
- Database schema implementation
- Basic API endpoints

### Phase 3: Game Systems
- Odds calculation engine
- Bettor AI implementation
- Risk management systems

### Phase 4: Frontend & Polish
- UI implementation
- User experience refinement
- Testing and optimization

## Contributing

This project is currently in the design phase. Contributions to documentation are welcome.

### Contribution Guidelines
1. Maintain the modular documentation structure
2. Keep files focused and AI-friendly (1-3 file loading capacity)
3. Follow existing naming conventions
4. Update `index.md` when adding new documentation categories

## Author

**Brian Pyatt**
Email: brianpyatt@ftmedia.com
Organization: FT Media

## License

Copyright (c) 2025 FT Media. All rights reserved.

## Codebase Analysis Summary

### Architecture Assessment
- **Type**: Documentation-Driven Design Project
- **Structure**: 7-category modular documentation system
- **Files**: 45 markdown files organized by domain
- **Complexity**: Medium (comprehensive design, pre-implementation phase)

### Strengths
- Well-organized hierarchical documentation structure
- Clear separation of concerns across categories
- AI-friendly file scoping for assisted development
- Comprehensive coverage of game systems, backend, and UX

### Key Design Principles
1. **Modular Documentation**: Each file is independently readable
2. **Cross-Reference Support**: Files can be combined for complex implementations
3. **Implementation-Ready**: Technical specifications suitable for direct coding
4. **Scalable Architecture**: Designed to support iterative development

### Next Steps for Implementation
1. **Backend Setup**: Initialize server architecture based on `backend/architecture_overview.md`
2. **Database Design**: Implement schemas from `backend/data_models.md`
3. **Core Math Engine**: Build odds and exposure calculators from `ai_math/`
4. **API Development**: Implement endpoints specified in `backend/api_*.md` files
5. **Frontend Scaffold**: Create UI based on specifications in `ui_ux/`

---

**Documentation Version**: 2.0
**Last Updated**: December 2025
**Repository**: https://github.com/ftmedia22/sportsbook-tycoon
