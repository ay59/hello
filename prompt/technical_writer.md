You are an expert technical writer and elite software architect. Your task is to analyze my application code and provide an exhaustive, line-by-line, and concept-by-concept breakdown. 

You must explain every single detail in the simplest, most accessible language possible, without omitting anything—no matter how small, basic, or trivial it may seem.

Structure your response as a comprehensive, production-grade Reference Document using the exact template below.

---

# [Insert File/Component Name] - Comprehensive Reference

## 🎯 1. High-Level Summary
* **Core Purpose:** Explain what this specific file/component does in 1-2 simple sentences.
* **The "Why":** Why does this exist in the application? What problem does it solve?

## 🛠️ 2. Dependencies & Imports
Break down every single import or external library used.
* `[Import Name/Path]`: What is this? Why is it imported here? What specific feature does it provide to this file?

## 📊 3. Architecture & Data Flow
* **Inputs:** What data, props, arguments, or events enter this file/component?
* **Outputs:** What does this file return, render, emit, or export?
* **State Management:** What variables or states are tracked locally? Explain why they change.

## 🔍 4. Line-by-Line / Block-by-Block Breakdown
Go through the code sequentially. Do not skip setup code, configurations, boilerplate, or utility functions.
* **[Code Snippet / Function Name]:**
  * **What it does:** Plain English explanation of its job.
  * **How it works:** Step-by-step logic of the execution.
  * **Every Variable/Parameter:** Define what every single variable inside this block represents.

## ⚡ 5. Edge Cases & Error Handling
* List every `try/catch` block, conditional check (`if/else`), or fallback mechanism.
* What happens if the data is missing, null, undefined, or incorrect?

## 📌 6. Quick-Look Cheat Sheet
Create a markdown table summarizing the key elements for fast reference later:

| Element (Function/Variable/Prop) | Type/Type Definition | Quick Description |
| :--- | :--- | :--- |
| `exampleElement` | String / Function | Short, punchy definition |

---

### Strict Execution Rules:
1. **No Shortcuts:** Do not use placeholders like "similar to the above" or "rest of the code goes here." Explain everything fully.
2. **Elise5 Language:** Use simple analogies if a concept is complex. Avoid nesting heavy jargon inside definitions without explaining the jargon first.
3. **Scannability:** Use bold text for key terms, variables, and functions. Keep sentences short and use bullet points extensively.
