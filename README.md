EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
NAME: MOHAN K
Reg.no:212225240087
AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
Evaluation of Prompting Techniques for
Text Summarization Across AI Platforms

1. Aim of the Experiment
2. 
To evaluate and compare the effectiveness of different prompting techniques—zeroshot, few-shot, chain-of-thought, and role-based prompting—across multiple AI
platforms (ChatGPT, Gemini, Claude, and GitHub Copilot) for summarizing a 500-word
technical article titled “The Basics of Blockchain Technology” for undergraduate
students.

4. Task Description
The task involves generating a concise, student-friendly summary (120–150 words) of a
technical blockchain article. The same input article and the same prompt (per
technique) were used across all AI platforms to ensure fairness.

6. Prompting Techniques with Outputs from Different
AI Platforms

3.1 Zero-Shot Prompting

Single Prompt Used
The AI was instructed to summarize the blockchain article in simple terms suitable for
undergraduate students, without providing any examples or additional guidance.
Outputs

ChatGPT Output (Zero-Shot):

Blockchain is a technology that allows data to be stored securely across multiple
computers instead of a single central system. Information is grouped into blocks, which
are linked together using cryptographic hashes to form a chain. Once data is added, it
cannot be easily changed, making blockchain reliable and transparent. It is commonly
used in cryptocurrencies like Bitcoin but also has applications in healthcare, supply
chains, and finance.

Gemini Output (Zero-Shot):

Blockchain technology is a decentralized system used to record digital transactions.
Each block contains data that is verified by a network of computers. This system
improves transparency and reduces the risk of fraud. Blockchain is widely known for
supporting cryptocurrencies but is also useful in other digital record systems.

Claude Output (Zero-Shot):

Blockchain is a digital record-keeping system where information is stored across many
computers. Data is organized into blocks that are securely connected, making the
system transparent and difficult to alter. It is best known for cryptocurrencies but can
also support secure data sharing in many industries.

GitHub Copilot Output (Zero-Shot):

Blockchain is a distributed ledger technology that stores data in blocks and connects
them using cryptographic methods. It is mainly used in cryptocurrency systems.
Zero-Shot Analysis
Zero-shot prompting produced fast results, but the summaries lacked depth and
educational clarity, especially in Copilot.

3.2 Few-Shot Prompting

Single Prompt Used
The AI was first shown a short example summary of a technical topic (cloud computing)
and then instructed to summarize the blockchain article in a similar simple and concise
style.

Outputs
ChatGPT Output (Few-Shot):

Blockchain technology is a decentralized system that stores information across many
computers. Data is grouped into blocks and linked using cryptographic techniques. This
design ensures security, transparency, and trust without relying on a central authority.
Blockchain is commonly used in cryptocurrencies and is expanding into areas such as
supply chain management and digital identity.

Gemini Output (Few-Shot):

Blockchain is a technology that records data in a secure and distributed manner. Each
block is verified by a network and added to a chain, making records difficult to change. It
is widely used for cryptocurrencies and other digital systems that require transparency.

Claude Output (Few-Shot):

Blockchain is a decentralized technology that allows data to be stored securely across
a network of computers. Information is added in blocks that are linked together,
ensuring transparency and preventing unauthorized changes. It is widely used in digital
currencies and other applications requiring secure data sharing.

GitHub Copilot Output (Few-Shot):

Blockchain stores data across multiple systems using linked blocks. It improves data
security and transparency and is mainly used in digital currency systems.
Few-Shot Analysis
Few-shot prompting improved structure and clarity across all platforms, with Claude and
ChatGPT showing the most balanced summaries.

3.3 Chain-of-Thought Prompting

Single Prompt Used
The AI was instructed to first identify key blockchain concepts, then briefly explain them,
and finally produce a simplified summary for undergraduate students.
Outputs

ChatGPT Output (Chain-of-Thought):

Blockchain works by storing data in blocks that are linked together using cryptographic
hashes. These blocks are shared across many computers, creating a decentralized
system. This structure improves security, transparency, and trust. Blockchain is mainly
used for cryptocurrencies but also supports applications like supply chain tracking and
secure data storage.

Gemini Output (Chain-of-Thought):

Blockchain stores data in blocks that are verified by a network of computers. Each
block is connected to the previous one, making changes difficult. This technology
supports secure digital transactions and record keeping.

Claude Output (Chain-of-Thought):

Blockchain is a decentralized system where data is stored in connected blocks across
multiple computers. Each block is verified, ensuring accuracy and security. This
approach allows trusted data sharing without a central authority and is used in many
digital applications.

GitHub Copilot Output (Chain-of-Thought):

Blockchain is a system where data is stored in blocks and shared across a network. It
ensures data security and consistency.
Chain-of-Thought Analysis
Chain-of-thought prompting improved conceptual accuracy but slightly reduced speed.
Claude and ChatGPT benefited most from structured reasoning.

3.4 Role-Based Prompting

Single Prompt Used
The AI was asked to act as a computer science professor and summarize the
blockchain article clearly for undergraduate students using simple language.
Outputs

ChatGPT Output (Role-Based):

Blockchain is a digital system that records information across many computers instead
of one central server. Data is stored in blocks and securely linked together, making it
difficult to change past records. This ensures transparency and trust. Blockchain is
widely used in cryptocurrencies like Bitcoin and is also applied in areas such as
healthcare, finance, and supply chains.

Gemini Output (Role-Based):

Blockchain is a decentralized technology that keeps records across a network of
computers. Each block of data is verified and linked securely, improving trust and
transparency. It is best known for cryptocurrencies but has many other uses.

