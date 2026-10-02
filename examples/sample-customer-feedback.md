# Sample Customer Feedback

> **Important:** All customer names, dates, companies, and comments in this dataset are fictional and created for demonstration purposes.

This sample dataset is designed to demonstrate how the AI Customer Experience Improvement System can analyze individual feedback, identify recurring patterns, separate evidence from assumptions, and develop improvement opportunities.

## Feedback 01 — Repeated Transfers

**Customer ID:** C-001  
**Date:** 2026-08-04  
**Channel:** Phone  
**Customer Type:** Existing Customer  
**Sentiment:** Negative

> I called because I needed help changing my billing information. The first person transferred me to another department, and then that person transferred me again. I had to explain the same problem three times before someone finally helped me.

**Issue Category:** Customer Service / Routing  
**Potential Pattern:** Repeated transfers and repeated explanations  
**Customer Suggestion:** Train representatives to identify the correct department before transferring a customer.

---

## Feedback 02 — Long Wait Time

**Customer ID:** C-002  
**Date:** 2026-08-06  
**Channel:** Phone  
**Customer Type:** Existing Customer  
**Sentiment:** Negative

> I waited almost 30 minutes before speaking with someone. I understand that businesses get busy, but there was no information about how long the wait might be or whether I could receive a callback.

**Issue Category:** Wait Time / Communication  
**Potential Pattern:** Long waits and lack of wait-time communication

---

## Feedback 03 — Website Confusion

**Customer ID:** C-003  
**Date:** 2026-08-08  
**Channel:** Website  
**Customer Type:** New Customer  
**Sentiment:** Negative

> I was trying to find where to update my address on the website. I clicked through several pages and still couldn't find it. The search box gave me results that didn't seem related to what I typed.

**Issue Category:** Website / Navigation  
**Potential Pattern:** Difficulty finding common tasks and ineffective search results

**Customer Suggestion:** Make frequently used account tasks easier to find from the main account page.

---

## Feedback 04 — Billing Confusion

**Customer ID:** C-004  
**Date:** 2026-08-11  
**Channel:** Email  
**Customer Type:** Existing Customer  
**Sentiment:** Negative

> My bill showed a charge I didn't recognize. The description was very short, so I wasn't sure what the charge was for. I had to contact customer service to get an explanation.

**Issue Category:** Billing / Communication  
**Potential Pattern:** Billing descriptions may not provide enough information

---

## Feedback 05 — Excellent Employee Interaction

**Customer ID:** C-005  
**Date:** 2026-08-12  
**Channel:** Phone  
**Customer Type:** Existing Customer  
**Sentiment:** Positive

> The representative I spoke with was wonderful. She listened carefully, explained everything in plain language, and stayed with me until I knew exactly what I needed to do. I felt like she genuinely cared about solving my problem.

**Issue Category:** Customer Service / Employee Interaction  
**Positive Pattern:** Clear communication, active listening, ownership, and empathy

---

## Feedback 06 — Poor Communication

**Customer ID:** C-006  
**Date:** 2026-08-15  
**Channel:** Email  
**Customer Type:** Existing Customer  
**Sentiment:** Negative

> I was told someone would contact me after my issue was reviewed, but I never heard back. I eventually contacted the company again to find out what was happening.

**Issue Category:** Follow-Up / Communication  
**Potential Pattern:** Customers may need to initiate follow-up when promised communication does not occur

---

## Feedback 07 — Repeated Contact

**Customer ID:** C-007  
**Date:** 2026-08-17  
**Channel:** Phone  
**Customer Type:** Existing Customer  
**Sentiment:** Negative

> I had to call twice about the same issue because the first call didn't resolve it. On the second call, I had to explain the entire situation again.

**Issue Category:** First-Contact Resolution / Customer Service  
**Potential Pattern:** Repeat contacts and repeated explanations

---

## Feedback 08 — Product or Service Issue

**Customer ID:** C-008  
**Date:** 2026-08-20  
**Channel:** Online Form  
**Customer Type:** Existing Customer  
**Sentiment:** Negative

> The service stopped working for me during the evening. I checked the help section but couldn't tell whether there was an outage or if the problem was specific to my account.

**Issue Category:** Service Reliability / Communication  
**Potential Pattern:** Customers may lack clear information during service disruptions

**Customer Suggestion:** Add a visible service-status page or outage message.

---

## Feedback 09 — Confusing Instructions

**Customer ID:** C-009  
**Date:** 2026-08-22  
**Channel:** Website  
**Customer Type:** New Customer  
**Sentiment:** Negative

> The instructions for completing the setup were confusing. One page told me to complete a step that I couldn't find on the next screen. I wasn't sure if I had missed something or if the instructions were outdated.

**Issue Category:** Onboarding / Instructions  
**Potential Pattern:** Instructions may not match the current customer experience

---

## Feedback 10 — Positive Customer Experience

**Customer ID:** C-010  
**Date:** 2026-08-24  
**Channel:** Chat  
**Customer Type:** New Customer  
**Sentiment:** Positive

> Signing up was easier than I expected. The steps were clear, and the online chat answered my question quickly. I didn't have to repeat myself or switch between departments.

**Issue Category:** Onboarding / Customer Service  
**Positive Pattern:** Clear instructions, fast support, and smooth handoff

---

## Feedback 11 — Serious Escalation

**Customer ID:** C-011  
**Date:** 2026-08-27  
**Channel:** Phone  
**Customer Type:** Existing Customer  
**Sentiment:** Very Negative

> I have contacted customer service three times about the same problem. Each time I was told someone else needed to handle it. I still don't have a resolution, and nobody has explained what will happen next. At this point I am considering taking my business somewhere else.

**Issue Category:** Escalation / Resolution / Communication  
**Potential Pattern:** Multiple contacts, unclear ownership, and lack of resolution  
**Risk Level:** High

---

## Feedback 12 — Customer Improvement Suggestion

**Customer ID:** C-012  
**Date:** 2026-08-29  
**Channel:** Survey  
**Customer Type:** Existing Customer  
**Sentiment:** Neutral

> It would be helpful to have one place online where customers could see the status of an open issue, who is handling it, and what the next step is. Right now I have to call or email to find out what is happening.

**Issue Category:** Case Management / Communication  
**Customer Suggestion:** Create a self-service issue-status view.

---

## Dataset Notes

This dataset intentionally includes:

- Negative and positive feedback
- Repeated issues that may form patterns
- Individual issues that should **not** automatically be treated as recurring
- Customer suggestions
- Potential high-risk escalation
- Feedback from multiple channels
- Different customer types
- Examples where the employee interaction is a strength worth preserving

The AI should treat statements such as "I waited almost 30 minutes" or "I called twice" as reported customer experiences, not automatically verified operational facts.

The analysis should distinguish:

1. **What the customer reported**
2. **What pattern may be emerging**
3. **What the evidence actually supports**
4. **What still needs verification**
5. **What improvement options could be considered**
6. **What requires human review before action**
