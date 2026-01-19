# Grantha-Kosa

**ग्रन्थकोश** (Grantha-Kosa) - Sanskrit for "treasury of books"

A personal web application for managing your book inventory, tracking your reading journey, and organizing your literary collection.

## Overview

Grantha-Kosa is a comprehensive book inventory manager that helps you maintain and organize your personal library across three key categories:

- **Read** - Books you've completed
- **Currently Reading** - Books you're actively reading
- **Want to Read** - Your reading wishlist

## Features

- Track books across different reading states
- Organize and categorize your personal library
- Search and filter your book collection
- Maintain reading history and progress
- Clean, intuitive user interface

## Project Structure

This is a monorepo containing all components of the Grantha-Kosa application:

```
grantha-kosa/
├── packages/
│   ├── frontend/          # Web application frontend
│   ├── backend/           # API server and business logic
│   └── shared/            # Shared types and utilities
├── README.md
└── package.json
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Database (PostgreSQL/MongoDB recommended)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd grantha-kosa
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env
```

4. Start the development server:
```bash
npm run dev
```

## Tech Stack

- **Frontend**: [Your chosen framework - React, Vue, Svelte, etc.]
- **Backend**: [Your chosen framework - Express, NestJS, etc.]
- **Database**: [Your chosen database]
- **Language**: TypeScript

## Development

### Running Tests

```bash
npm run test
```

### Building for Production

```bash
npm run build
```

### Linting

```bash
npm run lint
```

## Contributing

This is a personal project, but suggestions and feedback are welcome.

## License

[Yet to be chosen]

## Acknowledgments

The name **Grantha-Kosa** (ग्रन्थकोश) derives from Sanskrit:
- **Grantha** (ग्रन्थ) - book, text, literary work
- **Kosa** (कोश) - treasury, collection, repository

Together, they form "a treasury of books" - a fitting name for a personal library management system.

---

*Built with ❤️ for book lovers*