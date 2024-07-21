
# Umbraco Vite Boilerplate

Welcome to the Umbraco Vite Boilerplate! This project provides a template for integrating Vite, a modern front-end build tool, with Umbraco, a popular CMS. This boilerplate aims to streamline your development workflow with fast builds and hot module replacement (HMR) out of the box.

## Features

- **Vite Integration**: Leverage Vite’s fast development server and optimized build process.
- **Hot Module Replacement (HMR)**: Enjoy instant updates in your browser as you develop.
- **Modern JavaScript Support**: Write ES6+, TypeScript, and JSX with minimal configuration.
- **Optimized Production Builds**: Benefit from advanced optimizations like tree-shaking and code splitting.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v20 or higher)
- [Umbraco CMS](https://umbraco.com/) (v14 or higher)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/semirhamid/umbraco-vite-boilerplate.git
   cd umbraco-vite-boilerplate
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Run the development server:**
   ```sh
   npm run dev
   ```

4. **Build for production:**
   ```sh
   npm run build
   ```

## Configuration

### Vite Config

The Vite configuration is located in `vite.config.js`. You can customize it according to your project requirements. By default, the build output is directed to the `wwwroot` directory of your Umbraco project.

### Umbraco Integration

Ensure that your Umbraco views reference the bundled assets from the `wwwroot` directory. You can update the paths in your templates as needed.

### Scripts

- **`npm run dev`**: Starts the Vite development server with HMR.
- **`npm run build`**: Builds the project for production, outputting files to `wwwroot`.

## Pushing to the Main Branch

If you are setting up the repository and want to push to the `main` branch, follow these steps:

1. **Create and switch to the `main` branch:**
   ```sh
   git checkout -b main
   ```

2. **Add your changes:**
   ```sh
   git add .
   ```

3. **Commit your changes:**
   ```sh
   git commit -m "Initial commit"
   ```

4. **Set the upstream and push to the remote repository:**
   ```sh
   git push --set-upstream origin main
   ```

## Contributing

We welcome contributions! To contribute, please follow these steps:

1. **Fork the repository:**
   Click on the "Fork" button at the top right of this page.

2. **Clone your forked repository:**
   ```sh
   git clone https://github.com/semirhamid/umbraco-vite-boilerplate.git
   cd umbraco-vite-boilerplate
   ```

3. **Create a new branch:**
   ```sh
   git checkout -b feature/your-feature-name
   ```

4. **Make your changes and commit them:**
   ```sh
   git add .
   git commit -m "Add your message here"
   ```

5. **Push to your branch:**
   ```sh
   git push origin feature/your-feature-name
   ```

6. **Create a pull request:**
   Go to the original repository on GitHub and click on the "New Pull Request" button.

### Collaboration Rules

- **Write clear, concise commit messages.**
- **Follow the existing code style.**
- **Test your changes before submitting a pull request.**
- **Be respectful and considerate in your communication.**

## Raising Issues

If you encounter any issues or have suggestions for improvements, please open an issue on GitHub. Follow these steps:

1. **Go to the Issues tab in the repository.**
2. **Click on the "New Issue" button.**
3. **Provide a clear and descriptive title for the issue.**
4. **Describe the problem or suggestion in detail.**
5. **Include any relevant screenshots or code snippets.**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Vite](https://vitejs.dev/)
- [Umbraco CMS](https://umbraco.com/)

---

Happy coding!
```
