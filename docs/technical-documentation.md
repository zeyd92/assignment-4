# Technical Documentation

## Implemented Features
- Project cards with images, descriptions, and toggleable details.
- Added third project (Gym Workout Program Web App) with full layout.
- GitHub API integration to load the latest 5 repositories (sorted by date).
- Project search filter for real-time filtering.
- Contact form with full validation (email, phone, empty fields).
- Dark/Light theme toggle stored in LocalStorage.
- Greeting system that updates dynamically.
- Floating contact button with responsive tooltip.
- Compressed images and optimized layout for performance.
- Mobile-responsive design:
  - Project cards stack vertically.
  - Images auto-resize for small screens.
  - Navbar spacing fixed to prevent overlap with greeting.
  - Buttons centered with better touch spacing.
- Code cleanup:
  - Removed unused JSON files.
  - Removed unnecessary functions and logs.
  - Simplified logic and added small, clear comments.

## How to Run
1. Clone or download the project.
2. Open `index.html` directly in the browser (Live Server recommended).
3. No backend or build tools required.
4. Fully works offline — all dynamic features use JavaScript only.

## Deployment
The website is deployed using **Vercel** for fast static hosting.  
It automatically builds and serves the `index.html` and static assets.  

**Live Link:** [Open Website](https://assignment-4-gamma-swart.vercel.app)



## Future Improvements
- Backend service for the contact form (Node.js or Firebase).
- Loading animation for GitHub API requests.
- Additional project categories and filtering options.
- Smoother transitions for theme toggling and search animations.
- Profile section with more user interaction.
- Saving greeting name from login form instead of manual entry.
