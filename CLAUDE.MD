# CLAUDE.MD

This file provides context and guidance for AI assistants working on the Bryan Walsh personal website project.

## Project Overview

**bryanwalsh-site** is a personal website for Bryan Walsh. This repository contains the source code and assets for the site.

## Project Purpose

- Personal portfolio/website
- Showcase work, projects, and professional information
- Provide contact information and online presence

## Repository Structure

```
bryanwalsh-site/
├── CLAUDE.MD          # This file - AI assistant guidance
├── README.md          # Project documentation
└── [Future directories for source code, assets, etc.]
```

## Development Guidelines

### Technology Stack

*To be determined - update this section when tech stack is chosen*

Possible options:
- Static site generator (Hugo, Jekyll, Next.js, etc.)
- Frontend framework (React, Vue, Svelte, etc.)
- Hosting platform (Vercel, Netlify, GitHub Pages, etc.)

### Code Style

- Use clear, semantic naming conventions
- Keep code modular and reusable
- Comment complex logic
- Follow accessibility best practices (WCAG 2.1 AA minimum)

### Branching Strategy

- Main branch: Production-ready code
- Feature branches: Use `claude/` prefix for AI-assisted development
- Commit messages: Clear, descriptive, focusing on the "why"

### Testing

*Update when testing framework is implemented*

### Deployment

*Update when deployment pipeline is configured*

## Key Considerations for AI Assistants

1. **Accessibility First**: Ensure all features are accessible (semantic HTML, ARIA labels, keyboard navigation)
2. **Performance**: Optimize images, minimize bundle size, lazy load where appropriate
3. **SEO**: Include proper meta tags, structured data, and sitemap
4. **Responsive Design**: Mobile-first approach, test across breakpoints
5. **Security**: Follow OWASP best practices, sanitize inputs, use HTTPS

## Project Context

### Current State
- Repository initialized
- Minimal structure in place
- Ready for initial development

### Next Steps
1. Choose and implement technology stack
2. Create basic site structure
3. Design and implement UI/UX
4. Add content sections (About, Projects, Contact, etc.)
5. Set up deployment pipeline

## Contact & Resources

- Repository: bryanwalsh-site
- Owner: Bryan Walsh

## Notes for Development

### Common Tasks

**Adding a new page/section:**
- Create component/template
- Add routing if applicable
- Update navigation
- Ensure responsive design
- Add appropriate meta tags

**Updating content:**
- Locate content files (to be determined based on stack)
- Follow existing content structure
- Update navigation if adding new pages

**Deploying changes:**
- Ensure all tests pass
- Review changes in staging/preview
- Deploy to production
- Verify deployment

## File Patterns to Ignore

- `node_modules/`
- `.env` files (never commit secrets)
- Build artifacts
- `.DS_Store` and editor-specific files

## Additional Context

This CLAUDE.MD file should be updated as the project evolves. Keep it current with:
- Technology decisions
- Architecture changes
- Development processes
- Deployment procedures
- Any project-specific conventions

---

*Last Updated: January 7, 2026*
