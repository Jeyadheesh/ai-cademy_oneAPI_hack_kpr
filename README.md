# Next.js Project Setup

This repository contains a [Next.js](https://nextjs.org/) project. Follow the steps below to install, build, and run the project locally or deploy it to production.

## Prerequisites

Ensure that you have the following tools installed on your machine:

- **Node.js**: [Download here](https://nodejs.org/en/download/) (Version 16.x or higher is recommended).
- **npm**: Comes bundled with Node.js (or you can use **yarn**).

To verify if you have them installed, run these commands in your terminal:

```bash
node -v
npm -v
```

If you prefer **Yarn** as the package manager, you can install it using npm:

```bash
npm install --global yarn
```

## Project Setup

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone <repository-url>
cd <project-folder>
```

### 2. Install Dependencies

Once inside the project folder, install the required dependencies using npm (or yarn):

```bash
npm install
```

Or with yarn:

```bash
yarn install
```

### 3. Build the Project

After installing the dependencies, build the project:

```bash
npm run build
```

Or with yarn:

```bash
yarn build
```

This step compiles the project and optimizes it for production.

### 4. Start the Project

To run the project locally after building, use the following command:

```bash
npm start
```

Or with yarn:

```bash
yarn start
```

Once the server is running, you can access the app at:

```
http://localhost:3000/
```

## Development Workflow

During development, you can run the project with hot reloading enabled by using the following command:

```bash
npm run dev
```

Or with yarn:

```bash
yarn dev
```

This will automatically reload the app when file changes are detected. Access the development server at:

```
http://localhost:3000/
```
