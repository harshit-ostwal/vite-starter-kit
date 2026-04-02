# react-starter-kit

Scaffold a production-ready React application with a single command.

## Usage

```sh
bunx create-vite-starter-kit <project-name>
```

Or with npm:

```sh
npx create-vite-starter-kit <project-name>
```

Or with pnpm:

```sh
pnpx create-vite-starter-kit <project-name>
```

## What's included

- **React 19** for building UI components
- **Vite** for lightning-fast dev server and builds
- **Tailwind CSS v4** for utility-first styling
- **Axios** for HTTP requests
- **Biome** for formatting and linting
- Pre-configured folder structure for scalable apps

## Interactive Setup

The CLI will prompt you to:

1. Enter your project name (or use `.` for the current directory)
2. Choose your preferred package manager — **pnpm** (recommended), **npm**, **yarn**, or **bun**

Dependencies are installed automatically after scaffolding.

## Project Structure

```
├── src/
│   ├── app.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── components/
│   ├── constants/
│   ├── context/
│   ├── lib/
│   │   └── axios.js
│   ├── routes/
│   ├── screens/
│   └── utils/
├── index.html
├── vite.config.js
├── biome.json
└── package.json
```

## Scripts

| Script | Description |
|---|---|
| `dev` | Start the development server |
| `build` | Build for production |
| `preview` | Preview the production build |
| `biome:format` | Format code with Biome |
| `biome:lint` | Lint code with Biome |
| `biome:check` | Run Biome format + lint |

## Requirements

- [Bun](https://bun.sh/) >= 1.3.4

## Repository

[github.com/harshit-ostwal/react-starter-kit](https://github.com/harshit-ostwal/react-starter-kit)

## License

MIT — Made by [Harshit Ostwal](https://github.com/harshit-ostwal)