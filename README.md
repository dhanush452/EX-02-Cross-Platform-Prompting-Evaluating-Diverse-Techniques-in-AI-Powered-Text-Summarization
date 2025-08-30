# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## NAME : DHANUSH E
## REG : 212222060041

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

# Summaries by Prompting Strategy (ChatGPT Example)

# Zero-shot Prompting

Summary:
Blockchain is a secure, digital record-keeping system where data is stored in blocks linked together. Once added, data cannot be altered, making it reliable. Unlike centralized databases, blockchain is decentralized, with many computers verifying transactions. This increases trust and prevents fraud. It is most commonly used in cryptocurrencies like Bitcoin, and in supply chains where products can be tracked from production to delivery. Governments are also testing blockchain for secure voting.

# Few-shot Prompting (given 2 examples of simple summaries first)

Summary:
Blockchain is like a digital notebook shared across many computers. Each page (block) is connected, forming a chain. Once written, the notes cannot be erased, ensuring security. Instead of one authority controlling it, everyone in the network helps verify the records, building trust. Real-world uses include Bitcoin, where people send money without banks, and supply chain tracking, which ensures products are genuine. This makes blockchain important in finance, business, and government services.

# Chain-of-Thought Prompting (step-by-step reasoning hidden, but simplified output)

Summary:
Blockchain is a decentralized technology for recording data securely. Information is stored in linked blocks that cannot be altered once confirmed, ensuring transparency and trust. Because multiple computers validate the records, no single authority controls it. For example, cryptocurrencies like Bitcoin use blockchain to allow direct transactions without banks. In logistics, companies use it to track goods from production to delivery, reducing fraud. Some governments also explore it for voting systems. Overall, blockchain is a foundation for secure, transparent, and reliable digital applications.

# Role-based Prompting (as “teacher explaining to undergraduates”)

Summary:
Think of blockchain as a chain of digital blocks, like Lego pieces connected in order. Each block stores information, and once it’s locked in, nobody can change it. Unlike a normal database controlled by one person, blockchain is shared across many computers, making it harder to cheat and easier to trust. A common example is Bitcoin, where blockchain records transactions without a bank. Another example is in supply chains, where companies track food or medicine to ensure they are safe and genuine. Governments are also testing it for secure voting. Blockchain is important because it makes data management more transparent, secure, and fair.


| Prompting Technique  | Accuracy   |  Coherence   |           Simplicity           | Speed   |           User Experience          |
| -------------------- | ---------- | ------------ | ------------------------------ | ------- | ---------------------------------- |
| Zero-shot            | High       | Good         | Moderate (a bit technical)     | Fast    | Simple, but less beginner-friendly |
| Few-shot             | High       | Very good    | High (uses analogies)          | Medium  | Engaging, student-friendly         |
| Chain-of-Thought     | Very High  | Very good    | Medium-High (clear but formal) | Slower  | Useful for clarity, less playful   |
| Role-based (Teacher) | High       | Excellent    | Very High (simple analogies)   | Medium  | Feels natural for undergraduates   |


# Key Takeaways

Best Overall for Undergraduates: Role-based prompting (clear, simple, engaging).

Most Accurate & Detailed: Chain-of-thought.

Fastest & Adequate: Zero-shot.

Best Balance of Simplicity + Engagement: Few-shot with analogies.

<img width="1024" height="1536" alt="ChatGPT Image Aug 29, 2025, 01_50_32 PM" src="https://github.com/user-attachments/assets/569bd510-8b4d-4690-a5d3-d2e74d3cd9d5" />


## Visual comparison:
<img width="2358" height="2092" alt="prompting_techniques_radar" src="https://github.com/user-attachments/assets/5f10345f-9de6-49a4-98bc-ab0f9b704aa4" />


## Result
The results of this evaluation will be presented in a structured format, providing a clear comparison of the effectiveness of different prompting techniques across the chosen AI platforms for the task of summarizing the technical article on "The Basics of Blockchain Technology."
