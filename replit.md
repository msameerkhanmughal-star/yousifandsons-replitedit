# Yousif & Sons Rent A Car

## Overview
A car rental management application built with React, Vite, and Firebase. Imported from Lovable platform. Features include booking management, vehicle tracking, invoice generation, and PWA support.

## Recent Changes
- 2026-02-10: Imported from Lovable to Replit
  - Updated Vite config: port 8080 -> 5000, host 0.0.0.0, allowedHosts: true
  - Removed lovable-tagger dependency from vite config
  - Configured static deployment (dist folder)

## Project Architecture
- **Frontend**: React 18 + TypeScript + Vite 5
- **Styling**: Tailwind CSS + shadcn/ui components
- **Routing**: react-router-dom v6
- **State**: TanStack React Query v5
- **Backend**: Firebase (auth, database)
- **PWA**: vite-plugin-pwa with workbox
- **PDF**: jspdf + html2canvas

## Key Files
- `src/App.tsx` - Main app with routing
- `src/hooks/useAuth.tsx` - Firebase authentication
- `src/components/Layout.tsx` - App layout wrapper
- `vite.config.ts` - Vite configuration (port 5000)
- `index.html` - Entry HTML with PWA meta tags

## User Preferences
- (none recorded yet)
