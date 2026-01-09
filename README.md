# Adare Restaurant Landing Page

A modern, elegant landing page for Adare Restaurant, an Irish dining establishment located in County Limerick, Ireland. This project showcases a clean, single-page design highlighting the restaurant's atmosphere, location, and reservation options.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Browser Compatibility](#browser-compatibility)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Overview

This landing page was designed to provide visitors with an immediate sense of Adare Restaurant's brand identity and dining experience. The site features a full-screen background image that immerses users in the restaurant's ambiance, complemented by clean typography and intuitive navigation.

The design philosophy emphasizes simplicity and elegance, allowing the restaurant's personality to shine through without overwhelming visitors with unnecessary complexity.

## Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Navigation**: Clean, accessible navigation menu for easy site exploration
- **Integrated Google Maps**: Embedded map showing the restaurant's exact location in Adare, Co. Limerick
- **Email Reservations**: Direct mailto link for convenient reservation requests
- **Performance Optimized**: Lightweight CSS and HTML ensure fast page load times
- **Accessible**: Built with web accessibility standards in mind

## Technologies Used

- **HTML5**: Semantic markup for better structure and SEO
- **CSS3**: Modern styling with flexbox and responsive media queries
- **Google Maps Embed API**: Interactive location display

## Getting Started

### Prerequisites

No special prerequisites are required. You only need a modern web browser to view the site.

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Martin888Maina/Restaurant.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Restaurant
   ```

3. Open `index.html` in your preferred web browser:
   ```bash
   # On Windows
   start index.html
   
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   ```

Alternatively, you can use a local development server for testing:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js with http-server
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Project Structure

```
Restaurant/
│
├── index.html          # Main HTML file
├── Styles.css          # Stylesheet with responsive design
├── Images/             # Image assets
│   ├── Background.jpg  # Hero background image
│   └── Logo.png        # Restaurant logo
├── README.md           # Project documentation
└── LICENSE             # MIT License file
```

## Browser Compatibility

This site has been tested and works well on:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

Potential improvements for future iterations:

- Add an interactive menu section with dish photos and pricing
- Implement online ordering functionality
- Create a photo gallery showcasing the restaurant's interior and cuisine
- Add customer testimonials and reviews section
- Integrate with OpenTable or similar reservation systems
- Implement a contact form with backend validation
- Add social media integration
- Create a blog section for restaurant news and events
- Implement animations and micro-interactions for enhanced user experience

## Deployment

### GitHub Pages

To deploy this site to GitHub Pages:

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select the branch to deploy (usually `main` or `master`)
4. Click Save
5. Your site will be available at `https://yourusername.github.io/Restaurant/`

### Other Hosting Options

This static site can be deployed to:
- **Netlify**: Drag and drop the project folder
- **Vercel**: Connect your GitHub repository
- **Surge**: Run `npm install -g surge` and `surge` in the project directory

## Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note**: This is a frontend demonstration project. The email link and some navigation items are placeholders for demonstration purposes.
