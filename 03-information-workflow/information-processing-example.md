# Information Processing Workflow Example

## Raw Input (Unstructured Customer Feedback)
- "The app keeps freezing every time I try to check out. I tried 3 times and my card was charged twice but no confirmation! I need a refund."
- "Customer service was great and Sarah was very helpful, but the delivery was delayed by two days from the promised date."
- "The new update is terrible, the colors are too bright and I can't find the offers section anymore. Please change it back."

## Chosen Task
Extracting and Restructuring: Turning messy, unstructured customer reviews into a prioritized action-item table for the product and support teams to drive decisions[cite: 1].

## Prompt Used
"Act as a Customer Experience Analyst. Read the following raw customer feedback. Extract the core issue, determine the sentiment, assign a priority level, and define an action item with an assigned department. Output the result as a Markdown table."

## Final Structured Output (After Human Review)

| Customer Issue | Sentiment | Priority | Action Item | Assigned Department |
|---|---|---|---|---|
| App freezing at checkout / Double charge | Negative | High | Process refund immediately & investigate checkout API bug | Finance / Tech Team |
| Delivery delayed by two days | Mixed | Medium | Review logistics SLA & send apology discount to customer | Logistics / CX Team |
| Cannot find offers in new UI | Negative | Low | Add a UI tooltip guide to highlight the new offers section | UI/UX Design Team |

*Note: Missing specific customer IDs were intentionally marked as [Not Specified] or omitted to maintain privacy, and no details were invented by AI[cite: 1].*
