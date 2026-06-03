# AWS Student Builder Group - Workshop Template

> Credit: Van Hoang Kha | First Cloud AI Journey

![AWS Student Builder Group](static/images/virtual-background-amber.png)

---

A Hugo-based workshop template for AWS Student Builder Group members. This repository provides a ready-to-use structure, theme, and branding so members can fork and create their own workshops.

## How to Use

1. Fork this repository to your account or organization
2. Update content in the `content/` directory with your workshop material
3. Edit `config.toml` to change title, description, and links
4. Push to GitHub - the site will auto-deploy via GitHub Pages

## Run Locally

```bash
# Clone the repo
git clone <repo-url>
cd <repo-folder>

# Install Hugo (if not installed)
# macOS
brew install hugo
# Windows
choco install hugo
# Ubuntu
sudo apt-get install hugo

# Start local server
hugo server -D
```

Visit http://localhost:1313 to preview.

## Directory Structure

```
content/           # Workshop content (markdown)
static/            # Images and static assets
themes/            # Hugo theme
layouts/           # Custom layout overrides
config.toml        # Hugo configuration
.github/workflows/ # GitHub Actions deployment
```

## Deployment

This repo includes a GitHub Actions workflow. Enable GitHub Pages (source: GitHub Actions) in your repo settings and the site will automatically build and deploy on every push to main.

## Multi-language Support

The template supports multiple languages out of the box:
- English (default)
- Vietnamese

## Support

- AWS Student Builder Group: https://www.facebook.com/groups/awsstudentbuildergroupvn/
- AWS Study Group: https://awsstudygroup.com

## License

This repository is provided for educational purposes within the AWS Student Builder Group program.

---

AWS Student Builder Group
