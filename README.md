# Word Document Corrector using Claude

A Google Colab notebook that uses Claude 3.5 Sonnet (Anthropic API) to correct Microsoft Word documents beyond Word's inbuilt capabilities. Simply upload your .docx file and get detailed corrections in colour. 

## Notebook Usage
1. Click <a href="https://colab.research.google.com/github/michellepace/word-document-corrector-claude/blob/main/word_document_corrector_claude.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
1. Then follow these steps in section 'Notebook Usage⭐'
2. 
## Features
- Deep language correction beyond Word's capabilities
- Fixes grammar, spelling, and improves word choice
- Handles large documents (up to 300k words)
- Multi-language support: English, German, French, Italian
- Colour-coded corrections for easy review
- Preserves document structure and meaning
- Comprehensive testing suite to ensure correction integrity

## Example Files
To get a view of what corrections this Notebook makes, view the below files. What is interesting too is to open the input file in Word and see how many corrections it missed compared to the Output file from the notebook.
- Input file: [MyWordDoc.docx](https://michellepace.github.io/word-document-corrector-claude/example-files/MyWordDoc.docx) - sample Word document with various errors.
- Output file: [MyWordDoc.docx.PROCESSED.html](https://michellepace.github.io/word-document-corrector-claude/example-files/MyWordDoc.docx.PROCESSED.html) - corrected version with changes highlighted.

## Notebook Implementation by Section
1. **Setup:** Installs and imports necessary libraries
2. **Pre-processing:** Extracts text from Word, converts to markdown, splits into chunks
3. **Processing:** Sends chunks to Claude for correction
4. **Post-Processing:** Reassembles chunks, creates HTML output
5. **Testing:** Evaluates output, tests prompt, and tests code

For a visual representation of the workflow, see [notebook-workflow-visualised.md](notebook-workflow-visualised.md).

## Testing Framework
Includes automated testing for:
- Document structure preservation
- Content integrity
- Semantic similarity
- Prompt effectiveness
- Code functionality

## License
[License.md](License.md)
