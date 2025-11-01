# StackDock Documentation

Official documentation for [StackDock](https://github.com/stackdock/stackdock) - An open-source multi-cloud management platform.

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm 9+
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/stackdock/docs.git
cd docs

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the documentation.

## 📚 Documentation Structure

```
content/docs/
├── index.mdx                    # Introduction
├── progress.mdx                 # Current build status
├── architecture/
│   └── overview.mdx            # System architecture
└── guides/
    ├── dock-adapter.mdx        # Building dock adapters
    └── contributing.mdx        # Contributing guide
```

## 🛠️ Tech Stack

- **[Next.js](https://nextjs.org/)** - React framework
- **[Fumadocs](https://fumadocs.vercel.app/)** - Documentation framework
- **[MDX](https://mdxjs.com/)** - Markdown with JSX
- **[Tailwind CSS](https://tailwindcss.com/)** - Styling

## 📝 Adding Documentation

### Create a New Page

1. Create a new `.mdx` file in `content/docs/`
2. Add frontmatter with title and description:

```mdx
---
title: Your Page Title
description: A brief description of the page
---

# Your Content Here

Your markdown content goes here...
```

3. The page will automatically appear in the navigation

### Organizing Pages

Create subdirectories in `content/docs/` to organize pages into sections:

```
content/docs/
├── guides/
│   ├── guide-1.mdx
│   └── guide-2.mdx
└── reference/
    ├── api.mdx
    └── cli.mdx
```

## 🚀 Deployment

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/stackdock/docs)

### Manual Deployment

```bash
# Build for production
npm run build

# Start production server
npm start
```

The documentation will be built as static files in `.next/` directory.

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](https://github.com/stackdock/stackdock/blob/main/CONTRIBUTING.md) for details.

### Quick Contribution Steps

1. Fork the repository
2. Create a new branch: `git checkout -b docs/your-feature`
3. Make your changes
4. Commit: `git commit -m "docs: your message"`
5. Push: `git push origin docs/your-feature`
6. Create a Pull Request

## 📄 License

MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- [StackDock Repository](https://github.com/stackdock/stackdock)
- [StackDock Website](https://stackdock.dev)
- [Fumadocs Documentation](https://fumadocs.vercel.app/)
- [Report Issues](https://github.com/stackdock/docs/issues)

## 📧 Contact

- **General**: contact@stackdock.dev
- **Security**: security@stackdock.dev

---

Built with ⚓️ by the StackDock team
