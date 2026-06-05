# Ett Rom Til - Portfolio Website

A clean, modern portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing interior design, furniture, and building projects.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Navigation Bar**: Smooth scrolling navigation with Swedish labels
- **Portfolio Grid**: Dynamic grid layout for showcasing projects
- **Image Placeholders**: Ready for your portfolio images
- **GitHub Pages Ready**: Deploy directly to GitHub Pages for free

## Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # JavaScript interactions
├── src/                # Image folder (add your images here)
│   ├── portfolio-1.jpg
│   ├── portfolio-2.jpg
│   ├── portfolio-3.jpg
│   └── portfolio-4.jpg
└── README.md           # This file
```

## How to Add Images

1. Navigate to the `src` folder
2. Upload or add your portfolio images:
   - `portfolio-1.jpg` - First project image
   - `portfolio-2.jpg` - Second project image
   - `portfolio-3.jpg` - Third project image
   - `portfolio-4.jpg` - Fourth project image

The images will automatically replace the placeholder text on the homepage.

## Navigation Sections

- **Tjenester** - Services
- **Prosess** - Process
- **Projekter** - Projects
- **Kontakt** - Contact

You can add content sections for each of these by following the existing HTML structure.

## Customization

### Change Colors
Edit the CSS variables at the top of `styles.css`:

```css
:root {
    --primary-color: #000000;
    --secondary-color: #ffffff;
    --accent-color: #f0f0f0;
    --text-color: #333333;
}
```

### Modify Content
Update the text in `index.html` to match your brand and message.

### Add More Projects
Duplicate a `.portfolio-item` div and update the image path and alt text.

## Deploy to GitHub Pages

1. Push all files to your GitHub repository
2. Go to **Settings** → **Pages**
3. Set the source to your main branch
4. Your site will be live at `https://yourusername.github.io/Nikolic-Studio-Website/`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Feel free to use and modify this template for your portfolio!
