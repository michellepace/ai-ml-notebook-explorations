# Notebook-01: Fix Word Doc Claude

## Description
Fix Word Doc Claude is an AI-powered proofreading tool that uses Anthropic's Claude Sonnet model to correct and enhance Word documents. It catches subtle language and style errors often missed by standard spell-checkers, supporting multiple languages including English, German, Italian, and French.

## Features
1. Uses the Claude API for intelligent text processing
1. Handles large-scale text correction in multiple languages
1. Highlights corrections in colour for easy identification
1. Preserves original document semantic meaning and structure
1. Includes comprehensive testing and evaluation
1. Future potential: writing tone adjustments and correction

## Notebook Usage
1. Open the notebook [Fix Word Doc Claude](Fix_Word_Doc_Claude.ipynb)
2. Click 'Open in Colab' > File > Save a copy
3. Follow these steps in the notebook: [Notebook Usage⭐](https://colab.research.google.com/github/michellepace/ai-ml-notebook-explorations/blob/main/notebook-01/Fix_Word_Doc_Claude.ipynb#scrollTo=Notebook_Usage_)

## Example Input and Output
You can view these files to see the kind of corrections and improvements the notebook makes (beyond what Word can do).
- Input file: [MyWordDoc.docx](https://michellepace.github.io/ai-ml-notebook-explorations/notebook-01/example-input-output/MyWordDoc.docx) - sample Word document with various errors.
- Output file: [MyWordDoc.docx.PROCESSED.html](https://michellepace.github.io/ai-ml-notebook-explorations/notebook-01/example-input-output/MyWordDoc.docx.PROCESSED.html) - corrected version with changes highlighted.

## Notebook Structure
1. **Setup:** Installs and imports necessary libraries
2. **Pre-processing:** Extracts text from Word, converts to markdown, splits into chunks
3. **Processing:** Sends chunks to Claude for correction
4. **Post-Processing:** Reassembles chunks, creates HTML output
5. **Testing:** Evaluates output, tests prompt, and tests code

## Notebook Workflow Diagram
To better understand the process flow of this notebook, refer to our [Notebook Workflow Picture](notebook-workflow-picture.md). This Mermaid diagram visually represents the main steps in the document processing pipeline, including preprocessing, API processing, and testing stages.

## Notebook Testing
The notebook includes comprehensive testing:
- "Output file" testing (structure preservation, word count, semantic similarity)
- Prompt testing
- Code testing

## License
This project is licensed under the MIT License - see the see the [LICENSE](../License.md) file for details.
