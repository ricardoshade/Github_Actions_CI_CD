# GitHub Actions CI/CD

![Build Status](https://github.com/ricardoshade/Github_Actions_CI_CD/actions/workflows/main.yml/badge.svg)

## Overview

This project is a full-stack application that demonstrates continuous integration and continuous deployment (CI/CD) using GitHub Actions. The application is built with a combination of TypeScript, JavaScript, HTML, and CSS. The backend is powered by Express and MongoDB, while the frontend is built using React and Vite.

## Features

- **CI/CD**: Automated testing, building, and deployment using GitHub Actions.
- **Frontend**: Built with React, Vite, and Bootstrap.
- **Backend**: Built with Express and MongoDB.
- **TypeScript**: Used for type safety and better development experience.
- **Linting**: Enforced code quality with ESLint.
- **Testing**: Unit and integration tests with Vitest.

## Technology Stack

- **Frontend**: React, Vite, TypeScript, Bootstrap
- **Backend**: Express, MongoDB, Mongoose, TypeScript
- **CI/CD**: GitHub Actions
- **Linting**: ESLint
- **Testing**: Vitest

## Getting Started

### Prerequisites

- Node.js (>=14.x)
- npm (>=6.x)
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ricardoshade/Github_Actions_CI_CD.git
   cd Github_Actions_CI_CD
   ```

2. Install dependencies for both the server and client:
   ```bash
   npm run install
   ```

3. Create a `.env` file in the `server` directory and add your MongoDB URI:
   ```bash
   MONGODB_URI=<Your MongoDB URI>
   ```

### Running the Application

#### Development

To start the application in development mode with hot reloading:

```bash
npm run start:dev
```

This will concurrently start the client and server development servers.

#### Production

To build and start the application in production mode:

```bash
npm run build
npm start
```

### Deployment

The application is set up for deployment using Render. The build and start commands are specified in the `package.json` scripts:

- **Build Command**: `npm run client:build && npm run build`
- **Start Command**: `npm start`

### Scripts

- `start`: Build the client and start the server.
- `start:dev`: Start the client and server in development mode.
- `server`: Start the server.
- `server:dev`: Start the server in development mode.
- `client:build`: Build the client.
- `client:dev`: Start the client in development mode.
- `build`: Build the server and client.
- `seed`: Seed the database with initial data.
- `render-build`: Install dependencies and build the application for Render.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

### License

This project is licensed under the ISC License.

### Acknowledgments

- [GitHub Actions](https://github ▋
