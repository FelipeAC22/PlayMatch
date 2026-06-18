# PlayMatch

PlayMatch is designed to connect gamers quickly and efficiently through intelligent matchmaking. User preferences are analyzed before matches are suggested.

## Team

- Felipe Antunes
- João Borba

## Technologies Used

- **React** – Used for building the front-end interface, providing a dynamic and responsive user experience.  
- **Node.js + NestJS + TypeScript** – Used for back-end development, ensuring scalable server-side logic and type safety.  
- **PostgreSQL** – Used as the database to store user profiles, matches, and reputation scores.  
- **Git + GitHub** – Used for version control and collaborative development.  
- **Vercel + Render** – Used for deployment, making the application accessible online.

## Features

- User profiles are synchronized with Steam API to automatically display owned games and playtime.  
- Matches are generated based on preferences, availability, and play style.  
- Reputation scores are assigned after each interaction to ensure trust and reliability.  
- Filters are applied to help users find teammates by genre, skill level, or platform.  

## Installation

1. Clone the repository to your local machine.  
   ```bash
   git clone <repo-url>
   npm install

## How to Run

```bash
npm run start
```
## Changelog

### v1.0.0
The repository project was created.
The introduction slide was created.
The objective section was added.

## Roadmap

Dark mode will be added in the next release.

MatchMaking will be implemented to improve the experience.

## Rules & Requirements

Invalid input must be rejected by the system.

User passwords must be encrypted before storage.

Reputation scores must be updated after each match to maintain fairness
