# Text Analysis and Exploration Tool with AI Daemons

This project integrates AI-powered Daemons into a text editor to assist users with text analysis, bias checking, tone adjustments, and exploration of related topics. The tool uses OpenAI's GPT-3.5 to provide suggestions and insights in real-time.

## Features

- **Text Analysis Daemon**: Analyzes the text and provides feedback on the tone, type of writing, and level of writing.
- **Bias Check Daemon**: Identifies potential biases within the text and suggests counterarguments.
- **Tone Adjustment Daemon**: Offers suggestions to adjust the tone of the text according to user preference.
- **Exploration Daemon**: Lists related topics of discussion and allows users to select a topic for further brainstorming.

## How It Works

The tool uses a Quill.js editor for text input and manipulation. Custom buttons trigger different Daemons:

- **Analyze Text**: Sends the current text to the AI model and retrieves an analysis which is displayed in a modal popup.
- **Check Bias**: Checks the text for biases and provides counterarguments in the modal popup.
- **Apply Tone**: Allows users to input a desired tone and retrieves a version of the text with that tone applied, presented in the modal popup.
- **Explore Topics**: Generates a list of related topics based on the text content. Users can click on a topic to prompt the AI to brainstorm on that topic.

## Usage

1. Input your text into the Quill.js editor.
2. Use the toolbar buttons to interact with the different Daemons.
3. Engage with the modal popups to refine your text or explore related topics.
