# Docura

Docura is a SaaS-style document workspace for organizing, processing, and preparing PDF-related workflows. The current phase focuses on the professional application foundation rather than production document-processing engines.

## Current Phase

Phase 1 establishes the application shell, design system, responsive layout, navigation, reusable UI foundations, placeholder routes, environment configuration, and documentation structure. Advanced PDF processing, OCR, AI document intelligence, authentication, billing, and storage backends are intentionally not implemented yet.

## Technology Stack

- React with TypeScript
- Vite for development/build tooling
- React Router for initial navigation
- CSS tokens and a centralized design system
- Lucide icons for consistent UI iconography

## Installation

```bash
npm install
```

## Development

```bash
npm run dev
```

## Environment Configuration

Create a local environment file from the example:

```bash
cp .env.example .env
```

The application is prepared for future configuration of API endpoints, database access, AI service keys, PDF service settings, and application URL values. Do not commit credentials or secrets.

## Project Structure

```text
src/
  components/
    layout/
    ui/
  config/
  hooks/
  pages/
  services/
  styles/
  types/
```

## Planned Future Phases

- Phase 2: document model, dashboard widgets, upload pipeline, and API service contracts
- Phase 3: PDF processing UI and backend service integration
- Phase 4: AI-assisted document workflows and workflow automation
- Phase 5: production security, billing, and business operations foundations
