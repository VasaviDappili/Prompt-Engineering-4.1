# Prompt-Engineering-4
### Name: DAPPILI VASAVI
### Reg No: 212223040030
# EXP 4 Scenario-Based Report Development Utilizing Diverse Prompting Techniques- Lab Scenario: Smart Health Assistant System
# Description: 
## Background:
You are part of a development team working on an AI-based Smart Health Assistant named "MediGuide" that assists elderly patients in managing chronic diseases like diabetes, hypertension, and arthritis. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

## Objective:
Develop a scenario-based report that demonstrates how diverse prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, and multi-modal prompts) can be used to optimize MediGuide’s responses in different use cases.


## 📊 Algorithm
## Step 1: Data Collection
Input: Simulated patient data (e.g., symptoms, vitals, test results)

Platforms: ChatGPT (GPT-4) and Claude (Anthropic)

## Step 2: Apply Prompting Techniques
Zero-shot Prompting: No examples given—directly asks for diagnosis and treatment.

Few-shot Prompting: Provides 2–3 examples before asking for analysis.

Chain-of-Thought Prompting: Promotes step-by-step reasoning.

Role-based Prompting: Assigns a role to the model (e.g., "act as a geriatric doctor").

Multi-modal Prompting: Incorporates images or tables alongside text prompts (used with simulated tabular health data).

## Step 3: Input Prompts into AI Platforms
Submit each type of prompt to ChatGPT and Claude for analysis.

## Step 4: Collect and Evaluate Responses
Analyze outputs for:

1.Accuracy

2.Completeness

3.Clarity & Simplicity

4.Coherence

5.Relevance to elderly care

## Step 5: Compare Results
Evaluate platform performance for each prompting method.

## Step 6: Generate Report
Tabulate responses and summarize findings.

## ⚕️ Use Case: AI-powered Diagnostics for Elderly Patients
Simulated Patient Scenario:
Age: 72
Gender: Female
Symptoms: Fatigue, increased thirst, frequent urination, blurred vision
History: Type 2 Diabetes, Hypertension
Vitals: Blood Sugar: 250 mg/dL, BP: 150/90 mmHg

## 🤖 Prompting Techniques & Responses
## 1. Zero-shot Prompting
## Prompt:
"A 72-year-old woman presents with fatigue, frequent urination, and blurred vision. She has a history of diabetes and high blood pressure. What is the likely diagnosis and treatment plan?"

## ChatGPT Output:

"The symptoms suggest uncontrolled Type 2 Diabetes (likely hyperglycemia). Treatment includes adjusting insulin or oral medications, lifestyle modifications (diet, exercise), and regular monitoring."

## Claude Output:

"This case appears to involve hyperglycemia due to poorly controlled Type 2 Diabetes. Treatment involves reassessing her diabetes management plan, possibly intensifying medication, monitoring blood glucose, and encouraging hydration."

| Criteria     | ChatGPT                                     | Claude                        |
| ------------ | ------------------------------------------- | ----------------------------- |
| Accuracy     | Correctly identified diabetes complications | Same                          |
| Simplicity   | Clear, easy to understand                   | More clinical tone            |
| Coherence    | Logical and well-structured                 | Structured and specific       |
| Completeness | Slightly more general                       | More detailed follow-up steps |

## 2. Few-shot Prompting
## Prompt:
"Here are examples:

A 68-year-old with chest pain and BP 180/110 was diagnosed with hypertension crisis.

A 75-year-old with tremors and rigidity was diagnosed with Parkinson’s.

Now, a 72-year-old woman presents with fatigue, frequent urination, and blurred vision. She has a history of diabetes and hypertension. What is your diagnosis and plan?"

## ChatGPT Output:

"Based on the symptoms and examples, this patient is likely experiencing hyperglycemia. Adjust diabetes meds, emphasize lifestyle interventions, and follow up with blood sugar monitoring."

## Claude Output:

"This resembles hyperglycemia due to poor diabetes control. A1C testing and medication reassessment are advised, along with dietary counseling and blood pressure monitoring."

| Criteria  | ChatGPT                            | Claude                             |
| --------- | ---------------------------------- | ---------------------------------- |
| Accuracy  | Matches condition well             | Same                               |
| Relevance | Incorporated context appropriately | Included further detail (A1C test) |
| Clarity   | Clear for general users            | Suitable for clinicians            |

