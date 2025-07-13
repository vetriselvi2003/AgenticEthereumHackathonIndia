Agentic Ethereum Hackathon India

Project Title - GramFinance (Team: Data Miners)

Welcome to our submission for the Agentic Ethereum Hackathon by Reskilll & Geodework! This repository includes our project code, documentation, and related assets.

---

-->Problem Statement

We addressed the challenge: “Financial Inclusion for the Unbanked in Rural India”
Over 200 million people in India remain outside the formal financial system. Lack of credit history, no access to smartphones or banking apps, and low financial literacy are core obstacles. Despite this, most use UPI and WhatsApp — opening a pathway for inclusive innovation.

-->Our Solution

Project Name:GramFinance
Tagline:DeFi for Bharat, Powered by Agents

GramFinance is a decentralized finance (DeFi) platform enabling local financial agents to bring AI-powered micro-banking to rural populations using simple devices and trusted interfaces like WhatsApp and voice.

Our AI agent assists in:

* Estimating credit scores from UPI and bill payment patterns
* Disbursing micro-loans via Ethereum smart contracts
* Enabling voice-based interactions in local languages
* Offering insurance & savings recommendations
* Recording consent and building credit on-chain

We aim to empower rural communities with real-world financial tools using blockchain + AI + human trust.

-->Tech Stack

Frontend: React.js, Tailwind CSS
Backend: Node.js, Express.js
AI: GramGPT (voice NLP agent), LangChain
Blockchain: Solidity, Hardhat, Polygon Mumbai
DB/Storage: Firebase, IPFS
Hosting: Vercel, Firebase Hosting


--->Repository Structure

bash
.
├── frontend/           # Frontend code (React.js
├── backend/            # Backend services (Node.js, APIs)
├── contracts/          # Smart contracts (Solidity)
├── assets/             # PPT, video links, images
├── docs/               # Architecture diagrams, user flows
├── README.md           # This file
├── .env.example        # Sample environment config
├── package.json        # Project dependencies
```

-->Features

* Agent onboarding via Polygon ID
* Voice-based loan requests in local languages
* WhatsApp + UPI integration
* AI-driven credit score generation
* Low-interest micro-loans with on-chain disbursal
* Blockchain-secured transactions and credit history
* Commission & rewards system for field agents

-->Example Story: Meena’s Journey

* Meena, a dairy farmer from Tamil Nadu, gets a ₹5,000 loan by speaking into the GramFinance app in Tamil.
* Verified by Aadhaar + Polygon ID.
* Loan disbursed via smart contract.
* Pays ₹834/month and builds her credit history on-chain.
* Buys livestock insurance for ₹50/year.
* Refers 3 more women and her local agent, Ravi, earns a reward.

-->Challenges & Learnings

* Designing intuitive UI for low-literacy, non-tech users
* Building trust through local agents & verified identities
* Optimizing for low gas costs with Layer 2 scaling (Polygon)
* Offline sync capabilities for rural connectivity issues

-->Future Scope

* Integration with eKYC and national identity systems
* Native token economy for agent and user incentives
* Expansion to insurance, savings, and investment DeFi products
* Full voice-to-smart-contract flows in multiple languages

-->Conclusion

GramFinance shows how decentralized finance, AI, and community agents can work together to build financial bridges for those left out of the system. With voice, trust, and on-chain transparency, we’re making DeFi usable for Bharat.
