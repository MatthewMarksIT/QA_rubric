# Data Annotation QA Framework
---
## Purpose

This project demonstrates a practical QA rubric for evaluating data annotation quality in human-in-the-loop AI workflows.  
It is designed to reflect how real data operations teams assess quality, deliver feedback, and maintain consistent standards at scale.

---
## How This Rubric Is Used

- Annotators submit completed tasks  
- QA reviews samples against defined criteria  
- Issues are categorized as Significant or Minor  
- Feedback is provided and tasks are corrected if needed  
- Repeated Significant Issues trigger retraining or escalation


This rubric defines how annotation errors are categorized and counted during QA review.  
It is designed to promote consistent evaluation, clear feedback, and high-quality outputs across human data workflows.


<img width="877" height="509" alt="image" src="https://github.com/user-attachments/assets/92d72a1b-7884-4f9d-99eb-b7a602ca7fd2" />


# Error Counting Guidelines

Each error should be counted based on the **type of issue**, not frequency.  
For example, multiple spelling mistakes count as **[1] Minor Issue – Spelling/Grammar**.

---

## Significant Issues
Errors that **materially impact task quality or usability** and represent a fundamental deviation from requirements.

**Examples:**
- Factual inaccuracies / hallucinations  
- Significant formatting errors  
- No explanation provided in the Explanation Box  
- Unsafe or harmful content  
- Incorrect UI selections  
- Significantly over the word limit  

---

## Minor Issues
Errors that are **cosmetic or easily correctable** by QA or the annotator after send-back.

**Examples:**
- Spelling or grammar mistakes  
- Minor formatting errors  
- Incorrect explanation format  
- Incomplete or low-quality explanations  
- Slightly over the word limit  

