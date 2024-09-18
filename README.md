# CalX

CalX is a lightweight vanilla JavaScript app designed for creating and managing customizable calendar events with a sleek, user-friendly interface. It integrates seamlessly with various tools and uses AI to optimize scheduling and task management.

## Features

- **Automated Task Scheduling**: AI analyzes deadlines, meetings, and tasks to suggest optimal time slots, avoiding overlaps and prioritizing important tasks.
- **Seamless Integration**: Automatically integrates deadlines for tasks from DocX, reminders for emails from MailX, and due dates for document signatures or reviews.
- **Smart Reminders**: Provides notifications for upcoming deadlines and meetings, with AI-driven recommendations for efficient time management.

## Installation

To get started with CalX, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/IBMTechXChange/CalX.git
   cd CalX
   ```

2. **Install Dependencies**

   Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed. Then run:

   ```bash
   npm install
   ```

## Development

To start the development server and view the app locally:

```bash
npm run dev
```

The development server will open your default web browser with the app running on [http://localhost:3000](http://localhost:3000).

## Building for Production

To create a production build of the app:

```bash
npm run build
```

This command will generate optimized production files in the `dist` directory.

## Deployment

To deploy the app to GitHub Pages:

1. Build the project:

   ```bash
   npm run build
   ```

2. Deploy:

   ```bash
   npm run deploy
   ```

This will push the `dist` directory to the `gh-pages` branch of the repository.

## Code Quality

- **Linting**: Run the following commands to check code quality and fix issues:
  
  ```bash
  npm run lint
  npm run lint:fix
  ```

- **Stylelint**: To check and fix CSS code quality issues:

  ```bash
  npm run stylelint
  npm run stylelint:fix
  ```

## Configuration

The project uses [Webpack](https://webpack.js.org/) for bundling and [ESLint](https://eslint.org/) for JavaScript linting. Configuration files are provided in the root of the project.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For any questions or feedback, please contact [Salik Uddin](mailto:uddinsalik@outlook.com).

## Acknowledgments

- [Webpack](https://webpack.js.org/)
- [ESLint](https://eslint.org/)
