
 
![Image](https://github.com/user-attachments/assets/7816c508-6111-4133-bcaf-de3aaf955a00)
### **Botathon: Building On-Chain AI Agents on ICP** 

The **Botathon** is a developer-focused event where participants will build **AI agents on-chain** using the **Internet Computer Protocol (ICP)**. These AI agents will leverage the power of **decentralized computation**, ensuring transparency, autonomy, and on-chain execution.  

#### **What Are AI Agents?**  
AI agents are **autonomous programs** that can analyze data, make decisions, and execute tasks based on predefined logic. By deploying AI agents **on-chain**, we ensure that they operate without centralized control, enhancing security and trust.
AI agents are a growing paradigm in software that help perform complex tasks using simple natural language. The ecosystem is evolving rapidly. But rather than a future where AI agents run on proprietary platforms where companies lock you in, compromise your data, and monitor your digital life, we believe there's a better alternative. The Internet Computer is completely open source, powered by over 130 independent data centers around the world, and is uniquely positioned to host AI agents.  

**Key Features of On-Chain AI Agents:**  
- **Smart contract integration:** AI agents interact with **self-executing code** (smart contracts) to automate tasks.  
- **Decentralized execution:** Agents run on ICP, leveraging its **infinite scalability and cost efficiency**.  
- **Autonomous decision-making:** Agents can process data, learn from inputs, and execute actions independently.  

#### **Approach for Building AI Agents on ICP**  
1. **Defining the Use Case:** Choose an AI agent application (e.g., trading bot, content generator, or fraud detection).  
2. **Developing the Model:** Use AI frameworks like **Hugging Face**, **OpenAI APIs**, or train your own model.  
3. **Deploying on ICP:** Utilize **Motoko** or **Rust** to integrate the AI agent into a smart contract.  
4. **Enabling On-Chain Interaction:** AI agents can communicate with other canisters (smart contracts) and external data sources using **HTTPS outcalls** or **oracles**.  

#### **Example AI Agent Projects** 
# Example Demo:https://vgjrt-uyaaa-aaaal-qsiaq-cai.icp0.io/


Here are some AI agents that could be built during the Botathon: 
 **Command bots** which accept a command from an OpenChat user from within the OpenChat interface.
- **Integration bots** which accept a command from an external system using an API key.
- **Autonomous bots** which generate their own commands and interact with the OpenChat backend autonomously.
- **On-Chain Trading Bot** – An AI agent that analyzes price trends and executes trades autonomously.  
- **Decentralized AI Chatbot** – A chatbot that interacts with users on ICP-based platforms like OpenChat.  
- **Fraud Detection Agent** – AI that scans on-chain transactions for suspicious activity.  
- **NFT Recommendation Engine** – An AI-powered tool that suggests NFTs based on user behavior.  
- **Smart Contract Auditor** – AI that analyzes ICP smart contracts for vulnerabilities.  



#### **Refer to this Repositories below** 

## https://github.com/open-chat-labs/open-chat-bots.git
## https://github.com/ldclabs/anda.git~
## https://github.com/onicai/ic_llm_notebook.git
## https://github.com/Tevin-Isaac/ic-eliza-eth-wallet-agent.git
## https://github.com/asDNSk/eliza.git
## https://github.com/elna-ai/ELNA-DApp.git
## https://github.com/ICP-Hub-Kenya/DeAI.git




#### **How to Participate**  
1. **Fork the repositories above** and explore starter templates.  
2. **Join the community discussions** on OpenChat and Twitter.  
3. **Start coding your AI agent** using Motoko/Rust.  
4. **Read this Blog** https://medium.com/dfinity/deai-agent-economy-icp-as-new-home-for-autonomous-agents-edc2c04ceb32. 



 # Manifesto for Decentralized AI (DeAI)

In an era where Artificial Intelligence (AI) is increasingly central to our daily lives, this ubiquitous use of AI in applications ranging from mundane to critical tasks has powerful forces racing to establish control; the power over these transformative technologies, though, must not be confined to a few centralized entities. The Internet has brought tremendous decentralization of access to information and ease of communication, but also the centralization of power and corporate ownership of data. This trend will worsen if left unchecked. The principles of Decentralized AI (DeAI) can reverse this trend if users and application developers recognize its importance to their long-term welfare.

We envision a future where AI is democratized, broadly empowering, and adaptive to the diverse needs and values of all users, groups, and their contexts. This manifesto lays out the principles and reasons for decentralizing AI and advocates for a fair, transparent, and user-centric AI ecosystem.

## Principles of Decentralized AI

- **DeAI Is Safe AI**: DeAI prioritizes user safety by implementing robust security measures and rigorous testing protocols to minimize the risk of unintended consequences or malicious exploitation.

- **DeAI Is Self-Sovereign AI**: Users should have complete control over their AI. Your AI should work for you, reflect your values, and serve your needs without external interference.

- **DeAI Is Secure AI**: Privacy is a guarantee, not just a feature. DeAI ensures your data remains your own, safe from prying eyes and misuse.

- **DeAI Is Accessible AI**: DeAI makes advanced AI available to all. Extending the principles of the World Wide Web to AI, it is inclusive in the users it serves and in the supported interaction methods.

- **DeAI Is Participatory AI**: By allowing open contributions and attributing the created value back to the owner, DeAI enables everyone to participate in shaping the AI revolution and benefiting from it.

- **DeAI Is Responsible AI**: User empowerment and respecting stakeholders’ best interests are topmost priorities for DeAI. This includes best efforts to be resource-efficient and deliver sustainable solutions.

- **DeAI Is Verifiable AI**: Enabling thorough inspection and verification of DeAI systems promotes transparency of the underlying code and algorithms, as well as accountability to identify and rectify errors or biases in the AI's behavior.




## DeAI_Agent_Economy_table

| **Pillar**                          | **What AI Agents Need**                                                                                                                                 | **How ICP Provides It**                                                                                                                                                                                                                   |
|--------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Network Custody**                  | AI agents must handle private keys directly onchain for secure and independent transactions.                                                          | Secure Wallets using [Threshold ECDSA](https://internetcomputer.org/docs/current/developer-docs/smart-contracts/signatures/t-ecdsa/) and Schnorr signatures ensure AI agents can own and manage crypto assets autonomously. |
| **Secure Runtime Environments**      | AI agents need a tamper-proof execution environment where they can operate autonomously.                                                               | ICP’s decentralized network ensures secure, trustless execution of AI agents and logic. See [Canister-based](https://forum.dfinity.org/t/introducing-the-llm-canister-deploy-ai-agents-with-a-few-lines-of-code/41424) or [IC-TTE agents](https://github.com/ldclabs/ic-tee).                         |
| **Secure Access to Web & Blockchains** | Agents must retrieve external data, learn, and access liquidity pools on different chains.                                                              | [Chain Fusion](https://internetcomputer.org/chain-fusion) enables multi-chain integration, while [HTTP Outcalls](https://internetcomputer.org/https-outcalls/) grant agents secure web access.                                  |
| **Secure & Verifiable LLM Access**   | AI agents require onchain, verifiable access to Large Language Models (LLMs) to process information autonomously.                                     | [LLM Canister](https://forum.dfinity.org/t/introducing-the-llm-canister-deploy-ai-agents-with-a-few-lines-of-code/41424) with Verifiable Computation ensures cryptographic proof of LLM outputs before execution. AI Workers are stateless nodes set up for the sole purpose of processing LLM prompts.  |
| **Interfaces for AI Agents**         | AI agents need a way to interact with users and other agents seamlessly.                                                                                | [Direct Interfaces](https://internetcomputer.org/docs/current/developer-docs/web-apps/application-frontends/overview) allow agents to serve HTTP APIs directly, providing frictionless interaction.                                     |
| **Data Privacy & Encryption**        | AI agents must store and process private data securely.                                                                                                 | [VETKeys](https://internetcomputer.org/docs/current/references/vetkeys-overview/) (Verifiable Encrypted Threshold Keys) enable onchain encryption and private data handling.                                                        |
| **Decentralized Governance**         | AI agents should operate within governance frameworks for alignment with decentralized communities.                                                     | [DAOs on ICP](https://internetcomputer.org/docs/current/developer-docs/daos/nns/overview) allow AI agents to participate in governance and align with decentralized decision-making.               |
| **AI Monetization & Tokenized Incentives** | AI agents should autonomously earn, stake, and pay for services.                                                                                         | ICP supports [Digital Assets](https://internetcomputer.org/docs/current/developer-docs/defi/overview) and onchain transactions, enabling self-sustaining AI economies.                                            |


