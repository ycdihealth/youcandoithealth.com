# You Can Do It Health Coaching

## Project Overview
This is a static website built with Hugo, a fast static site generator. The site uses the Ananke theme and is designed for "You Can Do It Health Coaching."

## Project Structure
- **hugo.toml**: Main configuration file for Hugo
- **archetypes/**: Templates for new content
- **themes/ananke/**: The Ananke theme (cloned from GitHub)
- **public/**: Generated static site output (excluded from git)
- **resources/**: Hugo resource cache (excluded from git)

## Development Setup
- **Language/Framework**: Hugo (v0.147.3+extended)
- **Theme**: Ananke (from https://github.com/theNewDynamic/gohugo-theme-ananke.git)
- **Development Server**: Runs on port 5000, bound to 0.0.0.0
- **Build Command**: `hugo --minify`

## Workflow Configuration
The "Hugo Server" workflow runs the development server with:
- Host: 0.0.0.0 (to work with Replit's proxy)
- Port: 5000
- BaseURL: / (for proper routing in Replit environment)
- Fast render disabled for reliability

## Deployment Configuration
- **Type**: Static site deployment
- **Build Command**: `hugo --minify`
- **Public Directory**: `public/`
- **Deployment Target**: Static files from the `public` directory after build

## Recent Changes
- 2025-11-23: Initial project setup in Replit environment
  - Installed Hugo via Nix package manager
  - Cloned Ananke theme into themes/ananke directory
  - Configured workflow to run Hugo server on port 5000
  - Created .gitignore for Hugo-specific files
  - Configured static deployment settings
  - Verified site loads correctly in Replit preview

## Notes
- The theme is cloned directly (not as a git submodule) due to Replit git restrictions
- Hugo server is configured to work with Replit's proxy infrastructure
- The site is ready for both development and deployment
