# ADR NNNN: <Title>

- **Status:** Proposed | Accepted | Superseded by ADR NNNN
- **Date:** YYYY-MM-DD

## Context
I want to learn more about the Azure-based stack and AI architecture. The AI roles I am targeting build on the Microsoft ecosystem and Azure, so hands-on experience with these services is directly relevant. Currently my best expertise is with the solutions and understanding business use cases. Starting this project, I have good basic understanding of software development, but I want to deepen my understanding in building solutions that are scalable in an enterprise environment. This project aims to fill that knowledge gap. Moreover, this project aims to solve the gap in Microsoft ecosystem and Azure enviroment utilization.

## Decision
Build the project on Azure: Azure OpenAI for models, Azure AI Search for retrieval, Azure SQL and Blob storage for data, Container Apps for the backend and Entra ID for identity.

## Alternatives considered
| Option | Pros | Cons |
| --- | --- | --- |
| **Azure (chosen)** | Matches target roles; enterprise patterns (Entra ID, Key Vault, managed identity) | Higher cost, more configuration, slower start |
| Vercel + Supabase + Gemini | easiest and cheapest to start | does not utilize the MS environment |
|  AWS | Market leader | not fit-for-purpose due to focus on Microsoft ecosystem |

## Consequences
In this project, I need to be budget-cautious. To mitigate this risk, I have set up budget control and alerts for 50% 80% and 100%. The budget is 20 euros. Negative consequences come with more configuration and slower start compared to other alternatives. Positive consequences in learning Entra ID, Key Vault and managed identity.
