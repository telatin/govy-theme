# Govy Template

A clean, minimalist Jekyll blog template inspired by GOV.UK design patterns but simplified for personal use.
This template is designed to be easy to use, accessible, and GitHub Pages compatible.

## Installation

1. Clone or download this repository
2. Install Jekyll and Bundler:
   ```
   gem install jekyll bundler
   ```
3. Navigate to the project directory and run:
   ```
   bundle install
   ```
4. Start the local server:
   ```
   bundle exec jekyll serve
   ```
5. Visit `http://localhost:4000` in your browser

## Customization

### Site Configuration

Edit the `_config.yml` file to customize:
- Site title and description
- Contact information
- Social media links
- Build settings

### Layout and Design

The template structure follows Jekyll conventions:
- `_layouts`: Contains the main layout templates
- `_includes`: Contains reusable components
- `_posts`: Contains blog posts
- `assets`: Contains CSS, JavaScript, and images

### CSS

The main CSS file is located at `assets/css/main.css`. It's organized by component and uses CSS variables for easy theming.

### Creating Posts

To create a new post:
1. Add a file to the `_posts` directory with the naming convention: `YYYY-MM-DD-title.md`
2. Add front matter at the top of the file:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS +0000
   categories: category-name
   author: Your Name
   toc:
     - id: section-id
       title: Section Title
   ---
   ```
3. Write your post content in Markdown below the front matter

## Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Push your Jekyll site to the repository
3. In the repository settings, enable GitHub Pages and select the `main` branch as the source

## License

This template is available as open source under the terms of the [MIT License](LICENSE).

## Credits

This template was created based on [**GOV.UK design patterns**](https://design-system.service.gov.uk/styles/page-template/),
simplified and adapted for Jekyll and personal blogging use.
