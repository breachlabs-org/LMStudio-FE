# LM Studio Chat Interface

A modern, responsive, web-based chat interface designed to interact with the **LM Studio API**. This project features a sleek dark theme, auto-resizing text input, and Markdown support with syntax highlighting for code blocks.

## Features
- **Dark Theme**: Clean and modern UI with a focus on readability.
- **Dynamic Model Selection**: Fetches available models from the LM Studio server and allows users to select a model.
- **Interactive Chat**: Enables users to send messages and receive responses from the selected model.
- **Markdown Rendering**: Parses assistant responses, supporting rich text and code formatting.
- **Syntax Highlighting**: Uses `highlight.js` for beautifully formatted code blocks in assistant responses.
- **Auto-Resizing Input**: The text input field grows dynamically as the user types.
- **Error Handling**: Provides user-friendly error messages for server and response issues.

## Technologies Used
- **HTML5**: Structure and layout.
- **CSS**: Custom styling for a dark theme.
- **JavaScript**: Dynamic functionality and API integration.
- **marked.js**: For Markdown parsing and rendering.
- **highlight.js**: For syntax highlighting in code blocks.

## Requirements
- An LM Studio server running and accessible via API (e.g., `http://YOUR_INSTANCE_HOSTED_LMSTUDIO:1234`).
- A browser capable of running modern JavaScript (e.g., Chrome, Firefox).

## Setup
1. Clone the repository.
2. Open the `index.html` file in your browser.
3. Ensure your LM Studio server is running and configured in the `API_URL` constant within the script.
4. Start chatting and enjoy!

## Screenshots

![image](https://github.com/user-attachments/assets/89715124-c260-44c7-9078-80b7d87c7376)

---

## License
*GNU General Public License v3.0*
