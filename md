# Copilot Studio Cost Analysis for OrgInsight Agent

This document provides a transparent breakdown of the credit consumption model for the OrgInsight Agent.

## 🔢 Copilot Credit Consumption

| Operation                   | Credits |
|----------------------------|---------|
| Graph grounding (SharePoint/Graph) | 10 |
| Generative LLM answer      | 2       |
| **Total per question**     | **12**  |

---

## 📈 Monthly Usage Scenario

Assume employees ask questions daily through Teams or internal portals.

### Case: 50 questions per weekday

- 50 × 5 = 250 per week  
- 250 × 4 = ~1,000 per month  
- 1,000 × 12 credits = **12,000 credits/month**

---

## 💲 Cost Interpretation

Message Pack Cost:  
- **25,000 messages = $200/month**

OrgInsight Agent at this usage consumes **48%** of a message pack.

If more departments adopt the agent, total cost grows linearly.

---

## 📉 Optimization Techniques

- Reduce unnecessary grounding calls  
- Use cached summaries for repeat questions  
- Keep response length tight  
- Limit retrieval to top-k chunks  
- Chunk documents efficiently  
- Reuse embeddings, avoid re-indexing  
- Monitor credit usage with logs  

These strategies can reduce per-call credit consumption significantly.

---

## Conclusion

AI agents introduce a new dimension of operational cost.  
Understanding credits, grounding, and retrieval behavior is essential for budgeting, DevOps planning, and scaling safely.
