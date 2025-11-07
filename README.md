# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim:
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses.

### AI Tools Required: 
ChatGPT

## Introduction: 
Artificial Intelligence (AI) has undergone significant transformation over the past decade, with Large Language Models (LLMs) leading the way in natural language understanding and generation. These models are capable of producing human-like responses, completing tasks, and assisting with decision-making. However, their effectiveness largely depends on the quality of the input prompt provided.

Prompt engineering refers to the practice of carefully designing these inputs to improve the relevance, accuracy, and depth of AI-generated responses. Broad or unstructured prompts often lead to vague or incomplete answers. Refined prompts, on the other hand, guide the model to produce more precise, relevant, and context-aware outputs.

This study investigates three prompting techniques:

### 1.Zero-Shot Prompting:  
- asking the AI to complete a task without providing examples.
### 2.Few-Shot Prompting: 
- guiding the AI with one or more examples.
### 3.Chain-of-Thought Prompting :
- requiring the AI to generate step-by-step reasoning.
Each technique is tested using both broad/unstructured and refined prompts. Outputs from two AI tools are recorded, and their performance is analyzed using rubric-based evaluation.

## Prompt Engineering and Pattern Models:
Pattern models such as GPT-based systems rely on predicting the most probable sequence of tokens based on prior training. These models can handle multiple types of instructions, but the prompt structure often determines how effectively they produce desired responses.

### Broad Prompts: 
Simple, vague instructions (e.g., "Explain photosynthesis.")
### Refined Prompts:
Structured, context-rich instructions (e.g., "Explain photosynthesis to a 10-year-old in simple language using an analogy.")
By comparing responses to these two styles, this study demonstrates the importance of deliberate prompt design.

## Methodology:
### Prompting Techniques Tested:
Zero-Shot, Few-Shot, Chain-of-Thought.
### Scenarios: 
Business, education, and problem-solving contexts.
### Tools Used: 
Tool A and Tool B (representing two advanced AI systems).
### Evaluation Method:
Rubric-based scoring (1–5 scale) for Clarity, Accuracy, Depth, and Relevance.
### Data Collection:
For each scenario, broad and refined prompts were tested with both tools, and results were compared.

## 1. Zero-Shot Prompting
### Explanation
Zero-Shot prompting instructs the model to perform a task without providing any prior examples.

### 
Scenario: Cloud Computing for Small Businesses

### Broad Prompt
"Explain cloud computing."

Tool A Response (Broad) Cloud computing is the use of internet-based services like storage and servers. It helps businesses lower costs and improve flexibility.
Tool B Response (Broad) Cloud computing refers to accessing computing resources through the internet instead of using local infrastructure.

### Refined Prompt
"Summarize the three main advantages of cloud computing for small businesses in terms of cost, scalability, and accessibility."

Tool A Response (Refined) Cloud computing benefits small businesses by reducing upfront IT expenses, enabling scalable infrastructure to match business growth, and offering accessibility for employees working remotely.
Tool B Response (Refined) The advantages of cloud computing for small businesses include reduced capital expenditure, elastic scalability, and global accessibility that supports flexible work environments.

### Evaluation
<img width="587" height="249" alt="Screenshot 2025-11-07 183916" src="https://github.com/user-attachments/assets/1f88dafe-76fd-4d6e-b801-bf302650447a" />

### Analysis
Zero-Shot with broad prompts generated surface-level definitions, while refined prompts delivered structured insights relevant to small businesses.

## 2. Few-Shot Prompting
### Explanation
Few-Shot prompting provides one or more examples in the input, enabling the AI to mimic a style or structure.

### Scenario: Explaining Photosynthesis
### Broad Prompt
"Explain photosynthesis."

Tool A Response (Broad) Photosynthesis is the process where plants make food using sunlight.
Tool B Response (Broad) Plants convert sunlight into energy through photosynthesis, producing glucose and oxygen.

### Refined Prompt with Examples
*"Here are examples:

To a child: ‘Photosynthesis is how plants eat sunlight to grow.’
To a college student: ‘It is the process of converting light energy into glucose using chlorophyll.’ Now, explain photosynthesis to a software engineer."*
Tool A Response (Refined) For a software engineer, photosynthesis is like a function where inputs (sunlight, CO₂, water) are processed by chlorophyll to output glucose and oxygen.
Tool B Response (Refined) Photosynthesis can be understood as a program: sunlight is the input, chlorophyll is the processor, and glucose and oxygen are the outputs.

### Evaluation
<img width="575" height="260" alt="image" src="https://github.com/user-attachments/assets/169a9e7d-020d-4e0e-9d0e-896ddf3dd6cb" />

### Analysis
Few-Shot prompting with examples guided the AI to provide audience-specific explanations, demonstrating adaptability and creativity.

## 3. Chain-of-Thought Prompting
### Explanation
Chain-of-Thought prompting requires the AI to produce reasoning steps before giving the final answer.

### Scenario: Shopkeeper’s Profit
### Broad Prompt
"A shopkeeper bought 10 pens for $50 and sold each for $7. Find his profit."

Tool A Response (Broad) Profit = $20.
Tool B Response (Broad) The shopkeeper gained $20 profit.

### Refined Prompt (Chain-of-Thought)
*"Solve step by step:

Find cost price per pen.
Find selling price for all pens.
Subtract total cost from selling price."*
Tool A Response (Refined) Step 1: Cost per pen = $50 ÷ 10 = $5. Step 2: Selling price for 10 pens = $70. Step 3: Profit = $70 – $50 = $20.
Tool B Response (Refined) Cost per pen = $5. Selling price of 10 pens = $70. Profit = $20.

### Evaluation
<img width="588" height="261" alt="Screenshot 2025-11-07 190040" src="https://github.com/user-attachments/assets/bec5fe74-b922-4979-8444-8f36349be8f1" />

### Analysis: 
Chain-of-Thought prompting ensures detailed reasoning, which improves transparency and builds user trust in the results.

## Applications of Prompting in Real-World Domains
### Business
#### Zero-Shot: 
Quick market insights.
#### Few-Shot: 
Tailored reports for stakeholders.
#### CoT:
Risk analysis with reasoning steps.

### Healthcare
#### Zero-Shot: 
Definitions of medical conditions.
#### Few-Shot: 
Patient communication adjusted by examples.
#### CoT: 
Diagnostic reasoning with transparent steps.

## Limitations and Challenges
- Broad prompts reduce clarity and depth.
- Few-Shot prompting depends on the quality of examples.
- CoT prompting may increase response length and processing time.
- Large prompts can hit size limitations, leading to truncated outputs.

# OUTPUT
<img width="1057" height="323" alt="Screenshot 2025-11-07 190250" src="https://github.com/user-attachments/assets/bfcd9f27-9820-4389-a419-16f23a01b965" />

# RESULT: 
The prompt for the above said problem executed successfully
