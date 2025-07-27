# Active Context

## Current Work Focus
- Building and refining a static website for Seedling Bio
- Ensuring seamless navigation between main content and infographic
- Implementing and debugging a persistent floating audio player

## Recent Changes
- Added navigation links between index.html and infographic.html
- Implemented cross-page persistent audio player with Dropbox hosting
- Attempted to update audio player to require user interaction for playback (mobile autoplay policy fix)
- Rolled back autoplay fix after user feedback (restored auto-resume logic)

## Next Steps
- Continue improving user experience and accessibility
- Monitor for bugs or feedback from users

## Active Decisions and Considerations
- Use of localStorage for audio player state persistence
- Dropbox for audio hosting due to CORS issues with Google Drive
- Mobile autoplay restrictions require careful handling; current logic prioritizes desktop/mobile consistency

## Important Patterns and Preferences
- Static HTML/CSS for simplicity and GitHub Pages compatibility
- Emphasis on clarity, accessibility, and non-intrusive enhancements

## Learnings and Project Insights
- CORS and asset hosting can impact embedded media reliability
- User preferences (e.g., audio player visibility) should persist across sessions
- Mobile browsers may require different UX for audio playback; not all fixes work as expected
