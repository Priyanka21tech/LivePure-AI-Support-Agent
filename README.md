An AI-powered customer support agent deployed on a Salesforce Experience (Aura-enabled) site, designed to handle customer queries, automate service requests, and provide intelligent escalation.

## 🧠 Key Features
- Handles product queries and FAQs
- Creates and tracks service requests
- Performs warranty registration
- Fetches case details
- Supports web search capabilities
- Escalates to human agent when needed
- OTP-based customer verification

## ⚙️ Tech Stack
- Salesforce Agentforce
- Aura Components (Experience Cloud)
- Salesforce Flows
- Apex
- Prompt Engineering

## 🔄 Workflow
1. User interacts with AI agent on website
2. Agent resolves queries using knowledge base
3. If unresolved → suggests service request
4. Creates a service-request in the org after analysing the conversation with the user.
5. Performs OTP verification
6. Creates case with full conversation as context
7. Escalates to human agent if required

## 🏗 Architecture Highlights
- Multi-topic Agent design
- Knowledge + action-based responses
- Secure OTP verification flow
- Context-aware case creation

## 📽 Demo
Screenshots of the agent and page attached

## 💡 Business Impact
- Reduces support workload
- Improves customer experience
- Automates end-to-end support lifecycle

 Multilingual support
 
- Voice-based interaction
- Sentiment analysis for escalation
