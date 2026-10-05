# SWYNEX AI Problem Design – Task 1

## AI-Based Customer Support Ticket Classification

### 1. Problem Statement

Customer support teams receive many messages every day related to payments, deliveries, refunds, returns, and product issues. Manually reading and categorizing every message can take a lot of time.

The goal of this project is to design an AI-based system that automatically classifies customer support messages into the correct category.

### 2. AI Use Case

This project focuses on a Text Classification problem.

The AI system will take a customer support message as input and classify it into one of the following categories:

- Payment Issue
- Delivery Issue
- Product Issue
- Refund / Return
- Other

Example:

Input:
"My order has not arrived yet."

Predicted Category:
"Delivery Issue"

### 3. Target User

The main users of this system are:

- Customer support teams
- E-commerce businesses
- Companies handling large numbers of customer queries

The system can help these users organize support tickets and route customer problems to the appropriate team faster.

### 4. Data Source

A small labeled dataset of customer support messages will be used.

The dataset will contain two main fields:

- Customer Message
- Category

Example:

| Customer Message | Category |
|---|---|
| My payment was deducted twice | Payment Issue |
| My order has not arrived yet | Delivery Issue |
| The product I received is damaged | Product Issue |
| I want to return my order | Refund / Return |

For the initial prototype, a small sample dataset can be created manually using realistic customer support queries.

### 5. Constraints

The initial system has some limitations:

- The dataset will be relatively small.
- Customer messages may contain spelling or grammar mistakes.
- Some customer messages may be unclear or ambiguous.
- The first version will support only five predefined categories.
- Performance may decrease when the system receives messages very different from the training data.

### 6. Evaluation Approach

The dataset will be divided into training and testing data.

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics will help determine how correctly the AI system classifies different types of customer queries.

### 7. Success Criteria

The initial success target is to achieve at least 80% classification accuracy on the test dataset.

The model should also show reasonable performance across all five categories rather than performing well on only one category.

A successful system should correctly classify most common customer support messages and reduce the amount of manual ticket sorting required.

### 8. Expected Outcome

The expected outcome is a simple AI solution that can automatically identify the type of customer issue from a text message.

This can help businesses:

- Reduce manual work
- Route support tickets faster
- Improve response time
- Organize customer queries efficiently

---

## Internship

**Organization:** SWYNEX Technologies  
**Task:** Task 1 – AI Problem Design  
**Domain:** Artificial Intelligence / Machine Learning
