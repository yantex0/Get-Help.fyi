# Get-Help.fyi

Source repository for **[Get-Help.fyi](https://get-help.fyi/)** — concise, beginner-friendly PowerShell documentation and guides written from hands-on IT experience.

## Built With

- **[Hugo](https://github.com/gohugoio/hugo)** — static site generator
- **[Hugo Book](https://github.com/alex-shpak/hugo-book)** — documentation theme
- **Cloudflare Workers Static Assets** — hosting and deployment

## Running Locally

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended edition recommended)
- [Git](https://git-scm.com/)

### Preview the Site

```powershell
git clone https://github.com/yantex0/Get-Help.fyi.git
cd Get-Help.fyi
hugo server -D
```

Then open `http://localhost:1313/` in your browser.

## Repository Structure

```text
├── assets/              # Custom styles and icons
├── content/docs/        # Markdown documentation pages
├── layouts/             # Custom Hugo partial overrides
├── static/              # Static files (including Cloudflare _headers)
├── themes/hugo-book/    # Hugo Book theme
├── hugo.toml            # Hugo site configuration
└── wrangler.jsonc       # Cloudflare Workers Static Assets configuration
```

## Contributing

Spotted a typo, broken link, or something that could be clearer? Feel free to open an issue or submit a pull request.
