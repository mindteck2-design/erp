# Project Documentation

## Overview
This document outlines the project structure of the `mindteck2-design/erp` repository, including both the client and server directories.

## Project Structure

```
erp/
├── client/
│   ├── src/                  # Source files for the client application
│   │   ├── components/       # React components
│   │   ├── styles/           # CSS or SCSS files
│   │   ├── utils/            # Utility functions
│   │   └── index.js          # Main entry point for client app
│   ├── public/               # Public assets
│   ├── package.json          # Client dependencies
│   └── README.md             # Client-specific documentation
│
├── server/
│   ├── src/                  # Source files for the server application
│   │   ├── controllers/       # Request handlers
│   │   ├── models/            # Database models
│   │   ├── routes/            # API routes
│   │   └── index.js          # Main entry point for server app
│   ├── config/               # Configuration files
│   ├── package.json          # Server dependencies
│   └── README.md             # Server-specific documentation
│
└── README.md                # Overall project documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mindteck2-design/erp.git
   cd erp
   ```

2. Install dependencies:
   - For client:
   ```bash
   cd client
   npm install
   ```
   - For server:
   ```bash
   cd server
   npm install
   ```

## Usage

- Run the client:
  ```bash
  cd client
  npm start
  ```

- Run the server:
  ```bash
  cd server
  npm run start
  ```

## Contributing

Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Acknowledgments

- Hat tip to anyone whose code was used as inspiration.
- Inspiration from [React documentation](https://reactjs.org/docs/getting-started.html) and related resources.
