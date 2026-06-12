# FSLR Official Gamer Skill Ranking

A static HTML leaderboard for the FSLR (Fully Sanctioned Legitimate Ranking) gaming community.

## Features

- 📊 Dynamic leaderboard with player rankings
- 🎮 Multi-game skill tracking (CS2, Valorant)
- 📈 FOGSR™ (Fully Official Gamer Skill Rating) system
- 🎥 Embedded highlight videos
- 📱 Responsive design

## Analytics Setup

This project uses **Vercel Web Analytics** and **Vercel Speed Insights** for comprehensive monitoring:

### Web Analytics
- **Purpose**: Tracks visitor metrics, page views, referrers, and demographics
- **Implementation**: Cookie-free, privacy-friendly tracking via script tags
- **Documentation**: https://vercel.com/docs/analytics

### Speed Insights
- **Purpose**: Monitors Core Web Vitals and performance metrics
- **Implementation**: Real-time performance monitoring
- **Documentation**: https://vercel.com/docs/speed-insights

Both are configured in `index.html` using the official Vercel script tags for static HTML projects.

## Deployment

This site is optimized for deployment on Vercel:

1. Push to your GitHub repository
2. Connect to Vercel
3. Vercel will automatically detect the static HTML setup
4. Analytics and Speed Insights will be automatically enabled on deployment

## Local Development

To run locally:

```bash
# Using Python's built-in HTTP server
python -m http.server 8000

# Then open http://localhost:8000/index.html
```

Or use any static file server of your choice.

## Project Structure

```
FSLR gaming leaderboard/
├── index.html          # Main HTML file with embedded styles and scripts
├── package.json        # Project metadata and scripts
├── vercel.json        # Vercel deployment configuration
└── README.md          # This file
```

## Configuration Files

- **package.json**: Documents project metadata and provides npm scripts
- **vercel.json**: Configures Vercel's static site deployment
- **index.html**: Contains all HTML, CSS, and JavaScript inline

## License

MIT
