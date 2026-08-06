# General Prompt Optimization Engineer Prompt

## I. Project Overview

### 1.1 Project Positioning
This project provides a set of general prompts (Prompt), aiming to guide AI models to actively analyze user tasks, capture needs accurately through structured questioning, and thus generate high-quality, highly matched final instructions.

### 1.2 Core Value
- **Solving Pain Points**: Addressing output deviations caused by vague requirement descriptions in traditional human-machine interaction
- **Core Philosophy**: Enabling AI to "understand first, then execute"
- **Final Effect**: Significantly improving task completion efficiency and accuracy

### 1.3 Target Users
Whether you are writing copy, performing data analysis, coding, or executing other tasks requiring precise AI collaboration, simply copy and send this prompt to the AI chatbox. The AI will automatically enter "requirement analysis mode."

### 1.4 Usage Threshold
- No need to install any software
- No programming background required
- Only three steps are needed: "copy, paste, and send"
- Applicable to most mainstream AI chat models

---

## II. Core Features

### 2.1 Task Analysis in Advance
After sending this prompt, the AI will pause direct answering and instead analyze your task objectives, target audience, output format, style requirements, and other key elements to ensure the subsequent content is highly aligned with your actual needs.

### 2.2 Proactive Inquiry for Details
The AI will simulate a project manager's questioning logic and ask you for details one by one, such as:
- "Who is your target audience?"
- "What is the expected output length?"
- "Are there any key information that must be included?"

This ensures no important information is missed and prevents output deviations caused by vague requirements.

### 2.3 Automatic Generation of Optimized Prompt
After you answer all the questions, the AI will synthesize your responses and automatically generate a complete, clear, and logically rigorous final prompt for you to copy and use directly.

### 2.4 Zero Threshold Usage
No need to install any software, no programming background required, only three steps are needed: "copy, paste, and send," applicable to most mainstream AI chat models.

---

## III. Technical Principles

### 3.1 Technical Architecture
This project is based on the principles of prompt engineering (Prompt Engineering), guiding AI models into a requirement analysis process through pre-set instruction templates.

### 3.2 Core Mechanism
1. **Instruction Trigger**: Activate the AI's optimization mode through a specific prefix (e.g., `optimize prompt:`)
2. **Structured Questioning**: Pre-set a series of questioning templates targeting key task elements, covering objectives, audience, format, constraints, and other dimensions
3. **Information Integration**: The AI model generates a structured optimized prompt based on user responses

### 3.3 Operating Environment
This project does not rely on specific software or programming environments. It can run on any AI chat model that supports natural language interaction.

---

## IV. Applicable Scenarios

### 4.1 Copywriting
Tasks requiring AI to generate content in specific styles and tones, such as writing public account articles, Xiaohongshu notes, and short video scripts.

### 4.2 Data Analysis and Research
Tasks requiring AI to output results in specified formats, such as data cleaning, statistical analysis, and market research.

### 4.3 Programming Development
Tasks requiring AI to precisely understand technical requirements, such as generating code, debugging errors, and optimizing algorithms.

### 4.4 Other Precise Execution Scenarios
Any scenario where AI needs to complete specific tasks based on clear instructions, and users wish to reduce communication costs and improve output quality.

---

## V. Quick Start Guide

### 5.1 Prerequisites
- An AI chat model that supports natural language interaction (e.g., GPT series, DeepSeek, Tongyi Qianwen, Kimi, Claude, etc.)
- The prompt text of this project (obtained from the `system_prompt_english.md` file)

### 5.2 Operation Steps

**Step 1: Copy the Prompt Text**
Copy the complete prompt content from the project file `system_prompt_english.md`.

**Step 2: Open the AI Chat Tool**
Launch your commonly used AI chat model.

**Step 3: Turn Off Deep Thinking Mode**
Before sending the prompt, ensure that the AI model's deep thinking mode (e.g., "Deep Reasoning," "Advanced Analysis," etc.) is turned off to prevent the AI from over-analyzing the instruction structure and ignoring the execution requirements, which may lead to non-compliance with the prompt instructions.
> **Prompt**: If you need to use the deep thinking mode, you can restart it after the initial AI prompt is completed.

**Step 4: Paste and Send**
Paste the copied prompt content into the input box and send it.

**Step 5: Input the Prompt to be Optimized**
After the AI completes the initialization thinking, input the original prompt you need to optimize into the input box, and add the prefix `optimize prompt:` before it, then send it.
- Example: `optimize prompt: Please help me write an article about artificial intelligence.`

**Step 6: Answer the AI's Questions**
The AI will immediately ask you a series of questions about the task details. Please answer them truthfully according to your actual needs.

