# 🚀 Prompt Engineering Cheat Sheet for ChatGPT

## 📌 **Fundamental Principles**

### 1️⃣ Be Clear & Specific
- **❌ Bad Prompt:** `Tell me about history.`
- **✅ Good Prompt:** `Summarize the key events of World War II in under 200 words.`

### 2️⃣ Use Step-by-Step (Chain-of-Thought) Reasoning
- **✅ Example:**  
  ```
  Solve this math problem step by step: 37 × 25.
  ```

### 3️⃣ Define Role & Perspective
- **✅ Example:**  
  ```
  You are a cybersecurity expert. Explain encryption in simple terms.
  ```

### 4️⃣ Set Constraints (Word Limits, Format, Style)
- **✅ Example:**  
  ```
  Explain quantum physics in 100 words using a casual tone.
  ```

### 5️⃣ Provide Examples (Few-Shot Prompting)
- **✅ Example:**  
  ```
  Convert these sentences into a polite tone:
  1. "Give me the report now!" → "Could you please provide the report when you have a moment?"
  2. "I need help!" → (Your turn!)
  ```

## 📌 **Advanced Techniques**

### 6️⃣ Use Multi-Turn Prompting (Iterative Refinement)
- **Step 1:** `Write a blog post on AI ethics.`
- **Step 2:** `Make it engaging with a storytelling approach.`
- **Step 3:** `Summarize it in a tweet.`

### 7️⃣ Prompt Chaining (Breaking Down Complex Tasks)
- **✅ Example:**  
  ```
  1. List 5 popular business ideas.
  2. Expand on idea #3 with a business model.
  3. Create a 5-step launch plan for this business.
  ```

### 8️⃣ Generate Structured Data (JSON, Tables, Lists)
- **✅ Example (JSON Output):**
  ```json
  List 3 famous inventors in JSON format.
  ```
  **Output:**
  ```json
  {
    "inventors": [
      {"name": "Nikola Tesla", "invention": "AC Electricity"},
      {"name": "Marie Curie", "invention": "Radioactivity"},
      {"name": "Thomas Edison", "invention": "Light bulb"}
    ]
  }
  ```

### 9️⃣ Use Zero-Shot vs Few-Shot Prompting
- **Zero-Shot:** `Translate this sentence into Spanish: "Hello, how are you?"`
- **Few-Shot:**
  ```
  Translate these sentences into Spanish:
  1. "Good morning" → "Buenos días"
  2. "See you later" → "Nos vemos"
  Now translate: "Take care!"
  ```

## 📌 **Industry-Specific Applications**

### 🔹 **Coding & Development**
- Debugging: `Find the bug in this Python code: [paste code]`
- Code Explanation: `Explain this JavaScript function step by step.`
- Code Generation: `Write a Python function to sort an array.`

### 🔹 **Marketing & Copywriting**
- Ad Copy: `Write an Instagram ad for a fitness app.`
- Email Writing: `Write a cold email for a sales pitch.`

### 🔹 **Business & Productivity**
- Meeting Summaries: `Summarize this meeting transcript in bullet points.`
- Startup Ideas: `List 10 AI-based business ideas.`

## 🎯 **Final Pro Tips**
✅ Use **explicit instructions** (e.g., "Write in bullet points")  
✅ Experiment & iterate—**refine prompts** for better responses  
✅ If results are off, **rephrase or add examples**  
✅ Keep prompts **concise yet detailed**  

🚀 **Master these techniques, and you'll unlock the full potential of AI!**
