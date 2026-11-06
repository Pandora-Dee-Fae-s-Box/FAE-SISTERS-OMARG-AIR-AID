# Model Name: Historical Universal Memory (CHUM)

## Purpose:

The CHUM model is designed to interact with a user's exported conversation history data. It uses a local RAG/vector-search tool, a web-search tool, and a web-fetch tool to search, retrieve, and present information from the user's past conversations.

## How it works:

1. **the local document search**: This tool is used to read and search through the user's conversation history, which has been converted into PDF format and split into manageable segments.

2. **web search**: This tool is used to search the internet for additional, up-to-date information related to the topics discussed in the user's conversation history.

3. **web fetch**: This tool is used to visit specific web pages that may contain relevant information, based on the results from the web search.

## Usage:

1. Convert your conversation history (in .json format) into a PDF file using an online converter tool.

2. Split the PDF file into 200-page segments using a tool like "i love pdf".

3. Upload the PDF segments to a local RAG/vector-search tool to get the document IDs.

4. Use the CHUM model to interact with your conversation history. The model will use the a local RAG/vector-search tool tool to search through your conversation history, the a web-search tool tool to find additional information on the internet, and the a web-fetch tool tool to visit specific web pages for more details.

## Example:

User: "Find all mentions of 'quantum mechanics' in my conversation history."

CHUM: (Uses a local RAG/vector-search tool to search the user's conversation history for mentions of 'quantum mechanics', then uses a web-search tool to find recent information about 'quantum mechanics' on the internet, and finally uses a web-fetch tool to visit a specific web page with more details about 'quantum mechanics'.)
