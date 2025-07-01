# SoulAtlas

SoulAtlas is a personal, interactive web application for visually mapping and exploring your internal experience—including personality parts, core beliefs, emotional and behavioral patterns, life timeline events, and relationships. It is designed to support personal growth and self-understanding through insightful, engaging, and evolving visualizations.

## Features

- Interactive Parts Map: Visualize internal parts and their connections
- Core Beliefs Tree: Explore hierarchical beliefs and their influence
- Emotion-Behavior Cycles: See patterns of emotional triggers and responses
- Life Timeline: Map significant events and associated parts/beliefs
- Relationship Maps: Visualize key relationships and their impact
- Insight Notes: Add personal annotations to nodes or connections

## Project Goals

SoulAtlas is not just a "parts map" app—it's a flexible, expandable self-exploration tool that grows alongside your personal journey. The app is designed to be modular, extensible, and privacy-focused.

## Technology Stack

- **Frontend:** React (TypeScript)
- **Build Tool:** Vite
- **Styling:** Tailwind CSS + ShadCN UI components
- **Data Storage (MVP):** Static JSON files
- **Deployment:** Vercel or self-hosted Ubuntu server (PM2)

## Project Phases

See `/docs` for detailed breakdowns. High-level phases:

1. **Initial Setup & Scaffolding:** Project structure, styles, and data schemas
2. **Implement Visualizations:** Build and integrate core visualizations (Parts Map, Beliefs Tree, Timeline, etc.)
3. **User Data Input & Backend:** Forms/wizards for user data, backend for persistence (future)
4. **Guided Assessment Integration:** Psychological quizzes and adaptive wizards (future)

## Getting Started

1. Clone the repo
2. Install dependencies with your preferred package manager (e.g., `pnpm install`)
3. Set up Tailwind CSS and ShadCN UI (see `/docs/phase-1-setup-and-scaffolding.md`)
4. Start the development server:
   ```sh
   pnpm dev
   ```

## Contributing

This project is personal and evolving, but contributions and ideas are welcome! Please see the `/docs` directory for project structure and roadmap.

## License

MIT (see LICENSE file)

---

SoulAtlas is a tool for self-understanding and growth. Your data is yours—privacy and security are a top priority as the project evolves.
