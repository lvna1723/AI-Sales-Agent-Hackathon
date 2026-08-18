# AI Sales Agent — Intelligent Sales Automation

AI-powered sales agent developed during a Salesforce hackathon in collaboration with Santander and Iberotech.

The project addresses a real-world business problem by using an AI agent to automate repetitive sales operations and customer interactions through WhatsApp, reducing the need for human intervention while allowing escalation when necessary.

## 🚀 Overview

The solution allows customers to interact with an AI sales agent through WhatsApp using natural language.

The agent can understand customer requests, retrieve product information, generate quotations, create sales orders, provide order status updates, generate invoices, and answer questions about company policies and products.

The project was designed to go beyond a traditional chatbot by allowing the AI agent to perform business actions and interact with different processes involved in the sales cycle.

## 💡 Business Problem

The sales process involved several repetitive activities that could require human intervention, including:

* Searching for products
* Providing product information
* Preparing quotations
* Registering sales orders
* Notifying customers when their orders are ready
* Generating invoices
* Answering frequently asked questions
* Answering questions about company policies

The proposed solution uses an AI agent to automate these activities and provide customers with a more autonomous sales experience.

## 🧠 Solution

The AI agent acts as an intelligent interface between customers and the company's sales processes.

```text
Customer
    │
    ▼
 WhatsApp
    │
    ▼
 AI Sales Agent
    │
    ├── Product Search
    ├── Product Information
    ├── Company Policies
    ├── Quote Generation
    ├── Order Creation
    ├── Order Status
    └── Invoice Generation
    │
    ▼
Business Processes
    │
    └── Human Escalation
```

## ⚙️ Main Capabilities

### Product Search

Customers can describe the product they need using natural language, and the agent can identify and retrieve the relevant product information.

### Quotations

The agent can assist with the quotation process and generate a PDF quotation that can be emailed to the customer.

### Order Management

The agent can register sales orders and provide information about their status.

### Notifications

Customers can receive notifications related to their orders.

### Invoicing

The workflow allows invoices to be generated and emailed to the customer.

### Business Knowledge

The agent can answer questions about company policies and technical information related to products.

### Human Escalation

When a request requires human intervention, the workflow can escalate the interaction instead of attempting to complete the process autonomously.

## 🛠️ Technologies

* Salesforce Agentforce
* Salesforce Flow / Apex 

## 👩‍💻 My Contribution

The project was developed by a two-person team.

My teammate contributed primarily with the business requirements and domain knowledge, while I was responsible for the technical development of the AI agent.

My responsibilities included:

* Designing the AI agent solution
* Defining agent instructions
* Defining and configuring agent actions
* Designing and program agent flows
* Testing agent behavior
* Testing different business scenarios
* Identifying and correcting issues during testing
* Iterating on the agent based on test results

## 🏗️ Architecture

The following diagram represents the main components and interactions of the solution.

![System Architecture](architecture/system-architecture.png)

## 🔄 Example Workflow

A typical interaction follows a workflow similar to:

```text
Customer Request
       │
       ▼
Intent Understanding
       │
       ▼
Required Information
       │
       ▼
Agent Action
       │
       ├── Product Search
       ├── Quotation
       ├── Order
       ├── Order Status
       └── Invoice
       │
       ▼
Customer Response
```

## 🎥 Demonstration

A short demonstration of the solution is available below:

**[Watch the project demonstration](INSERT-LINK-HERE)**

## 📸 Screenshots

### Customer Interaction

![WhatsApp Interaction](images/01-whatsapp-interaction.png)

### Product Search

![Product Search](images/02-product-search.png)

### Quotation

![Quotation](images/03-quotation.png)

### Generated PDF

![Generated PDF](images/04-generated-pdf.png)

### Order Creation

![Order Creation](images/05-order-creation.png)

### Order Status

![Order Status](images/06-order-status.png)

### Invoice

![Invoice](images/07-invoice.png)

## 📄 Technical Case Study

For a more detailed explanation of the project, architecture, implementation decisions and workflows:

**[View Technical Case Study](docs/technical-case-study.pdf)**

## 📈 Results

The prototype demonstrated how an AI agent can automate multiple repetitive activities within a sales process while maintaining the possibility of human intervention when required.

The project focused on combining conversational AI with business actions, rather than limiting the solution to a question-and-answer chatbot.

## 📚 What I Learned

Through this project I gained practical experience in:

* Designing AI agents
* Creating instructions for agent behavior
* Defining agent actions
* Connecting AI agents with business processes
* Designing autonomous workflows
* Testing AI agent behavior
* Identifying limitations and edge cases
* Applying AI to a real-world business problem

## 🔒 Disclaimer

This repository is a portfolio representation of the project.

Confidential information, credentials, private configurations, customer information and proprietary business data have been removed or anonymized.
