# Next Essential

An Essential Template to build an Modern Next.js application with all the essentials included.

## Getting Started

### Radium - [Install Radium CLI](https://github.com/radiumlabs/radium) (Recommended)

`radium` is an CLI tool to initialize any project. By using `radium init --with` command, radium will install dependencies, initialize as git repository, and prepare your project for development by cleaning up the project.

```bash
radium init --with
```

and then follow the instructions to enter the name of project and url of this template.

### Manual Installation

You can also manually install the template by cloning the repository and installing the dependencies. But initially you have to clean up the project and then start the development server.

```bash
git clone https://github.com/radiumlabs/next-essential.git
```

```bash
cd next-essential
```

Choose your preferred package manager (PNPM or YARN or BUN or NPM) and install the dependencies but before that, you have to clean up the project such as removing the `.git` folder and `pnpm-lock.yaml` file.

```bash
git bash
```

```bash
rm -rf .git pnpm-lock.yaml
```

and then install the dependencies by using the package manager of your choice.

```bash
pnpm/yarn/bun/npm install
```

```bash
pnpm/yarn/bun/npm run dev
```

## Features

- ✨ Framework: [Next.js](https://nextjs.org/)
- 🚀 Styling: [Tailwind CSS](https://tailwindcss.com/)
- 💻 Language: [TypeScript](https://www.typescriptlang.org/)
- 🧹 Linting and Formatting: [Biome.js](https://biomejs.dev/)
- 🎨 Themes: [Next Themes](https://github.com/pacocoursey/next-themes)
- 💄 Icons: [Radix-Icon](https://www.radix-ui.com/icons)
- 🎨 UI: [Shadcn UI](https://ui.shadcn.com/)
- ⚙️ Build: Github Actions
- 🛠 Commit: [Husky](https://typicode.github.io/husky/)

## Contribute

Contributions are always welcome! Please submit a pull request or open an issue to discuss your ideas.