**Step 7: Obtain the Optimized Result**
After answering all the questions, the AI will generate an optimized prompt. You can directly copy it to complete your task.

---

## VI. Usage Tips and Optimization Suggestions

### 6.1 Enhancing Stability

#### Method 1: Add a Trigger Prefix
To more stably guide the AI into "optimization mode," it is recommended to add the prefix `optimize prompt:` at the beginning of the pasted prompt text.
- Example: `optimize prompt: [Enter the prompt to be optimized here]...`
- **Working Principle**: Some AI models are more sensitive to specific instruction words (e.g., "optimize"). This operation can reduce the risk of the AI skipping the Q&A session directly, ensuring it enters the expected requirement analysis process.

#### Method 2: Turn Off Deep Thinking Mode
When initializing the AI with this prompt, it is recommended to turn off the AI model's deep thinking mode (e.g., "Deep Reasoning," "Advanced Analysis," etc.). Deep thinking mode may cause the AI to over-analyze the structure and intent of the prompt rather than directly executing the instructions, thus reducing the AI's compliance with the prompt instructions. Turning off this mode ensures the AI strictly follows the pre-set questioning process, improving the task success rate.
> **Prompt**: If you need to use the deep thinking mode, you can restart it after the initial AI prompt is completed.

### 6.2 Advanced Usage

#### Customize Questioning Templates
If you have fixed requirements for specific scenarios, you can modify the questioning templates in the prompt text to better align with your business logic.

#### Multi-Round Optimization
For complex tasks, you can apply this process again to the optimized prompt for multiple rounds of iterative optimization.

---

## VII. Usage Examples

### 7.1 Scenario: Optimizing a Copywriting Prompt

**Original Prompt:**
```text
optimize prompt: Please help me write an article about artificial intelligence.
```

**AI Questioning Example:**
- Who is your target audience? (e.g., technical professionals, general public, students)
- What is the expected output length? (e.g., 500 words, 1000 words)
- What is the style requirement for the article? (e.g., popular science, professional, humorous)
- Are there any key information that must be included? (e.g., latest technology trends, application cases)

**User Answers:**
- Target audience: General public
- Output length: 800 words
- Style requirement: Popular science, easy to understand
- Key information: Application cases of artificial intelligence in the medical field

**Optimized Prompt:**
```text
Please write a popular science article for the general public, with the theme of artificial intelligence applications in the medical field. The article should be approximately 800 words long and use simple, easy-to-understand language, avoiding professional jargon. It should include at least two specific application cases (e.g., AI-assisted diagnosis, intelligent drug development) and briefly explain their impact on future healthcare. The article structure is recommended as follows: introduction (AI overview), main body (application cases), conclusion (prospects).
```

---

## VIII. Frequently Asked Questions

### Q1: Is this prompt applicable to all AI models?
**A**: It is applicable to most mainstream AI chat models (e.g., GPT series, DeepSeek, Tongyi Qianwen, Kimi, Claude, etc.). If the AI does not ask questions as per the prompt, it may be due to model version or setting issues. It is recommended to switch models or try again.

### Q2: Do I need to modify the prompt text myself?
**A**: No. Simply copy and use it directly. If you have special requirements (e.g., you want the AI to ask questions in English), you can modify the language description in the prompt text yourself.

### Q3: Why does the AI sometimes directly give answers without asking questions?
**A**: This is usually because the model is not sensitive enough to the instructions. Try adding the prefix `optimize prompt:` before the prompt, or switch to a more advanced model (e.g., GPT-4, Claude 3.5, etc.), which can significantly increase the AI's probability of asking questions proactively. In addition, please ensure that the AI's deep thinking mode is turned off to avoid the AI over-analyzing the instruction structure and ignoring the execution requirements.

### Q4: Will this prompt leak my privacy?
**A**: The prompt itself does not collect any data. The content of your conversation with the AI is processed by the AI platform you are using. Please refer to the platform's privacy policy. It is recommended not to disclose sensitive personal information in the conversation.

---

## IX. Contribution Guidelines

We welcome you to improve the prompt text itself! If you find better questioning methods, more efficient guiding logic, or want to add specific scenario adaptations, please participate in the following ways:

### 9.1 Submit Improvement Suggestions
Describe your ideas in the Issues section of GitHub or GitCode. We will evaluate and update them.

### 9.2 Share Usage Experiences
Share your success cases or encountered issues when using this prompt in the project discussion area to help other users.

### 9.3 Directly Modify the Text
If you are familiar with Markdown, you can Fork this project, modify the `system_prompt_english.md` file, and submit a Pull Request.

---

## X. License

This project is open-sourced under the MIT License, allowing free use, modification, and distribution, but the copyright notice must be retained.
