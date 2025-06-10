In order to run these notebooks, you will need a GEMINI API KEY. Please follow intstructions at https://ai.google.dev/gemini-api/docs/api-key


This project provides tools to convert textbook content into chunked Knowledge Components (KCs), and trace their correctness across student problem-solving data.

**textbook_to_kcs.ipynb**
Goal:
Takes a textbook (formatted as a CSV with one chapter per row) and outputs a list of chunked knowledge components (KCs) and their corresponding names.

Note:
For downstream use, you should manually refine and assign the relevant KCs to each homework problem. These KCs can then be added as a column to your student dataset.

**extraction_kcs.ipynb**
Goal:
Extracts whether each KC in a problem is used correctly, incorrectly, or not at all.

For further context on the methodology and application, check out our SIGCSE 2025 poster:
https://sigcse2025.sigcse.org/details/sigcse-ts-2025-posters/94/From-Code-to-Concepts-Textbook-Driven-Knowledge-Tracing-with-LLMs-in-CS1 

