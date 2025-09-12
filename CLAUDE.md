# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Mintlify-based blog/documentation site for elevate.do, containing technical articles and thoughts on AI infrastructure, agents, Model Context Protocol (MCP), AI in the workplace, and related topics.

## Development Commands

### Local Development
```bash
# Install Mintlify CLI globally (if not already installed)
npm i -g mintlify

# Start development server (run from /blogs directory where docs.json is located)
cd blogs
mintlify dev
```

### Troubleshooting
```bash
# Re-install dependencies if dev server isn't running
mintlify install
```

## Project Structure

- `/blogs/` - Main content directory containing:
  - `docs.json` - Mintlify configuration file defining site structure, navigation, and theming
  - Content organized in topical directories:
    - `ai-workplace/` - Articles about AI in workplace settings
    - `mcp/` - Model Context Protocol related content
    - `a2a/` - Agent-to-Agent Protocol discussions
    - `thoughts-on-agents/` - Philosophical takes on AI agents
    - `k8s/` - Kubernetes and infrastructure content
    - `musings/` - Personal reflections and observations
    - `beacon/` - My angel investment theses. A super dense VC style call for startups, research, and memos.
  - `images/` - Static assets and images
  - `README.md` - Mintlify setup instructions

## Content Format

- Articles are written in MDX format (`.mdx` files)
- Each article includes frontmatter with `title`, `date`, and `description`
- Navigation structure is defined in `blogs/docs.json` under the "navigation" object

## Style Guide
Use the [Style Guide](/blogs/Style%20Guide.md) to write the content.

## Site Configuration

The site uses Mintlify's "maple" theme with a custom color scheme (primary: #f7b305). Navigation is organized into groups within a single "Blog" tab, with external links to email and homepage in the navbar.

## Publishing

Changes are automatically deployed to production when pushed to the main branch via GitHub integration.