Claude Output (Role-Based):

Blockchain is a secure way of storing data across multiple computers. Information is
grouped into blocks and linked together, which prevents tampering and increases
transparency. This technology is commonly used in digital currencies and is expanding
into many other fields.

GitHub Copilot Output (Role-Based):

Blockchain is a distributed data storage system that links blocks securely. It is used to
maintain reliable digital records.
Role-Based Analysis
Role-based prompting produced the most student-friendly and coherent summaries,
especially with ChatGPT and Claude.

8. Detailed Evaluation of Prompting Techniques
9. 
Across AI Platforms
The evaluation of AI-generated summaries was carried out using five key parameters:
accuracy, coherence, simplicity, speed, and user experience. Each prompting
technique was analyzed across all AI platforms to determine its effectiveness for
educational text summarization.

4.1 Accuracy Evaluation

Accuracy refers to how correctly the AI captured the fundamental concepts of
blockchain technology, including decentralization, blocks, cryptographic linking, and
applications.

 Zero-Shot Prompting:

Accuracy was moderate across all platforms. While core ideas such as
decentralization and block structure were mentioned, some summaries lacked
important details like consensus mechanisms or immutability. GitHub Copilot
showed the lowest accuracy due to overly brief outputs.

 Few-Shot Prompting:

Accuracy improved noticeably, especially for ChatGPT and Claude. The
presence of an example helped guide the models toward including essential
blockchain concepts in a balanced manner.

 Chain-of-Thought Prompting:

This technique produced the highest conceptual accuracy. By encouraging stepby-step reasoning, models like Claude and ChatGPT generated summaries that
reflected a deeper understanding of how blockchain works.

 Role-Based Prompting:

Accuracy remained consistently high. By assuming the role of a professor,
models focused on explaining core ideas clearly without unnecessary technical
depth.
Best Performers: Claude and ChatGPT using chain-of-thought and role-based
prompting.

4.2 Coherence Evaluation

Coherence measures the logical flow, structure, and readability of the summary.

 Zero-Shot Prompting:

Outputs were generally readable but lacked smooth transitions between ideas.
Some summaries appeared as disconnected statements rather than a cohesive
explanation.

 Few-Shot Prompting:

Coherence improved significantly. The example summary provided a structural
template, leading to better-organized outputs across all platforms.

 Chain-of-Thought Prompting:

Summaries were logically structured, often following a clear progression from
definition to working to applications. However, in some cases, reasoning steps
slightly reduced conciseness.

 Role-Based Prompting:

This technique produced the most coherent summaries. Outputs followed a
natural teaching flow, making them ideal for undergraduate learners.
Best Performer: Role-based prompting on ChatGPT and Claude.

4.3 Simplicity Evaluation

Simplicity assesses how easy the summary is for undergraduate students to
understand.

 Zero-Shot Prompting:

Language was often neutral but occasionally too technical. Some models
assumed prior knowledge, reducing accessibility.

 Few-Shot Prompting:

The tone became simpler and more consistent, particularly in Claude’s outputs.
However, Gemini remained slightly formal.

 Chain-of-Thought Prompting:

Although accurate, some summaries included explanatory details that made
them slightly longer and less simple.

 Role-Based Prompting:

Simplicity was highest with this technique. The professor role encouraged plain
language, definitions, and student-friendly explanations.
Best Performer: Claude, followed closely by ChatGPT, using role-based prompting.

4.4 Speed Evaluation

Speed refers to how quickly a usable summary was produced.

 Zero-Shot Prompting:

This was the fastest technique across all platforms due to minimal instruction.

 Few-Shot Prompting:

Slightly slower due to processing the example but still efficient.

 Chain-of-Thought Prompting:

The slowest technique, as models were required to reason step by step before
producing the final output.

 Role-Based Prompting:

Balanced speed and quality. Slightly slower than zero-shot but significantly
better in output quality.
Fastest Technique: Zero-shot prompting
Best Speed–Quality Tradeoff: Role-based prompting

4.5 User Experience Evaluation

User experience considers ease of prompting, consistency of output, and overall
usefulness.

 ChatGPT:

Provided the best overall experience with consistent, high-quality outputs and
minimal need for prompt refinement.

 Claude:

Delivered excellent educational summaries with strong alignment to user intent,
making it ideal for academic use.

 Gemini:

Reliable but sometimes produced formal or generic responses that required
manual simplification.

 GitHub Copilot:

Less suitable for summarization tasks, as it is primarily optimized for coding
assistance.
Best User Experience: ChatGPT and Claude.
Each AI platform was evaluated using the same prompts for zero-shot, few-shot, chainof-thought, and role-based prompting techniques. The evaluation is based on accuracy,
coherence, simplicity, speed, and user experience, rated on a scale of 1 (Poor) to 5
(Excellent).

 Overall Final Conclusion
 
 Best AI Platform Overall: Claude

 Best Prompting Technique Overall: Role-Based Prompting

 Best Combination for Educational Summarization:

ChatGPT + Role-Based Prompting

Claude + Role-Based Prompting

This final analysis confirms that both platform choice and prompting strategy
significantly affect summarization quality. For undergraduate-level educational content,
role-based prompting consistently provides the most accurate, coherent, and simple
summaries.



RESULT:
The expanded evaluation clearly shows that role-based prompting is the most
effective technique for educational text summarization tasks. When combined with
ChatGPT or Claude, it delivers the best balance of accuracy, coherence, simplicity,
speed, and user experience. Few-shot prompting is a strong alternative, while chain-ofthought prompting is best suited for tasks requiring deeper reasoning rather than
concise summaries.
