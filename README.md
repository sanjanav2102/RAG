# Generative AI Shortcomings

## 1. Hallucinations

- Generative AI models sometimes produce incorrect, misleading, or completely fabricated information.
- These responses may sound confident and believable even when they are wrong.
- Hallucinations occur because AI predicts text patterns rather than truly understanding facts.

### Example
AI may invent fake references, statistics, or historical events.

### Impact
- Can reduce trust and reliability.
- Dangerous in fields like healthcare, finance, or law.

### Mitigation
- Verify outputs with trusted sources.
- Use human review and fact-checking.

---

## 2. Knowledge Attribution

- AI models often do not clearly identify where their information comes from.
- They generate responses from learned patterns in training data rather than citing exact sources.

### Challenges
- Verifying accuracy
- Detecting plagiarism
- Ensuring transparency

### Example
AI gives a technical explanation but cannot specify the original book or article.

### Importance
Proper attribution is essential in academics, journalism, and research.

### Solutions
- Use AI systems integrated with citation tools.
- Use retrieval-based systems for source tracking.

---

## 3. Knowledge Cutoff

- AI models are trained on data only up to a certain date.
- Information after that date may be missing or outdated.

### Example
AI may not know recent events, new technologies, or updated regulations.

### Limitation
Responses may not reflect current real-world information.

### Impact
Less useful for breaking news or rapidly changing industries.

### Solution
Combine AI with internet access or live databases.

---

## 4. Context Window Size

- Context window refers to how much information the AI can remember during a conversation.
- AI can only process a limited amount of text at one time.

### Issues in Long Conversations
- Older information may be forgotten.
- Responses can become inconsistent.

### Example
AI may forget instructions given earlier in a long chat.

### Challenges
Managing lengthy documents or conversations.

### Improvements
- Larger context windows
- Memory systems to retain important information

---
# Retrieval Augmented Generation (RAG)

## Overview
Retrieval Augmented Generation (RAG) is a technique that allows Large Language Models (LLMs) to access external knowledge sources while generating responses.

## Key Points

- RAG provides LLMs with access to external data and documents.
- Helps reduce hallucinations by retrieving accurate information from trusted sources.
- Enables AI systems to reference and use their own knowledge sources.
- Uses embeddings to understand relationships and meanings within text.
- Applies semantic search to find relevant information for answering user queries.

## Benefits

- Improves response accuracy
- Provides more up-to-date information
- Enhances reliability and transparency
- Supports question answering and summarization tasks

## Technologies Used in RAG

- Embeddings
- Vector Databases
- Semantic Search
- Large Language Models (LLMs)

## Summary

RAG combines information retrieval with text generation to create more accurate, context-aware, and reliable AI responses.

