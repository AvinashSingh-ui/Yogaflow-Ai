# YogaFlow AI

A web application for personalized yoga coaching, pose practice, and management.

## Features

- User authentication (signup, login)
- Dashboard for users
- Browse and view yoga pose library
- Detailed pose pages
- Guided practice sessions
- Responsive UI with Tailwind CSS

## Project Structure

```
project/
├── public/                 # Static assets
├── scripts/                # Utility scripts
├── src/                    # Source code
│   ├── components/         # Reusable UI components
│   ├── contexts/           # React context providers
│   ├── data/               # Static/mock data
│   ├── pages/              # Route-based pages
│   ├── utils/              # Utility functions
│   ├── App.tsx             # Main app component
│   └── main.tsx            # App entry point
├── index.html              # Main HTML file
├── package.json            # Project dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── vite.config.ts          # Vite configuration
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm (comes with Node.js) or [Yarn](https://yarnpkg.com/)

### Installation

1. **Navigate to the project directory:**
   ```sh
   cd project
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```
   or
   ```sh
   yarn
   ```

### Running the Project

Start the development server:

```sh
npm run dev
```
or
```sh
yarn dev
```

Open your browser and go to [http://localhost:5173](http://localhost:5173) to view the app.

### Building for Production

```sh
npm run build
```
or
```sh
yarn build
```

### Linting

```sh
npm run lint
```
or
```sh
yarn lint
```

## License

MIT

---

*Built with [Vite](https://vitejs.dev/), [React](https://react.dev/), and [Tailwind CSS](https://tailwindcss.com/).*
