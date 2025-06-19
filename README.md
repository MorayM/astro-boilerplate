# Astro Boilerplate

A modern, opinionated Astro boilerplate for creating fast static websites and blogs. This template includes carefully configured defaults for ESLint, Prettier, and TypeScript to provide an excellent developer experience out of the box.

## ✨ Features

### 🚀 **Performance & SEO**

- ✅ 100/100 Lighthouse performance scores
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Automatic sitemap generation
- ✅ RSS feed support
- ✅ Optimized image handling with Sharp

### 🛠 **Developer Experience**

- ✅ TypeScript with strict configuration
- ✅ Modern ESLint setup with flat config
- ✅ Prettier with Astro plugin for consistent formatting
- ✅ Pre-configured for VS Code
- ✅ Node.js 22+ support with pnpm package manager

### 📝 **Content Management**

- ✅ Markdown & MDX support
- ✅ Content collections for type-safe frontmatter
- ✅ Blog structure ready to use
- ✅ Astro Icon integration for easy iconography

### 🎨 **Styling**

- ✅ Minimal, clean styling (make it your own!)
- ✅ Responsive design patterns

## 🚀 Quick Start

### Using this template

```bash
# Clone this repository
git clone https://github.com/your-username/astro-boilerplate.git my-astro-site
cd my-astro-site

# Install dependencies
pnpm install

# Start the development server
pnpm run dev
```

### Using as a GitHub template

1. Click "Use this template" on GitHub
2. Create your new repository
3. Clone and install dependencies as shown above

## 📁 Project Structure

```text
├── public/                  # Static assets
├── src/
│   ├── components/         # Reusable Astro components
│   ├── content/           # Content collections (blog posts, etc.)
│   │   ├── blog/         # Blog posts in Markdown/MDX
│   │   └── config.ts     # Content collection schemas
│   ├── layouts/          # Page layouts
│   ├── pages/            # File-based routing
│   │   ├── blog/        # Blog pages
│   │   ├── index.astro  # Homepage
│   │   ├── about.astro  # About page
│   │   └── rss.xml.ts   # RSS feed
│   ├── styles/           # Global styles
│   ├── consts.ts         # Site configuration constants
│   └── env.d.ts          # TypeScript environment types
├── astro.config.mjs        # Astro configuration
├── eslint.config.js        # ESLint configuration (flat config)
├── .prettierrc             # Prettier configuration
├── tsconfig.json           # TypeScript configuration
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project:

| Command                 | Action                                       |
| :---------------------- | :------------------------------------------- |
| `pnpm install`          | Install dependencies                         |
| `pnpm run dev`          | Start local dev server at `localhost:4321`   |
| `pnpm run build`        | Build your production site to `./dist/`      |
| `pnpm run preview`      | Preview your build locally, before deploying |
| `pnpm run lint`         | Run ESLint to check for issues               |
| `pnpm run lint:fix`     | Run ESLint and automatically fix issues      |
| `pnpm run format`       | Format code with Prettier                    |
| `pnpm run format:check` | Check if code is properly formatted          |

## ⚙️ Configuration

### ESLint

This template uses the modern ESLint flat configuration with:

- TypeScript support with strict rules
- Astro-specific linting rules
- Prettier integration for consistent formatting
- Automatic fixes for common issues

### Prettier

Configured with opinionated defaults:

- No semicolons
- Single quotes
- 2-space indentation
- Trailing commas (ES5)
- 100 character line width
- Astro plugin for `.astro` file formatting

### TypeScript

- Extends Astro's strict TypeScript configuration
- Strict null checks enabled
- Includes all `.ts`, `.tsx`, and `.astro` files

## 🎯 Customization

1. **Site Information**: Update `src/consts.ts` with your site details
2. **Site URL**: Change the `site` URL in `astro.config.mjs`
3. **Content**: Add your blog posts to `src/content/blog/`
4. **Styling**: Customize the CSS in `src/styles/`
5. **Components**: Add your components to `src/components/`

## 📦 Dependencies

### Core

- **Astro**: The web framework
- **TypeScript**: Type safety and modern JavaScript features

### Integrations

- **@astrojs/sitemap**: Automatic sitemap generation
- **@astrojs/rss**: RSS feed support
- **astro-icon**: Easy icon integration

### Development Tools

- **ESLint**: Code linting with TypeScript and Astro support
- **Prettier**: Code formatting
- **Sharp**: Optimized image processing

## 📚 Learn More

- [Astro Documentation](https://docs.astro.build)
- [Astro Discord](https://astro.build/chat)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
