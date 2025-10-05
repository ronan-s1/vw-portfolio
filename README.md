# Vadim - Cinematographer Portfolio

A clean, modern one-page portfolio website for showcasing videography and cinematography work.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Dark theme with elegant gold accents perfect for showcasing visual work
- **Smooth Animations**: Scroll-based animations and smooth transitions
- **Embedded YouTube Videos**: 4 featured videos directly embedded from YouTube
- **Contact Form**: Easy-to-use contact form for potential clients
- **Mobile Navigation**: Hamburger menu for mobile devices

## File Structure

```
vadim/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # This file
```

## Usage

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize Content**: 
   - Edit the About section text in `index.html`
   - Change video URLs by updating the YouTube embed links
   - Update contact information (email and phone)
3. **Customize Styling**:
   - Edit `styles.css` to change colors, fonts, or layout
   - Current color scheme uses:
     - Primary: Dark black (#0a0a0a)
     - Accent: Gold (#e8b923)
     - You can change these in the `:root` variables

## Sections

1. **Hero**: Eye-catching landing section with call-to-action
2. **About**: Personal introduction and background
3. **Videos**: 4 embedded YouTube videos in a 2x2 grid
4. **Contact**: Contact form with email and phone information

## Contact Information

Current contact details in the site:
- **Email**: vwoinski2014@gmail.com
- **Phone**: 087 467 5340

## Customization Tips

### Changing Videos
To change a video, replace the YouTube video ID in the iframe src attribute:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
```

### Contact Form
The form currently shows an alert. To make it functional, connect it to a backend service like:
- Formspree
- EmailJS
- Netlify Forms
- Your own backend API

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Playfair Display & Inter)

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to customize and use this template for your portfolio!
