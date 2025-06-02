# CattyCode Editor

CattyCode is a simple web-based Blockly editor that allows users to create JavaScript code visually by dragging and connecting blocks. This editor uses Google's Blockly library to provide an easy-to-use, block-based programming interface for beginners or anyone looking to create code without writing it manually.

## Features
- **Blockly Integration**: Visual block-based code creation.
- **JavaScript Output**: Generate JavaScript code from Blockly blocks.
- **Interactive Workspace**: A live editor that lets you design your code and run it in real-time.
- **Customizable Categories**: Variables, Lists, Loops, Logic, Math, Text, and Functions categories for various programming tasks.

## Live Demo
You can try out the editor directly here: [CattyCode Editor](https://cattycode.github.io/editor/).

## Setup Instructions

### Prerequisites
- An internet connection (for loading external libraries and resources).

### How to Use
1. Open the live demo at [CattyCode Editor](https://cattycode.github.io/editor/).
2. Drag and drop blocks from the toolbox to the workspace.
3. Click the **Run Code** button to execute the generated JavaScript code.

### Customizing the Toolbox
You can customize the blocks and categories available in the Blockly workspace. The toolbox in the code currently includes categories such as:
- **Variables**: Create and manage variables.
- **Lists**: Work with lists (arrays).
- **Loops**: Add loop structures for iteration.
- **Logic**: Perform logical operations and comparisons.
- **Math**: Include mathematical operations.
- **Text**: Manipulate and print strings.
- **Functions**: Create reusable functions.

To customize the blocks, edit the `toolbox` variable in the JavaScript section of the code to add or remove blocks as needed.

### Running the Generated Code
- After designing your blocks, click the **Run Code** button.
- The editor will generate JavaScript code from the blocks and execute it in your browser using `eval()`.
- If there's an error in the generated code, it will be logged in the browser's console.

## Technologies Used
- **HTML5** for the structure.
- **CSS** for styling and layout.
- **JavaScript** for functionality.
- **Blockly**: A library from Google that helps create visual block-based programming environments.

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements
- [Blockly](https://developers.google.com/blockly) - For providing the library that powers the visual programming editor.
- [Unpkg](https://unpkg.com/) - For serving the libraries via CDN.
