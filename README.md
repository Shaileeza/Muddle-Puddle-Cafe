# Muddle Puddle Café Website

A modern, responsive website for Muddle Puddle Café in East Lismore, NSW - serving fresh coffee, all-day breakfast, and authentic Nepalese specialties.

## Features

✨ **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
🎨 **Modern UI** - Clean and professional design with smooth animations
☕ **Menu Filtering** - Filter menu items by category (All, Breakfast, Nepalese, Drinks)
📱 **Mobile Navigation** - Hamburger menu for mobile devices
📧 **Contact Form** - Easy way for customers to get in touch
🖼️ **Gallery** - Showcase of café ambiance and delicious food
🔍 **SEO Optimized** - Meta tags and semantic HTML for better search engine visibility

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript (Vanilla)** - No dependencies, lightweight and fast
- **GitHub Pages** - Free hosting and deployment

## File Structure

```
muddle-puddle-cafe/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/Shaileeza/muddle-puddle-cafe.git
cd muddle-puddle-cafe
```

2. Open `index.html` in your browser or use a local server:
```bash
python -m http.server 8000
# or
npx http-server
```

3. Visit `http://localhost:8000` in your browser

### Deployment (GitHub Pages)

The website is already set up for GitHub Pages deployment!

1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select "main" branch as the source
4. Your site will be live at: `https://Shaileeza.github.io/muddle-puddle-cafe/`

## Features Breakdown

### Navigation
- Sticky navigation bar with smooth scrolling
- Mobile-friendly hamburger menu
- Quick access to all sections

### Menu Section
- Browse all menu items
- Filter by category
- Display prices for each item
- Smooth animations and transitions

### Gallery
- Beautiful image showcase
- Hover effects for engagement
- Responsive grid layout

### Contact Section
- Business hours and location
- Contact information
- Contact form with validation
- Social media links

## Customization

### Change Business Information
Edit the following sections in `index.html`:

```html
<!-- Phone number -->
<a href="tel:+61266234567">(02) 6623 4567</a>

<!-- Email -->
<a href="mailto:hello@muddlepuddlecafe.com">hello@muddlepuddlecafe.com</a>

<!-- Hours -->
<strong>Monday – Friday:</strong> 7:30 AM – 2:30 PM<br>
```

### Change Colors
Edit CSS variables in `styles.css`:

```css
:root {
  --primary-color: #2f5d50;     /* Main color */
  --secondary-color: #f4b400;   /* Accent color */
  --dark-color: #222;
  --light-color: #fafafa;
}
```

### Add Menu Items
Add new cards in the menu section:

```html
<div class="card" data-category="breakfast">
  <h3>🍕 Your Dish Name</h3>
  <p>Description of your delicious dish.</p>
  <span class="price">$XX.XX</span>
</div>
```

### Update Gallery Images
Replace image URLs in the gallery section:

```html
<img src="YOUR_IMAGE_URL" alt="Description">
```

## Form Functionality

The contact form includes:
- Real-time validation
- Email format checking
- Success/error messages
- Auto-clear after submission

**Note:** Currently, the form stores data in browser console. To actually send emails, you'll need to connect it to a backend service like:
- Formspree
- Basin
- EmailJS
- Your own backend API

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

- 🔗 Backend integration for form submissions
- 📸 Image optimization and lazy loading
- 🌙 Dark mode toggle
- 🗺️ Google Maps integration
- 📅 Online booking system
- 💬 Live chat support
- 📸 Instagram feed integration

## License

This project is open source and available under the MIT License.

## Support

For questions or feedback, visit: https://www.facebook.com/share/1baFENFuak/

---

**Made with ❤️ for Muddle Puddle Café**
