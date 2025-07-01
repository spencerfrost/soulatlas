
# SoulAtlas — Project Overview

## Project Purpose

Create a personal, interactive web application to visually map and explore various aspects of the user’s internal experience — including personality parts, core beliefs, emotional and behavioral patterns, life timeline events, and relationships. The goal is to support personal growth and self-understanding by providing insightful, engaging, and evolving visualizations that users can interact with and build upon over time.

This is not exclusively a “parts map” app; rather, it is a flexible, expandable self-exploration tool designed to grow alongside the user’s therapeutic or personal growth journey.

## Initial Goals (MVP)

- Develop a responsive React frontend with Vite as the build tool.
- Display a foundational Parts Map visualization: interactive nodes representing internal parts, showing their connections and key attributes.
- Support additional visualization types such as:
  - Core Beliefs Tree
  - Emotion and Behavior Cycle Charts
  - Life Timeline with mapped parts and events
- Store initial data as static JSON files representing the user’s personal internal map.
- Implement basic interactive features:
  - Click nodes to see details
  - Highlight connections between parts
  - Timeline navigation
- Use Tailwind CSS and ShadCN components for styling and UI consistency.
- Deploy to Vercel or self-host on an Ubuntu server with PM2 (optional).

## Technology Stack

- **Frontend Framework:** React (with TypeScript recommended)
- **Build Tool:** Vite
- **Styling:** Tailwind CSS + ShadCN UI components
- **Data Storage (MVP):** Static JSON files
- **Deployment:** Vercel or self-hosted Ubuntu server (using PM2 or similar process manager)
- **Optional:** Backend + database (for future phases)

## Project Phases

### Phase 1: Static Visualizations & Basic Interaction (MVP)

- Build core visualizations and data structures based on static JSON representing your therapy journey.
- Implement interactive features to explore parts, beliefs, timelines, and relationships.
- Design a calming, clean UI consistent with therapeutic themes.

### Phase 2: Enhanced UI and Additional Visualizations

- Improve UX/UI with richer interactions, animations, and filtering options.
- Add more types of visualizations as conceptualized during therapy/personal growth.
- Create links between visualizations for seamless exploration.

### Phase 3: User Data Input & Backend Support

- Create user input forms/wizards to allow users to enter known information about themselves.
- Transition from static JSON files to a database backend to persist user profiles and data.
- Add user authentication (optional for personal use, necessary for multi-user).
- Ensure data privacy and security best practices.

### Phase 4: Guided Psychological Assessment Integration

- Integrate or develop psychological quizzes and scales to help users discover parts and beliefs they may not yet be aware of.
- Collaborate with mental health professionals to validate assessments.
- Build adaptive wizards that convert quiz results into personalized visualizations.
- Handle ethical considerations and data sensitivity with care.

## Potential Features & Visualizations

- **Interactive Parts Map:** Nodes representing internal parts, linked by emotional or behavioral relationships.
- **Core Beliefs Tree:** Hierarchical visualization of core beliefs and their influence on parts/emotions.
- **Emotion-Behavior Cycles:** Flow diagrams illustrating patterns of emotional triggers and responses.
- **Life Timeline:** Chronological mapping of significant life events with associated parts or beliefs.
- **Relationship Maps:** Visualizing key relationships and their impact on internal states.
- **Insight Notes:** Allow users to add personal annotations to nodes or connections.

## Considerations

- Prioritize privacy and security of user data, especially in phases involving personal or clinical information.
- Focus on simplicity and accessibility — users should not require psychological expertise to engage meaningfully.
- Design the app to be extensible and modular, allowing easy addition of new visualization types and data sources.
- Consider building a library of reusable visualization components for flexibility.

## Next Steps

1. Set up the project repo with Vite + React + Tailwind + ShadCN.
2. Define JSON schemas for parts, beliefs, timeline events, etc., based on your personal data.
3. Begin building MVP visualizations focusing on the Parts Map.
4. Iterate on UI/UX based on personal feedback and testing.
