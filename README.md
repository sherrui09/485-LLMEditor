# Text Analysis and Exploration Tool with AI Daemons

This project integrates AI-powered Daemons into a text editor to assist users with text analysis, bias checking, tone adjustments, and exploration of related topics. The tool uses OpenAI's GPT-3.5 to provide suggestions and insights in real-time.

## Features

- **Text Analysis**: This feature leverages AI to analyze the text's tone, writing style, and sophistication level. It offers options for constructive feedback to help users understand and improve their writing quality in multiple areas.
- **Bias Detection**: Identifies and highlights biased sections in the text. It also offers explanations for the identified biases, aiding in the creation of more balanced and objective content.
- **Tone Adjustment**: Allows users to specify a desired tone (e.g., formal, persuasive) and rewrites the text to match this tone, enhancing the text's impact and readability.
- **Topic Exploration**: Suggests relevant topics based on the text content. Users can select a topic to generate additional, contextually relevant content, fostering deeper exploration and expansion of ideas.
- **Interactive UI**: Features a user-friendly interface with a rich text editor and responsive modal popups for real-time feedback and suggestions.
- **Real-Time Editing and Suggestions**: Offers immediate feedback and text enhancements, streamlining the writing and editing process.


## How It Works

The tool uses a Quill.js editor for text input and manipulation. Custom buttons trigger different Daemons:

- **Analyze Daemon**: Triggered by the 'Analyze Text' button, this daemon analyzes the text's tone and writing level, providing a detailed breakdown and suggestions for improvement.
- **Bias Check Daemon**: Activated by the 'Check Bias' button, this daemon scans the text for potential biases, marks biased sections, and explains why they might be considered biased, promoting fair and unbiased writing.
- **Exploration Daemon**: Initiated by the 'Explore Topics' button, this daemon suggests related topics for further exploration based on the text's content, encouraging users to delve deeper into their subject matter.

## Usage

1. **Input Text**: Enter your text into the Quill.js editor.
2. **Interact with Daemons**: Utilize the toolbar buttons to engage with the different AI Daemons for analysis, bias checking, and topic exploration.
3. **Refine and Explore**: Engage with the modal popups to receive suggestions and insights. Refine your text or explore suggested topics to enhance your content.
