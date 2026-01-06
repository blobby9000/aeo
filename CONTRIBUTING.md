# Contributing to AEO.dev

Thanks for your interest in contributing! This guide will help you get started.

## Quick Start (No Coding Required)

The easiest way to contribute:

1. Go to **[aeo.dev/contribute](https://aeo.dev/contribute)**
2. Click **"Open Content Editor"**
3. Sign in with GitHub
4. Create or edit content using the visual editor
5. Submit — your changes automatically create a Pull Request

## Edit on GitHub

Every page can be edited directly:

1. Find the page you want to edit on [aeo.dev](https://aeo.dev)
2. Go to the corresponding file in `src/app/[path]/page.mdx`
3. Click the pencil icon on GitHub to edit
4. Submit a Pull Request

## Local Development

For larger contributions or new sections:

```bash
# Clone the repository
git clone https://github.com/answer-engine/aeo.git
cd aeo

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the site.

### Creating Content

```bash
# Create a branch
git checkout -b feature/your-contribution

# Add your content in src/app/
# Follow the existing MDX format

# Commit and push
git add .
git commit -m "Add: description of your contribution"
git push origin feature/your-contribution
```

Then open a Pull Request on GitHub.

## Content Guidelines

- **Cite sources** — Link to research, data, or case studies
- **Be specific** — Include numbers, examples, implementation details
- **Stay current** — Note when information was last verified
- **No promotion** — Educational content, not marketing
- **Share failures too** — Failed experiments teach us something

## File Structure

```
src/app/
├── ai-search/         # AI search engine guides
├── optimization/      # Optimization techniques
├── strategies/        # Strategy guides
├── technical/         # Technical implementation
├── resources/         # Best practices, FAQ, glossary
└── tools/             # AEO tools documentation
```

## Tech Stack

- **Next.js 15** with App Router
- **MDX** for documentation
- **Tailwind CSS** for styling
- **Decap CMS** for visual editing

## Questions?

- [GitHub Discussions](https://github.com/answer-engine/aeo/discussions)
- [Slack Community](https://answer-engine.slack.com)

