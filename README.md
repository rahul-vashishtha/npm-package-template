<h1 style="text-align: center">@rahulv.dev/npm-package-template</h1>

<p style="text-align: center">A template for creating and publishing TypeScript-based npm packages, with a focus on type safety, testing, and automated releases.</p>

<br />

<p align="center">
  <a href="https://github.com/rahul-vashishtha/npm-package-template/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/rahul-vashishtha/npm-package-template?style=social">
  </a>
  <a href="https://github.com/rahul-vashishtha/npm-package-template/blob/main/LICENSE.md">
    <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
  </a>  
</p>

## Features

-   **TypeScript**: Develop your package with TypeScript for enhanced type safety.
-   **Testing with Vitest**: Write and run tests using Vitest for reliable and fast test execution.
-   **Build with Vite**: Build your package using Vite for optimized bundling and performance.
-   **Automated Releases**: Use Semantic Release to automate the release process, ensuring consistent versioning and changelog generation.

## Getting Started

To create your own npm package using this template:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/rahul-vashishtha/npm-package-template.git
    cd npm-package-template
    ```

2. **Install Dependencies**:

    ```bash
    npm install
    ```

3. **Start Development**:

    Start the development server:

    ```bash
    npm run dev
    ```

4. **Build the Package**:

    Compile TypeScript and bundle your package with Vite:

    ```bash
    npm run build
    ```

5. **Run Tests**:

    Execute the test suite:

    ```bash
    npm run test
    ```

## Publishing

To publish the package to npm, ensure you have configured your npm credentials, and then run:

```bash
npm publish
```

## Configuration

### TypeScript

Customize your TypeScript settings by editing `tsconfig.json`.

### Semantic Release

Semantic Release is set up to manage versioning and releases automatically. Configure the release settings in `package.json` and `.releaserc` if needed.

## Contributing

Contributions are welcome! Please submit issues and pull requests for any improvements or suggestions.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

-   Author: Rahul Vashishtha
-   Website: [rahulv.dev](https://rahulv.dev)
-   Repository: [GitHub](https://github.com/rahul-vashishtha/npm-package-template)

## Bugs and Issues

For any bugs or issues, please open a new issue on the [GitHub Issues](https://github.com/rahul-vashishtha/npm-package-template/issues) page.

---

Feel free to modify and use this template to kickstart your npm package development!
