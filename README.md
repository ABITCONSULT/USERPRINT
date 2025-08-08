# USERPRINT
USERPRINT is a scalable, zero-shot framework that personalizes large language models (LLMs) by generating persona vectors from dialogues. It evaluates model performance across different conditions (chat, persona, combined), improving semantic and lexical alignment, and provides insights into robust, transferable LLM adaptation.

Key Features:
Zero-shot Persona Extraction: Automatically generates persona vectors from open-domain dialogues, allowing LLMs to adapt to users' unique traits and behaviors without the need for retraining.

Cross-Domain Evaluation: Evaluates personalization across multiple datasets, models, and conditions, providing detailed insights into semantic alignment (BERTScore) and lexical fidelity (ROUGE-L).

Consistency and Robustness: Proposes novel metrics for evaluating the robustness of personalized LLMs across various prompting strategies and real-world conditions.

Transferable Personalization: Achieves personalization without altering model weights, offering a scalable, flexible solution for various LLMs and use cases.

Evaluation and Results:
The framework evaluates multiple models (such as qwen3-latest, deepseek-r1, gpt4, and others) across different personalization techniques (chat-based, persona-driven, and combined chat-persona strategies).

The results showcase consistent improvements in personalization quality across multiple LLMs, with detailed evaluations based on BERTScore and ROUGE-L metrics.

Leaderboard: The performance of the models across various personalization conditions is summarized in an interactive leaderboard, allowing easy comparison of different LLMs' effectiveness in personalization tasks.

Applications:
Personalized AI Assistants: Enhancing user experience by tailoring responses based on individual persona traits.

Chatbots: Making conversational agents more context-aware and adaptable to diverse user behaviors.

Behavioral Models: Investigating how models respond to various personalization inputs and adjusting their behavior accordingly.

Future Work:
Future extensions of USERPRINT include integrating human evaluations, expanding to multilingual and multimodal contexts, and developing robustness probes for challenging models with evolving persona profiles.
