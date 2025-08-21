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
## prompt 
step 1:
Summarize the following 500-word article on “The Basics of Blockchain Technology” in 120–150 words for undergraduate students. Keep it clear and beginner-friendly. 
Step 2 (Feedback):
Please revise the summary to make it even simpler and include at least two real-world examples of blockchain applications.
## Original Text 
```
The Basics of Blockchain Technology

Blockchain is a revolutionary digital technology designed to record, verify, and share information in a secure and transparent way. At its core, blockchain is a type of database, but it is very different from traditional databases managed by a central authority. Instead of storing information in a single location, blockchain distributes it across a network of computers, often called “nodes.” This decentralized design makes it extremely difficult for anyone to change or hack the information, ensuring trust and reliability.

A blockchain is built from a series of “blocks,” each containing a list of transactions or records. These blocks are connected in chronological order, forming a “chain.” Every time new data is added, it becomes part of a new block, which is then linked to the previous one. Because each block is mathematically tied to the one before it, altering past records is almost impossible without changing every block in the chain. This feature gives blockchain its powerful security and transparency.

One of the most important aspects of blockchain is the concept of consensus mechanisms. Before a new block is added, the network participants must agree that the information is valid. Different blockchains use different methods to reach this agreement. For example, Bitcoin uses a method called Proof of Work, where computers solve complex problems to verify transactions. Other blockchains use alternatives like Proof of Stake, which are more energy-efficient.

Blockchain became widely known through cryptocurrencies, with Bitcoin being the first and most famous example. Using blockchain, Bitcoin allows people to send and receive money directly without relying on banks or intermediaries. Transactions are fast, transparent, and verifiable by anyone on the network. However, blockchain technology has grown far beyond cryptocurrencies and is now transforming multiple industries.

In supply chain management, blockchain helps track goods at every stage, from raw materials to the final product in stores. This ensures authenticity, prevents fraud, and improves consumer trust. For instance, food companies can trace products back to farms, making it easier to identify sources during safety recalls.

In healthcare, blockchain allows secure storage of patient medical records. Only authorized professionals can access the information, protecting privacy while ensuring quick availability in emergencies. This reduces paperwork and improves coordination among hospitals and clinics.

Another important application is in voting systems. By recording votes on a blockchain, governments can make elections more transparent and harder to tamper with. Similarly, in finance, banks and businesses are exploring blockchain to process cross-border payments faster and with lower fees.

Overall, blockchain combines decentralization, security, and transparency to build trust in digital interactions. While it is still developing and faces challenges like energy use and regulation, its potential is enormous. For students, the key lesson is that blockchain is not just about Bitcoin—it is a powerful tool that could reshape how we share information and value in the digital age.

```
## Summarized text
```
Blockchain is a digital system that records and shares information securely without needing a central authority. Data is stored in “blocks” linked in a “chain,” making it nearly impossible to alter once added. Every transaction is verified by a network of computers through consensus, ensuring trust and transparency. While it became popular through Bitcoin, blockchain is now used in many fields. For example, supply chains use it to track products from farms to stores, ensuring authenticity, while healthcare uses it to securely store patient records for authorized access. By combining security, transparency, and efficiency, blockchain is reshaping how information and value are exchanged in today’s digital world.
```
## Result


