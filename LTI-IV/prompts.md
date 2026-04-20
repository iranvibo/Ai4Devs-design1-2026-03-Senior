# Prompts Used for LTI System Design

This document outlines the sequence of prompts used to generate the architectural and product design artifacts for the LTI ATS project.

## 1. Product Discovery & Vision
**Prompt:**
> "Act as a Product Manager for LTI, a startup building the 'ATS of the future'. Define a brief description of the software, focusing on added value and competitive advantages. Research and incorporate keys for success in modern recruitment: HR efficiency, real-time collaboration, automation, and AI assistance. Summarize the main functions that would make this product stand out in a crowded market."

## 2. Business Model Visualization
**Prompt:**
> "Create a Lean Canvas for LTI. Include the following sections: Problem (manual screening, siloed comms), Solution (AI screening, real-time collab), Unique Value Proposition (AI that thinks like a recruiter), Unfair Advantage (proprietary bias detection), Customer Segments (fast-growing startups, mid-market HR), and Revenue Streams (Tiered SaaS). Present it using a Mermaid diagram."

## 3. Use Case Identification
**Prompt:**
> "Identify the 3 most critical use cases for LTI that demonstrate its core value (AI screening, collaboration, and automation). For each use case, provide a detailed description and a Mermaid Use Case diagram showing the interaction between actors (Recruiter, Hiring Manager, System, Candidate) and the system modules."

## 4. Data Modeling
**Prompt:**
> "Design a relational data model for LTI. Include entities such as Tenant, User, JobRequisition, Candidate, Application, Interview, Scorecard, and Offer. Define attributes with types and establish relationships (e.g., 1:N, N:M). Present the final model as a Mermaid ER Diagram."

## 5. Architectural Design (High-Level & C4)
**Prompt:**
> "Design a high-level system architecture for LTI. It must be cloud-native and follow a microservices pattern. Describe the components: API Gateway, Recruitment Service, Collaboration Service, and AI Engine. Create a Mermaid flowchart to visualize the system. 
> 
> Furthermore, provide a C4 Component diagram specifically for the 'Recruitment Service', showing its internal containers like API Controller, Domain Logic, and integrations with PostgreSQL, Elasticsearch, and the AI Service via message queues."

## 6. Document Compilation
**Prompt:**
> "Compile all the previous artifacts into a single, cohesive Markdown document named 'LTI-BD.md'. Use professional formatting, clear headings, and ensure all Mermaid diagrams are correctly embedded and syntactically valid."
