# Fix Word Doc Claude

## Description
Fix Word Doc Claude is an AI-powered proofreading tool that uses Anthropic's Claude Sonnet model to correct and enhance Word documents. It catches subtle language and style errors often missed by standard spell-checkers, supporting multiple languages including English, German, Italian, and French.

## Features
- Processes large documents (up to 42,000 words)
- Supports multiple languages
- Highlights corrections in color for easy identification
- Preserves original document semantic meaning and structure
- Includes comprehensive testing and evaluation

## Installation
1. Open the notebook (Fix_Word_Doc_Claude.ipynb)[Fix_Word_Doc_Claude.ipynb]
2. Click 'open in colab' > File > Save copy
4. Running the notebook will install required libraries
5. Set up an [Anthropic API key](https://console.anthropic.com/settings/keys) (Pro account required)

## Usage
1. Open the notebook in Google Colab
2. Run all cells
3. Input your Anthropic API key when prompted
4. Specify the full path to your Word document in Google Drive
5. The notebook will process your document and provide a corrected HTML version
6. The corrected HTML file will be automatically downloaded via your browser AND saved into your Google Drive
7. The corrected HTML file will be automatically saved into the same Google Drive directory as your original Word document

## Example Input and Output
To give you an idea of how the notebook works, we've provided an example:
- Input file: [MyWordDoc.docx](https://docs.google.com/document/d/1qoOZcVuk9xe-FTUVqjZEQPJDVpx3R6Gf) - This is a sample Word document with various errors.
- Output file: [MyWordDoc.docx.PROCESSED.html](https://michellepace.github.io/ai-ml-notebook-explorations/Fix_Word_Doc_with_Claude/MyWordDoc.docx.PROCESSED.html) - This is the corrected version of the document in HTML format, with changes highlighted.

You can view these files to see the kind of corrections and improvements the notebook makes.

## Project Structure
1. Setup: Installs and imports necessary libraries
2. Pre-processing: Extracts text from Word, converts to markdown, splits into chunks
3. Processing: Sends chunks to Claude for correction
4. Post-Processing: Reassembles chunks, creates HTML output
5. Testing: Evaluates output, tests prompt, and tests code

## Workflow Diagram
To better understand the process flow of this notebook, refer to our [Notebook Workflow Diagram](Notebook_Workflow_Diagram.md). This Mermaid diagram visually represents the main steps in the document processing pipeline, including preprocessing, API processing, and testing stages.

## Testing
The notebook includes comprehensive testing:
- Output file evaluation (structure preservation, word count, semantic similarity)
- Prompt testing
- Code testing

## Without an Anthropic Pro Account
If you don't have an Anthropic Pro account, you can still learn from this notebook:
- Each code block in the notebook has a screenshot of example output beneath it.
- Start by scanning the Table of Contents for an overview.
- Focus on the explanations between code blocks – there's no need to read the code itself.
- You can view the example input ([MyWordDoc.docx](https://docs.google.com/document/d/1qoOZcVuk9xe-FTUVqjZEQPJDVpx3R6Gf)) and output ([MyWordDoc.docx.PROCESSED.html](https://michellepace.github.io/ai-ml-notebook-explorations/Fix_Word_Doc_with_Claude/MyWordDoc.docx.PROCESSED.html)) files to see the kind of improvements the notebook makes.

## License
This project is licensed under the MIT License - see the see the [LICENSE](../LICENSE) file for details.

## Acknowledgements
This project was developed with assistance from Anthropic's Claude AI. Special thanks to the Slack community members who gave me the belief I could take my first delve into programmatic AI: Aaron and Unmesh.
