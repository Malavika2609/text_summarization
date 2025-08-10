1. LLaMA 3

    Goal: Understand and extract relevant information from PDF documents using advanced reasoning.

    Action: Feed extracted text from PDFs into LLaMA 3 with prompts for summarization, or Q&A.

    Outcome: Accurate and context-aware responses, even for complex or implicit information.

2. Mistral

    Goal: Perform fast and efficient extraction and summarization of PDF text.

    Action: Process PDF text chunks through Mistral for quick Q&A or concise summaries.

    Outcome: Lightweight, faster responses with good accuracy for straightforward queries.

3. Sentence Transformer + T5 Large

    Goal: Find the most relevant sentences or paragraphs in a PDF for a given query.

    Action: Convert the PDF text into embeddings and index in FAISS.

    Outcome: Retrieves the closest matching sections, enabling summarization.
