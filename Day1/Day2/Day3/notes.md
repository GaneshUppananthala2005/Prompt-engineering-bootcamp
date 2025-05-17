# 📘 Day 3 – Chain-of-Thought & System Prompts

---

## 🧠 What is Chain-of-Thought Prompting?

Chain-of-Thought (CoT) prompting is a technique where you ask the AI to **think step-by-step** instead of jumping to the answer.

This helps AI perform **reasoning-based** tasks more accurately.

---

### 🧪 Example

**Prompt (normal):**
t (chain-of-thought):**
Let's solve this step-by-step. First, break 23 into 20 and 3, and 47 into 40 and 7. Now add: 20 + 40 = 60, and 3 + 7 = 10. So the final answer is 70.

yaml
Copy
Edit

✅ Result: More accurate and logical answer

---

## 🧩 Why Use It?

- Helpful for **math problems**, **logic puzzles**, or **multi-step questions**
- Forces the model to “show its work”

---

## 🖥️ What Are System Prompts?

A **System Prompt** is a special prompt that sets the **behavior** or **role** of the AI before any user input.

It’s used in apps like **ChatGPT** or **custom AI bots**.

---

### 🧪 Example System Prompt:
You are a kind and knowledgeable science tutor. Answer all questions clearly and with patience.

sql
Copy
Edit

Then the user says:
What is gravity?

yaml
Copy
Edit

The AI now replies in a friendly, clear teaching style.

---

## 💡 Key Takeaways

- Chain-of-Thought helps AI break down complex tasks
- System Prompts set the tone, style, and behavior of the AI
- You can combine both for more powerful interactions

---

## 🧪 Practice Prompt

You are a history teacher. Explain World War I step-by-step to a 14-year-old student. Use simple language and short sentences.

markdown
Copy
Edit

✅ This uses:
- A system role (`history teacher`)
- A CoT-style request (`step-by-step`)
- Context and audience (`14-year-old`, `simple language`)
