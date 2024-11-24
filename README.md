# LM Studio Chat Interface

A modern, responsive, web-based chat interface designed to interact with the **LM Studio API**. This project features a sleek dark theme, auto-resizing text input, and Markdown support with syntax highlighting for code blocks.

Shout out to the LMStudio Team for providing a very nice interface to use LLM's. 

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

## How to make it work
1. Save the HTML file on your system
2. Configure your LMStudio Instance (Local Server)
3. Enable CORS
4. Enable SERVE ON LOCAL NETWORK
5. LOG PROMPTS AND RESPONSES
6. LOAD YOUR PREFERED MODEL
7. Use your prefered browser to access the HTML file, then choose the model, and asks questions.

## Screenshots

![image](https://github.com/user-attachments/assets/89715124-c260-44c7-9078-80b7d87c7376)
![image](https://github.com/user-attachments/assets/3ef3dc72-42a9-43a6-a600-bbdcef1d29b2)

---

## License
*GNU General Public License v3.0*
