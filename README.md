# First Electric - Review Website

A customer review display website for First Electric LLC, featuring reviews from Google and Yelp.

## Features

- Display customer reviews with filtering and sorting
- Mobile-responsive design with prominent "Leave a Review" button
- Review submission modal with star rating
- Automatic redirect to Google Reviews for 5-star ratings
- Contact form for feedback on 4-star or lower ratings
- Custom gold-themed UI matching First Electric branding

## Setup

This is a static website that can be hosted on GitHub Pages or any static hosting service.

### Local Development

1. Simply open `index.html` in a web browser
2. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

### GitHub Pages Deployment

1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select the branch (usually `main` or `master`)
4. Select the root directory
5. Save

The site will be available at `https://[username].github.io/[repository-name]`

## File Structure

```
review-website/
├── index.html              # Main HTML file
├── Logo.svg                # Company logo
├── data/
│   └── exported-reviews.json  # Review data
├── production/             # Production builds (if needed)
└── README.md
```

## Customization

- **Google Review URL**: Update the `GOOGLE_REVIEW_URL` constant in `index.html`
- **Logo**: Replace `Logo.svg` with your logo file
- **Review Data**: Update `data/exported-reviews.json` with new reviews

## License

© 2025 First Electric LLC. All rights reserved.

