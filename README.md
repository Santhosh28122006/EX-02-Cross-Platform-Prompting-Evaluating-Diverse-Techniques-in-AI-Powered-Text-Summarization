# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
# Comparative Study of Prompting Strategies Across AI Platforms

## Methodology

### 1. Article Selection
A technical article of approximately 500 words titled **“The Basics of Blockchain Technology”** was selected for the experiment. The article discussed major blockchain concepts such as decentralization, distributed ledgers, cryptographic security, mining, and practical applications.

### 2. Prompting Techniques Used
Four prompting methods were designed and tested:

#### Zero-shot Prompting
The AI model was directly instructed to summarize the article without giving any examples.

#### Few-shot Prompting
Two to three example summaries of similar technical articles were provided before asking the AI to generate a summary.

#### Chain-of-Thought Prompting
The model was instructed to logically analyze the article step-by-step before producing the summary.

#### Role-based Prompting
The AI was assigned a specific role, such as *“a university professor explaining blockchain concepts to first-year students.”*

### 3. AI Platforms Selected
The following AI systems were used in the experiment:

- ChatGPT (OpenAI)
- Gemini (Google)
- Claude (Anthropic)
- Copilot (Microsoft)

### 4. Execution Process
For each AI platform, all prompting techniques were applied using the same blockchain article as input. The generated summaries were recorded, and the response generation time was noted.

### 5. Evaluation Metrics
Each generated summary was evaluated using the following criteria:

- **Accuracy** – Correct representation of the article’s main points.
- **Coherence** – Logical structure and readability of the summary.
- **Simplicity** – Ease of understanding for undergraduate students.
- **Speed** – Time taken to generate the response.
- **User Experience (UX)** – Ease of interaction and convenience in copying or saving the output.

---

# Results and Comparison

| Platform | Prompt Type | Accuracy | Coherence | Simplicity | Speed | UX | Total (/25) |
|-----------|-------------|-----------|------------|-------------|-------|----|--------------|
| ChatGPT | Zero-shot | 4 | 4 | 4 | 5 | 5 | 22 |
| ChatGPT | Few-shot | 5 | 5 | 5 | 4 | 5 | 24 |
| ChatGPT | Chain-of-Thought | 5 | 5 | 4 | 3 | 5 | 22 |
| ChatGPT | Role-based | 5 | 5 | 5 | 4 | 5 | 24 |
| Gemini | Zero-shot | 3 | 3 | 3 | 5 | 4 | 18 |
| Gemini | Few-shot | 4 | 4 | 4 | 4 | 4 | 20 |
| Claude | Chain-of-Thought | 5 | 5 | 5 | 4 | 4 | 23 |
| Claude | Role-based | 5 | 5 | 5 | 4 | 5 | 24 |
| Copilot | Zero-shot | 3 | 3 | 3 | 5 | 4 | 18 |
| Copilot | Few-shot | 4 | 4 | 4 | 4 | 4 | 20 |

---

## Result

The study demonstrated that advanced prompting strategies improved the quality of AI-generated summaries. Among the tested methods, **Few-shot Prompting** and **Role-based Prompting** consistently produced better results in terms of clarity, structure, and simplicity.

Both **Claude with Role-based Prompting** and **ChatGPT with Few-shot Prompting** achieved the highest score of **24/25**. These combinations generated summaries that were highly accurate, coherent, and easy for undergraduate students to understand.

The experiment also highlighted that properly designed prompts significantly enhance AI performance, especially when summarizing technical content for educational purposes.


