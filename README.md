# Personal Website

This is my personal website built with [Hugo](https://gohugo.io/), a fast and flexible static site generator written in Go.

## Theme

This site uses the [hugo-coder](https://github.com/luizdepra/hugo-coder) theme, a minimalist blog theme for Hugo with a clean and responsive design.

## Tech Stack

- **Static Site Generator**: [Hugo](https://gohugo.io/)
- **Theme**: [hugo-coder](https://github.com/luizdepra/hugo-coder)
- **Hosting**: GitHub Pages
- **Domain**: [vedant15188.github.io](https://vedant15188.github.io)

## Development

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (Extended version recommended)
- [Git](https://git-scm.com/)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/vedant15188/vedant15188.github.io.git
   cd vedant15188.github.io
   ```

2. Start the development server:
   ```bash
   hugo server -D
   ```

3. Visit `http://localhost:1313` to view the site locally.

### Building

To build the site for production:

```bash
hugo --minify
```

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## Customization

The site can be customized by modifying:

- `hugo.toml` - Site configuration and theme settings
- `content/` - Page content and blog posts
- `static/` - Static assets like images and files
- `layouts/` - Custom layout overrides (if needed)

## Resources

- [Hugo Documentation](https://gohugo.io/documentation/)
- [Hugo-Coder Theme Documentation](https://github.com/luizdepra/hugo-coder#readme)
- [Hugo Quick Start Guide](https://gohugo.io/getting-started/quick-start/)
