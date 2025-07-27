# System Patterns

## System Architecture
- Static site architecture using HTML and CSS
- Two main pages: index.html (strategic plan) and infographic.html (data visualization)

## Key Technical Decisions
- Use of localStorage for persistent audio player state
- Dropbox for audio file hosting to resolve CORS issues

## Design Patterns in Use
- Modular navigation: clear links between main content and infographic
- Persistent UI component: floating audio player with cross-page state

## Component Relationships
- Audio player is loaded on both main and infographic pages, sharing state via localStorage
- Navigation links allow seamless movement between pages

## Critical Implementation Paths
- Audio player initialization and state restoration on page load
- Navigation logic for CTA and back links
- Asset hosting and CORS handling for embedded media
