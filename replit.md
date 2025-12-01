# You Can Do It Health Coaching

## Project Overview
This is a static website built with Hugo, a fast static site generator. The site uses the Ananke theme and is designed for "You Can Do It Health Coaching."

## Project Structure
- **hugo.toml**: Main configuration file for Hugo
- **archetypes/**: Templates for new content
- **themes/ananke/**: The Ananke theme (cloned from GitHub)
- **content/**: All page content files
- **public/**: Generated static site output (excluded from git)
- **resources/**: Hugo resource cache (excluded from git)
- **static/**: Static assets including images and custom CSS

## Current Site Pages
- **Homepage** (_index.md) - Hero banner with welcome message
- **Meet Your Coach** - Professional page with coach image
- **Free Discovery Call** (book-now.md) - Calendly booking integration
- **Contact** - Contact information
- **Disclaimer** - Legal disclaimer
- **Privacy Policy** - Privacy policy

## Navigation Setup

### Header Navigation (Main Menu)
- Meet Your Coach
- Newsletter (links to Mailchimp signup)
- Free Discovery Call

### Footer Navigation
- Contact
- Disclaimer
- Privacy Policy
- Instagram (http://instagram.com/youcandoithealth)
- Facebook (https://www.facebook.com/profile.php?id=61583343905186)
- TikTok (http://tiktok.com/@youcandoithealth)
- YouTube (https://www.youtube.com/@youcandoithealth)

## Development Setup
- **Language/Framework**: Hugo (v0.147.3+extended)
- **Theme**: Ananke
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

## Customizations
- **Custom CSS** (static/css/custom.css):
  - Widened content area to 90% of screen width for better readability
  - Increased max-width constraints for better spacing
- **Hero Images**:
  - Homepage: Fitness/wellness banner image
  - Meet Your Coach: Professional portrait image
- **Integrations**:
  - Calendly widget on Free Discovery Call page
  - Mailchimp newsletter signup link

## Recent Changes (December 1, 2025)
1. Set up Hugo in Replit environment
2. Cloned Ananke theme from GitHub
3. Configured Hugo server workflow on port 5000
4. Added hero images to homepage and Meet Your Coach page
5. Widened content margins for better readability
6. Removed dates from all pages
7. Updated header navigation to show only: Meet Your Coach, Newsletter, Free Discovery Call
8. Added comprehensive footer navigation with links to Contact, Disclaimer, Privacy Policy, and social media
9. Integrated Calendly booking widget on Free Discovery Call page
10. Configured static site deployment

## Notes
- The site is ready for both development and production deployment
- Custom CSS is used to override Ananke theme's default narrow width
- Calendly booking link needs to be configured with actual scheduling URL
- Mailchimp newsletter link needs to be configured with actual signup URL
