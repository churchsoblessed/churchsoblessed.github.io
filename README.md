# Church So Blessed International Website

Welcome to the official website repository for Church So Blessed International. This website is built with Jekyll, a static site generator that works seamlessly with GitHub Pages.

## 🌟 Features

- **Easy Content Management**: Update pages and events using simple Markdown files
- **Event Management**: Add, edit, and organize church events easily
- **Mobile Responsive**: Fully responsive design that works on all devices
- **GitHub Pages Compatible**: Automatically deployed when you push changes
- **SEO Optimized**: Built-in SEO tags for better search engine visibility

## 🚀 Quick Start

### Prerequisites

- Ruby 2.7 or higher
- Bundler gem
- Git

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/churchsoblessed/churchsoblessed.github.io.git
   cd churchsoblessed.github.io
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Run the local server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site:**
   Open your browser and go to `http://localhost:4000`

## 📝 How to Update Content

### Adding a New Event

1. Create a new file in the `_events` folder with the format: `YYYY-MM-DD-event-name.md`
2. Add the following front matter:
   ```yaml
   ---
   layout: event
   title: "Your Event Title"
   date: YYYY-MM-DD
   time: "Start Time - End Time"
   location: "Event Location"
   ---
   ```
3. Write the event description in Markdown below the front matter
4. Save and commit the file

### Updating Pages

- **Homepage**: Edit `index.md`
- **About Page**: Edit `about.md`
- **Events Page**: Edit `events.md`
- **Contact Page**: Edit `contact.md`

### Updating Site Information

Edit `_config.yml` to change:
- Site title
- Email address
- Description
- Other site-wide settings

## 📂 Project Structure

```
churchsoblessed.github.io/
├── _config.yml           # Site configuration
├── _layouts/             # Page templates
│   ├── default.html
│   ├── home.html
│   ├── page.html
│   └── event.html
├── _includes/            # Reusable components
│   ├── header.html
│   └── footer.html
├── _events/              # Event posts
├── assets/
│   └── css/
│       └── style.css     # Custom styles
├── index.md              # Homepage
├── about.md              # About page
├── events.md             # Events listing page
├── contact.md            # Contact page
└── Gemfile               # Ruby dependencies
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `assets/css/style.css`:
```css
:root {
  --primary-color: #2c5f8d;
  --secondary-color: #4a90c2;
  --accent-color: #f39c12;
}
```

### Adding Navigation Items

Edit the `header_pages` list in `_config.yml`

## 🚢 Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch. Make sure GitHub Pages is enabled in your repository settings.

## 🤝 Contributing

1. Create a new branch for your changes
2. Make your edits
3. Test locally
4. Submit a pull request

## 📞 Support

For questions or issues, please contact: info@churchsoblessed.org

## 📄 License

© 2024 Church So Blessed International. All rights reserved.
