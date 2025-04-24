# Next.js Tailwind CSS and TypeScript Starter

This is a starter project for building web applications using Next.js, Tailwind CSS, and TypeScript.

## Features

- **Next.js**: React framework for server-side rendering and static site generation. (v. 15)
- **React**: Fast and flexible UI library for building user interfaces. (v. 19)
- **TypeScript**: Strongly typed JavaScript for better development experience. (v. 5)
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development. (v. 4)
- **ESLint**: Linting for maintaining code quality. (v. 9)
- **Prettier**: Code formatting for consistent style. (v. 3)
- **Husky**: Git hooks for enforcing pre-push checks. (v. 9)
- **Yarn**: Package manager for managing dependencies. (v. 4)

## Prerequisites

1. Install [Node.js](https://nodejs.org/en/download) (LTS version recommended).
2. Enable Corepack to use a stable version of Yarn:

```sh
corepack enable
```

## Getting Started

1. Clone the repository:

```sh
git clone https://github.com/jhordyess/nextjs-tailwind-ts-starter.git
```

2. Navigate to the project folder:

```sh
cd nextjs-tailwind-ts-starter
```

3. Install dependencies:

```sh
yarn install
```

4. Start the development server:

```sh
yarn dev
```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to see your project.

## Project Structure

```md
nextjs-tailwind-ts-starter/
├── .gitignore              # List of files and directories to be ignored by version control.
├── .prettierrc.json        # Prettier configuration file.
├── .yarnrc.yml             # Yarn configuration file.
├── eslint.config.js        # ESLint configuration file.
├── next.config.js          # Next.js configuration file.
├── package.json            # Project configuration and dependencies.
├── postcss.config.mjs      # PostCSS configuration file.
├── README.md               # Project documentation.
├── tsconfig.json           # TypeScript configuration file.
├── yarn.lock               # Yarn lock file for dependency versions.
├── .husky/                 # Directory for Git hooks managed by Husky.
│   ├── pre-push            # Pre-push hook to run linting and TypeScript checks.
├── src/app/                # Main application directory.
│   ├── globals.css         # Global CSS styles.
│   ├── layout.tsx          # Main layout component.
│   ├── page.tsx            # Main page component.
```

## Commands

### Start the development server

```sh
yarn dev
```

### Build the project for production

```sh
yarn build
```

### Preview the project before production

```sh
yarn start
```

### Run TypeScript checks

```sh
yarn ts-check
```

### Lint the code

```sh
yarn lint
```

### Validate the project (lint + TypeScript checks)

```sh
yarn validate
```

### Format the code

```sh
yarn format
```

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.

---

Happy coding!
