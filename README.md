# Digital Business Card

A modern, responsive web application for creating and downloading digital business cards with QR code functionality.

## Features

- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Animated Header**: Beautiful wave pattern with color transitions
- **Profile Integration**: Circular profile image display
- **Contact Information**: Phone, email, and LinkedIn profile links
- **QR Code Generation**: Auto-generates QR codes for download version
- **One-Click Download**: Downloads business card as PNG image

## Setup Instructions

1. **Clone or Download** the project files
2. **Add Profile Image**: Replace `assets/profile.jpg` with your profile picture
3. **Update Information**: Edit the contact details in `index.html`:
   - Full name
   - Phone number
   - Email address
   - LinkedIn profile URL

## File Structure

```
digital-business-card/
├── index.html          # Main HTML structure
├── css/
│   └── styles.css      # All styling and animations
├── js/
│   └── script.js       # JavaScript functionality
├── assets/
│   └── profile.jpg     # Profile image (replace with yours)
└── README.md           # This file
```

## Customization

### Colors
- Primary: `#003C43`
- Secondary: `#005F69`
- Hover: `#77B0AA`
- Background: `#FFFFFF`

### Personal Information
Update these elements in `index.html`:
- `#fullName`: Your full name
- `#phoneNumber`: Your phone number
- `#emailAddress`: Your email address
- `#linkedinProfile`: Your LinkedIn URL

## Dependencies

- **QRCode.js**: Automatically loaded via CDN for QR code generation
- **Modern Browser**: Supports HTML5 Canvas and ES6+ features

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Deployment

### Local Development
1. Open `index.html` in a web browser
2. No server required for basic functionality

### Web Hosting
1. Upload all files to your web server
2. Ensure proper MIME types for assets
3. Test QR code functionality with HTTPS

## Technical Details

- **Canvas API**: Used for generating downloadable business card
- **QR Code Library**: Converts contact info to scannable QR codes
- **CSS Animations**: Smooth wave header transitions
- **Responsive Grid**: Flexible layout for all screen sizes

## Troubleshooting

**QR Codes not generating?**
- Check internet connection (CDN dependency)
- Ensure HTTPS for production deployment

**Profile image not displaying?**
- Verify image path in `assets/profile.jpg`
- Check image format (JPG, PNG, WebP supported)

**Download not working?**
- Modern browser required
- Check browser's download permissions