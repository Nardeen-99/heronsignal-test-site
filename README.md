# FlowPilot - HeronSignal Test Environment

FlowPilot is a lightweight, zero-backend React SaaS application built specifically for testing **HeronSignal**, an AI Website Observability platform.

## Features & Test Scenarios

### Key Funnels
1. **Acquisition Funnel**: Landing (`/`) -> Signup (`/signup`) -> Dashboard (`/dashboard`)
2. **Core App Interactions**: Dashboard -> Create Project -> Create Task -> Complete Task
3. **Analytics Usage**: Navigation -> Change Date Filters (7 / 30 / 90 days)

### Observability Testing (`/dev-tests`)
- JavaScript runtime error generation
- Unhandled promise rejection triggering
- Failed network requests (500 and 404 responses)
- High latency/slow network request testing

## Local Development

```bash
# Install dependencies
npm install

# Run local development server
npm run dev

# Create static production build
npm run build
```