## 3. Chain-of-Thought Prompting
## Prompt:
"The patient reports fatigue and frequent urination. These are common symptoms of hyperglycemia. Given her blood sugar of 250 mg/dL and diabetes history, what is your step-by-step diagnosis and recommendation?"

## ChatGPT Output:

"Step 1: Evaluate symptoms—fatigue and polyuria suggest hyperglycemia.
Step 2: Confirm with glucose reading (250 mg/dL).
Step 3: Assess current medication adherence.
Step 4: Adjust medications, monitor glucose, advise lifestyle changes."

## Claude Output:

"Step 1: Identify symptoms.
Step 2: Check lab values—250 mg/dL is high.
Step 3: Evaluate current therapy.
Step 4: Recommend dose adjustment, nutritionist referral, and regular follow-up."

| Criteria      | ChatGPT                   | Claude                          |
| ------------- | ------------------------- | ------------------------------- |
| Reasoning     | Strong step-by-step logic | Same                            |
| Completeness  | Comprehensive plan        | Included referral (added value) |
| Accessibility | Very understandable       | Slightly more technical         |

## 4. Role-based Prompting
## Prompt:
"You are a geriatric care physician. A 72-year-old female with a history of diabetes and hypertension complains of blurred vision and fatigue. Suggest a tailored diagnosis and management plan."

## ChatGPT Output:

"As a geriatric physician, I suspect hyperglycemia, possibly exacerbated by comorbidities. Management includes medication review, dietary changes, and vision screening."

## Claude Output:

"As a specialist in elderly care, I would consider diabetes-related complications including retinopathy. A referral to ophthalmology, adjustment of therapy, and monitoring is necessary."

| Criteria      | ChatGPT                        | Claude                                |
| ------------- | ------------------------------ | ------------------------------------- |
| Role accuracy | Aligned with geriatric context | More depth on elderly-specific issues |
| Tailoring     | Moderate                       | Highly focused on elderly needs       |
| Specificity   | Broad recommendations          | Included specialist referral          |

## 5. Multi-modal Prompting (with Table)
## Prompt:
"Analyze the table below and provide a diagnosis and treatment plan:

| Parameter       | Value                                       |
| --------------- | ------------------------------------------- |
| Age             | 72 years                                    |
| Blood Sugar     | 250 mg/dL                                   |
| Blood Pressure  | 150/90 mmHg                                 |
| Symptoms        | Fatigue, blurred vision, frequent urination |
| Medical History | Diabetes, Hypertension                      |

What is the likely condition and recommended care?"

## ChatGPT Output:

"This patient likely has hyperglycemia. Recommendations: medication adjustment, low-GI diet, monitor vitals, vision exam."

## Claude Output:

"Diagnosis: Poorly controlled diabetes (hyperglycemia). Management: Optimize meds, refer to ophthalmology, monitor BP."

| Criteria     | ChatGPT                    | Claude                                 |
| ------------ | -------------------------- | -------------------------------------- |
| Table Use    | Effectively processed data | Effectively processed + added referral |
| Completeness | Slightly brief             | More actionable follow-up              |

## 📊 Final Comparative Table

| Prompt Type           | Best Performer | Highlights                                   | Weaknesses                          |
| --------------------- | -------------- | -------------------------------------------- | ----------------------------------- |
| Zero-shot Prompting   | Claude         | More specific treatment steps                | Slightly clinical tone              |
| Few-shot Prompting    | ChatGPT        | Generalizable and understandable             | Lacked clinical testing references  |
| Chain-of-Thought      | Tie            | Logical and structured reasoning by both     | Claude a bit more technical         |
| Role-based Prompting  | Claude         | Better geriatric focus                       | Could be too specific for lay users |
| Multi-modal Prompting | Claude         | Used table data well, gave actionable output | Slightly denser phrasing            |

## 🧾 Conclusion
ChatGPT excelled in user-friendliness, conversational clarity, and ease of understanding—ideal for elderly users or caregivers.

Claude demonstrated clinical precision, deeper reasoning, and domain-specific tailoring—suited for healthcare environments.

Chain-of-thought and role-based prompting were especially effective in eliciting rich, diagnostic reasoning and patient-specific care suggestions.

Multi-modal prompting (e.g., using tabular data) enabled more accurate, structured interpretation by both models.

## Result
Thus, Both platforms were effective for the given healthcare use case, but **ChatGPT** was more user-friendly, while **Claude** offered more in-depth, technical insights.


