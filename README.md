# CI/CD Full-Stack Application

  ![License: MIT](https://img.shields.io/badge/License-MIT.svg)

  ## Description
  This application is a full-stack CI/CD pipeline that ensures continuous integration and continuous deployment (CI/CD) for a MERN stack project. The project integrates Cypress for component testing and GitHub Actions for automating test runs and deployment. It is designed to run Cypress tests automatically when a pull request is made to the develop branch, and deploy the application to Render when code is merged into the main branch. This ensures that code is tested and deployed in a smooth, automated workflow, supporting high-quality standards for the development process..

  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  - [Deployed-Link](#deployed-link)

  ## Installation
  1. Clone the repository from GitHub.
  2. Install dependencies by running npm install.
  3. Set up MongoDB environment variables.
  4. Start the server with npm run develop.

  ## Usage
  This project is designed to automatically run tests and deploy the app:

- **Run Cypress Tests**: When a pull request is made to the `develop` branch, Cypress tests will automatically execute through GitHub Actions to ensure the functionality of the application.
- **Continuous Deployment**: When changes are merged into the `main` branch, another GitHub Action will trigger the automatic deployment to Render, ensuring the app is always up-to-date with the latest changes.

### GitHub Actions Workflow
- **CI Pipeline**: Tests will be run automatically on each pull request to `develop` to check for failures in the codebase.
- **CD Pipeline**: Once code is merged into `main`, the app is automatically deployed to Render.

  ## License

![License: MIT](https://img.shields.io/badge/License-MIT.svg)

Link: (https://img.shields.io/badge/License-MIT.svg)

  ## Contributing
  Contributions are welcome! If you'd like to contribute, please reach out via the contact information below.

  ## Tests
  To run tests locally, use the following command:
  npm run test
  This will run Cypress tests using the specified browser (e.g., Electron). The tests verify the application's behavior, such as rendering components, form submissions, and other critical UI functionality.


  ## Questions
  If you have any questions, feel free to reach out to ashlinlee98 via [GitHub](https://github.com/ashlinlee98) or email at ashlinlee98@gmail.com.

  ## Deployed Link
    https://cicd-practice-ja5j.onrender.com
  