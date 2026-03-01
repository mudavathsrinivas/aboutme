# Srinivas Mudavath - Personal Portfolio

A simple, SEO-friendly personal portfolio website built with HTML and Bootstrap 5.

## Project Structure

```
├── index.html          # Home page (summary, skills, strengths, education, memberships)
├── experience.html      # Full work history (AT&T, Technovision, Optum)
├── awards.html         # Awards and recognition
├── publications.html   # Publications (The New Stack - TBD)
├── talks.html          # Placeholder
├── posts.html          # Placeholder
├── service.html        # Placeholder
├── teaching.html       # Placeholder
├── assets/
│   └── profile.svg     # Profile image placeholder
└── README.md
```

## How to Edit

### Updating Your Profile
- **index.html**: Edit the Summary, Skills, Strengths, Education, and Memberships sections. Replace placeholder links (LinkedIn, GitHub, Resume) with your actual URLs.
- **Profile image**: Replace `assets/profile.svg` with your photo (e.g. `profile.jpg`), then update the `src` in `index.html` to `assets/profile.jpg`.

### Adding Content to Placeholder Pages
Each placeholder page (talks, posts, service, teaching) has the same layout. Copy the structure from `experience.html` or `awards.html` and replace the main content inside the `.main-content` div.

### SEO Tips
- Update `<meta name="description">` and `<meta name="keywords">` on each page.
- Use semantic headings: `<h1>` for page title, `<h2>` for main sections, `<h3>` for subsections.
- Add descriptive `alt` text to images.
- Keep page titles unique (e.g. "Experience - Srinivas Mudavath").

## Running Locally

Open `index.html` in a browser, or use a simple local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve
```

Then visit `http://localhost:8000`.

## Dependencies

- **Bootstrap 5.3.2** (CDN)
- **Bootstrap Icons 1.11.1** (CDN)

No build step or npm install required.
