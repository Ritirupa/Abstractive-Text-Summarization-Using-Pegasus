# Abstractive-Text-Summarization-Using-Pegasus
Abstractive Text Summarization using Bidirectional LSTM & Pegasus
In NLP, there are two types of summarization: Extractive and Abstractive
1. **Extractive summarization** selects and combines existing sentences from a text document to create a summary.
This approach is relatively simple and computationally efficient, as it does not require any additional understanding of the text.\n
However, it can sometimes result in summaries that are choppy or unreadable, as they are simply a collection of existing sentences.
2. **Abstractive summarization** , on the other hand, generates new sentences that capture the main points of a text document.
This approach requires a deeper understanding of the text, as it must be able to identify the key concepts and relationships between them.
Abstractive summarization can produce more fluent and coherent summaries, but it is also more computationally expensive.\n\n
In this project, I have performed Abstractive Summarization on a news dataset using **Bidirectional LSTM** and **Pegasus** ,which is a pretrained Transformer
and compared their results. Transformers clearly outperform LSTM ,being more context aware with the help of attention mechanism.
