# Oase Creative Sales Documentation

Welcome to the Oase Creative sales documentation. This site provides comprehensive information about our services, pricing, and how to get started with your project.

## About Oase Creative

Oase Creative® is a creative agency specializing in e-commerce branding, design, and content creation. Founded in 2020, we help ambitious brands scale their e-commerce businesses through strategic design and high-quality visual content.

**Location:** Velperweg 54, Arnhem, 6824 BM, Netherlands  
**KvK:** 78201691 | BTW: NL003300299B43

## Our Approach

We believe that companies with well-designed product listings can achieve online success. We take branding and product photography seriously, and this is reflected in our work. Our goal is to help you stand out from your competitors through strategic design and attention to detail.

## Trust & Quality

With over 174 reviews on Trustpilot and a 4.9/5 rating, we're proud of the quality of work we deliver and the relationships we build with our clients.

## Get Started

Ready to start your project? Explore our [Services](/services/listings) or check out our [Pricing](/pricing) information. When you're ready, fill out one of our [Project Forms](/forms) to get started.

---

## Development & Setup

This documentation site is built with [Mintlify](https://mintlify.com/), a modern documentation platform.

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Local Development

1. **Install Mintlify CLI:**
   ```bash
   npm i -g mintlify
   ```

2. **Start the development server:**
   ```bash
   mint dev
   ```

3. **Preview your changes:**
   - Open `http://localhost:3000` in your browser
   - Changes will hot-reload automatically

### Validation & Quality Checks

Before deploying, run these commands:

```bash
# Validate configuration
mint validate

# Check for broken links
mint broken-links

# Check accessibility
mint a11y
```

### Project Structure

```
sales-oase/
├── docs.json              # Mintlify configuration
├── en/                    # English content
│   ├── index.mdx
│   ├── services/
│   ├── pricing.mdx
│   ├── faq.mdx
│   └── ...
├── nl/                    # Dutch content
│   ├── index.mdx
│   ├── services/
│   ├── pricing.mdx
│   ├── faq.mdx
│   └── ...
├── images/                # Image assets
├── logo/                  # Logo files
└── assets/                # PDFs and other files
```

### Deployment

This site is automatically deployed via Mintlify when changes are pushed to the main branch. No additional build steps are required.

### Troubleshooting

For common issues and syntax errors, see [MINTLIFY_TROUBLESHOOTING.md](./MINTLIFY_TROUBLESHOOTING.md).

### Contributing

When adding or editing content:

1. Ensure frontmatter is properly formatted with `title` and `description`
2. Use consistent formatting across all pages
3. Keep English and Dutch versions synchronized
4. Test locally with `mint dev` before committing
5. Run `mint broken-links` to check for broken references