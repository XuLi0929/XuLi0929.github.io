# Personal Academic Website

This is a clean, modern personal academic website template designed for researchers, PhD students, and academics. It features multiple pages and sections to showcase your academic profile, research interests, publications, and CV.

## Features

- Responsive design that works on all devices
- Dark mode toggle
- Separate pages for publications and CV
- Clean, modern UI with customizable color scheme
- Mobile-friendly navigation
- Publication filtering by type (conference, journal, workshop)
- Structured sections for research interests, news, and contact information

## How to Customize

### Basic Information

1. **Personal Details**: 
   - Edit the name, title, and alternative names in `index.html`
   - Replace `profile.jpg` with your photo (create a square image for best results)

2. **About Section**:
   - Update your bio, education, and research affiliations in the "About Me" section of `index.html`

3. **Research Interests**:
   - Modify the research areas in the "Research Interests" section of `index.html`
   - Add or remove research area cards as needed

4. **Publications**:
   - Update the publications listed in `publications.html`
   - For each publication, you can include:
     - Title, authors, venue
     - Abstract
     - Links to paper, code, slides, etc.
     - A thumbnail image
   - Group publications by year using the year dividers

5. **CV**:
   - Update all sections in `cv.html` with your education, experience, skills, etc.
   - You can add or remove sections as needed

6. **News**:
   - Update the news items in the "News" section of `index.html`
   - Format: Date + News content

7. **Contact Information**:
   - Update your email and social media links in the footer section of all HTML files

### Customizing Colors

The color scheme can be easily modified by editing the CSS variables at the top of the `styles.css` file:

```css
:root {
    --primary-color: #6c5ce7;    /* Main accent color */
    --secondary-color: #a29bfe;  /* Secondary accent color */
    --text-color: #333;          /* Main text color */
    --light-bg: #f9f9f9;         /* Light background color */
    --dark-bg: #2d3436;          /* Dark mode background */
    --dark-text: #f1f1f1;        /* Dark mode text color */
    /* ... other variables ... */
}
```

### Adding More Pages

To add a new page:

1. Create a new HTML file (e.g., `projects.html`)
2. Copy the header and footer from existing pages
3. Update the navigation links in all HTML files to include the new page
4. Add your content in the main section

## Deployment

### GitHub Pages

1. Push this code to your GitHub repository named `yourusername.github.io`
2. GitHub will automatically deploy your site at `https://yourusername.github.io`

### Custom Domain

If you want to use a custom domain:

1. Purchase a domain from a domain registrar
2. Add a file named `CNAME` to your repository with your domain name
3. Configure DNS settings with your domain registrar (follow GitHub's documentation)

## Development

To run this website locally:

1. Clone the repository
2. Open the `index.html` file in your browser

You can also use a local development server:

```bash
# Using Python
python -m http.server

# Using Node.js
npx serve
```

## Credits

- Font Awesome for icons
- Google Fonts for typography
- Placeholder images from placeholder.com

## License

This template is available under the MIT License. Feel free to use it for your personal academic website.

---

Happy customizing! 😊
