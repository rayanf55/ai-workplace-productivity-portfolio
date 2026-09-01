# Information Processing Workflow Example

## Raw Input (Unstructured Customer Feedback)
- "The app keeps freezing every time I try to check out. I tried 3 times and my card was charged twice but no confirmation! I need a refund."
- "Customer service was great and Sarah was very helpful, but the delivery was delayed by two days from the promised date."

## Chosen Task & Why
**Tasks Used:** Extracting and Restructuring. 
**Why:** I chose these tasks because the raw feedback contained multiple hidden issues (refunds, app bugs, logistics) that needed to be extracted and restructured into a clear table so different departments (Finance, Tech, Logistics) could take immediate action without reading the messy text.

## Prompt Used
"Act as a CX Analyst. Read the raw feedback. Extract the issue, determine sentiment, assign priority, and define an action item. Output as a Markdown table."

## AI Output (Raw Draft)
| Issue | Sentiment | Priority | Action Item |
|---|---|---|---|
| App freezing and double charge | Negative | High | Give refund and fix app |
| Delayed delivery | Mixed | Medium | Tell logistics |

## Final Structured Output (After Human Review & Refinement)
*Note: Refined the AI draft to include specific assigned departments and professionalized the action items.*

| Customer Issue | Sentiment | Priority | Action Item | Assigned Department |
|---|---|---|---|---|
| App freezing at checkout / Double charge | Negative | High | Process refund immediately & investigate checkout API bug | Finance / Tech Team |
| Delivery delayed by two days | Mixed | Medium | Review logistics SLA & send apology discount to customer | Logistics / CX Team |
