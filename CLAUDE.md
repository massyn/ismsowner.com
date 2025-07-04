# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static documentation website for ISMSOwner.com, built with MkDocs and deployed to AWS S3. The site provides educational resources about Information Security Management Systems (ISMS), including knowledge articles, tools, and guidance for implementing ISMS in organizations.

## Architecture

- **Static Site Generator**: MkDocs with custom Cinder theme
- **Content**: Markdown files in `/docs/` directory
- **Theme**: Custom theme in `/cinder/` directory (based on Bootstrap)
- **Deployment**: Automated via GitHub Actions to AWS S3
- **Site Structure**: 
  - Main content pages in `/docs/`
  - Custom theme templates in `/cinder/`
  - Configuration in `mkdocs.yml`

## Common Commands

### Build the site locally
```bash
mkdocs build -f mkdocs.yml -d /tmp/build -c --no-directory-urls
```

### Serve the site locally for development
```bash
mkdocs serve -f mkdocs.yml
```

### Install dependencies
```bash
python -m pip install mkdocs mkdocs-video mkdocs-mermaid2-plugin mkdocs-cluster mkdocs-bootstrap4 mkdocs-bootswatch
```

## Content Structure

- **Main Documentation**: All content pages are in `/docs/` as Markdown files
- **Navigation**: Configured in `mkdocs.yml` under the `nav` section
- **Home Page**: `docs/index.md`
- **ISMS Topics**: Individual markdown files covering different aspects of ISMS implementation

## Theme and Styling

- **Custom Theme**: Located in `/cinder/` directory
- **Base Templates**: `base.html`, `main.html`, `content.html`
- **CSS**: Custom styles in `/cinder/css/`
- **JavaScript**: Custom scripts in `/cinder/js/`
- **Theme Config**: `cinder/mkdocs_theme.yml`

## Deployment

- **CI/CD**: GitHub Actions workflow in `.github/workflows/blank.yml`
- **Target**: AWS S3 bucket `www.ismsowner.com`
- **Trigger**: Pushes to main branch
- **Process**: Build with MkDocs, sync to S3

## Key Files

- `mkdocs.yml`: Main configuration file
- `docs/index.md`: Homepage content
- `cinder/`: Custom theme directory
- `.github/workflows/blank.yml`: CI/CD pipeline

## Content Guidelines

- All content is educational and focused on ISMS implementation
- Content should be accessible to ISMS practitioners of all levels
- Use clear, professional language appropriate for security professionals
- Include practical examples and actionable guidance where possible
- Content has been updated to reflect ISO 27001:2022 standard (93 controls in 4 categories)
- References to ISO 27001:2013 have been updated to 2022 where appropriate
- Modern threat examples include ransomware, cloud security, remote work challenges