# rvgef-website
Homepage for RISC-V Global Ecosystem Forum (Hong Kong)

## About

This is the official website for the RISC-V Global Ecosystem Forum, a gathering of RISC-V enthusiasts, developers, and industry leaders in Hong Kong. The website serves as an information hub for attendees, speakers, and sponsors.

## Features

- **Bootstrap-style, Mobile-first Design**: Responsive design that works seamlessly across all devices
- **RISC-V Theme**: Blue (#283583) and yellow (#f7ce46) color scheme matching the RISC-V logo
- **Complete Event Information**: 
  - Event introduction and overview
  - Call for speakers with submission guidelines
  - Sponsorship opportunities and packages
  - Venue and agenda details
  - Organizer information
  - Travel and transportation guidance
  - Accommodation recommendations

## Technology Stack

- **Static Site Generator**: Hugo
- **CSS Framework**: Bootstrap 5.3
- **Deployment**: GitHub Pages via GitHub Actions
- **License**: Apache License 2.0

## Building Locally

### Prerequisites

- Hugo Extended v0.121.0 or later ([installation guide](https://gohugo.io/installation/))

### Development

1. Clone the repository:
   ```bash
   git clone https://github.com/rv2036/rvgef-website.git
   cd rvgef-website
   ```

2. Start the Hugo development server:
   ```bash
   hugo server -D
   ```

3. Open your browser to `http://localhost:1313`

### Building for Production

```bash
hugo --minify
```

The built site will be in the `public/` directory.

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch. The deployment is handled by the GitHub Actions workflow defined in `.github/workflows/hugo.yml`.

## Structure

```
.
├── config.toml           # Hugo configuration
├── content/              # Markdown content files
├── layouts/              # HTML templates
│   └── index.html        # Main homepage template
├── static/               # Static assets
│   ├── css/              # Custom CSS
│   ├── js/               # JavaScript files
│   └── images/           # Images and graphics
└── .github/
    └── workflows/
        └── hugo.yml      # GitHub Actions deployment workflow
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

Copyright 2024 RISC-V Global Ecosystem Forum

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Contact

For questions or inquiries about the event, please contact:
- General inquiries: info@rvgef.org
- Speaker submissions: speakers@rvgef.org
- Sponsorship opportunities: sponsors@rvgef.org

