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
8. The customer support and Raise issue button also creates the service and case erquest in the org using a form.

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

<img width="1901" height="911" alt="image" src="https://github.com/user-attachments/assets/edf67928-6c9a-490a-a7f6-1a04c5926deb" />
<img width="1896" height="917" alt="image" src="https://github.com/user-attachments/assets/de078c5f-005c-4d90-a4bb-23b4b4a962be" />
 Voice-based interaction
- Sentiment analysis for escalation
