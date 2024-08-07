# SVG_Logo_Maker

SVG Logo Maker is a Node.js command-line application that enables users to generate customizable SVG logos. Users can specify text, text color, shape (circle, triangle, or square), and shape color to create unique logos that are saved as SVG files.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Testing](#testing)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Walkthrough Video](#walkthrough-video)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## Installation

To install and run SVG Logo Maker locally, follow these steps:

1. **Clone the repository** from GitHub:

   ```bash
   git clone https://github.com/Meadoughnut/SVG_Logo_Maker.git
   ```

2. **Navigate** into the project directory:

   ```bash
   cd SVG_Logo_Maker
   ```

3. **Install dependencies** using npm:

   ```bash
   npm install
   ```

## Usage

To use SVG Logo Maker:

1. **Run the application** using Node.js:

   ```bash
   node index.js
   ```

2. **Follow the prompts** to enter the text for the logo (up to 3 characters), select text color, choose a shape (circle, triangle, or square), and set the shape's color.

3. **Once all prompts are completed**, an SVG file named `examples.svg` will be generated in the root directory of the project.

4. **Open** `examples.svg` **in a web browser** to view the generated logo.

## File Structure

The project structure is organized as follows:

```
.
├── examples/           # Directory for example SVG files generated by the application
├── lib/                # Directory containing shape classes and their tests
│   ├── shapes.js       # Definition of Circle, Triangle, and Square classes
│   └── shapes.test.js  # Jest tests for shape classes
├── .gitignore          # Specifies files and directories ignored by Git
├── index.js            # Main entry point of the Node.js application
├── package.json        # Project metadata, dependencies, and scripts
└── README.md           # Project overview, setup instructions, and usage guidelines
```

## Testing

Unit tests for the shape classes (`Circle`, `Triangle`, and `Square`) are implemented using Jest. To run the tests, use the following command:

```bash
npm test
```

The tests ensure that each shape's `render` method generates the correct SVG string based on the specified color.

## Technologies Used

- **Node.js**: Backend JavaScript runtime environment.
- **JavaScript**: Programming language used for application logic.
- **Inquirer**: Command-line interface library for user prompts.
- **Jest**: JavaScript testing framework for unit testing.

## Features

- Interactive command-line interface for generating SVG logos.
- Customizable text and shape options (text, text color, shape, shape color).
- Outputs SVG files that can be opened and displayed in web browsers.
- Modular code structure with unit tests to ensure reliability.

## Walkthrough Video

For a detailed walkthrough of how to use SVG Logo Maker and see it in action, watch our [Walkthrough Video](https://app.screencastify.com/v3/watch/1OepJFx9IyfkO0yksWUI).

## Contributing

Contributions are welcome! To contribute to SVG Logo Maker, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

## Contact

For questions or feedback regarding SVG Logo Maker, feel free to contact us at:

- Email: meadinmenbere488@gmail.com


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---




