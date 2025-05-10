# Prompt-Engineering-4
### Name: DAPPILI VASAVI
### Reg No: 212223040030
# EXP 4 Scenario-Based Report Development Utilizing Diverse Prompting Techniques- Lab Scenario: Smart Health Assistant System
# Description: 
## Background:
You are part of a development team working on an AI-based Smart Health Assistant named "MediGuide" that assists elderly patients in managing chronic diseases like diabetes, hypertension, and arthritis. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

## Objective:
Develop a scenario-based report that demonstrates how diverse prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, and multi-modal prompts) can be used to optimize MediGuide’s responses in different use cases.

# Algorithm:

### Step 1: Data Collection
1. **Input Data**: Provide the healthcare case data (e.g., symptoms, medical history, test results) in a structured format.
2. **Select AI Tools**: Choose two AI platforms for evaluation: **ChatGPT** and **Claude**.

### Step 2: Apply Different Prompting Techniques
1. **Straightforward Prompts**:
   - Prompt: Provide basic symptoms and request a diagnosis and treatment suggestion.
   - Example Prompt: "The patient presents with shortness of breath, fever, and chest pain. Based on these symptoms, what is the likely diagnosis and treatment?"

2. **Tabular Format Prompting**:
   - Present the data in a table format, listing symptoms, medical history, and test results.
   - Example Prompt: "Here’s the patient data in a tabular format: [Table with symptoms, medical history, and test results]. Based on this, what would be the likely diagnosis and recommended treatment?"

3. **Missing Word Prompting**:
   - Provide a partially completed sentence and ask the AI to fill in the missing information.
   - Example Prompt: "The patient's likely diagnosis is _____, and the recommended treatment involves _____."

### Step 3: Submit to AI Platforms
1. **Submit Prompt to ChatGPT**: Use the selected prompt with **ChatGPT**.
2. **Submit Prompt to Claude**: Use the same selected prompt with **Claude**.

### Step 4: Collect Responses
1. **ChatGPT Output**: Collect and store ChatGPT's response.
2. **Claude Output**: Collect and store Claude's response.

### Step 5: Evaluation Criteria
1. **Accuracy**: Check if the AI correctly identifies the disease and recommends suitable treatment.
2. **Completeness**: Ensure that the AI's response includes all necessary diagnostic steps and treatment plans.
3. **Simplicity**: Evaluate if the response is easy to understand, especially for non-medical professionals.
4. **Coherence**: Assess if the response is logically structured and follows a clear reasoning process.

### Step 6: Comparative Analysis
1. Compare **ChatGPT** and **Claude** based on the evaluation criteria.
2. Identify strengths and weaknesses of each AI platform in terms of clarity, specificity, and appropriateness of the response.

### Step 7: Generate Report
1. **Tabulate Findings**: Present the results in a table format for easy comparison.
2. **Conclusion**: Summarize the findings, highlighting the best-performing platform for each prompt type.
3. **Recommendations**: Suggest the most effective prompting strategy and platform based on the evaluation.

### Step 8: Reporting
- Output the final evaluation report, including the comparison of accuracy, completeness, simplicity, and coherence for each AI platform.

---

# OUTPUT 
## 📚 Use Case
# Healthcare Use Case: AI-driven Diagnostics and Recommendations

## Objective:
To compare the effectiveness of three distinct prompt types—

**Straightforward Prompts**
**Tabular Format Prompting**, 
**Missing Word Prompting**
—across two different AI platforms (e.g., **ChatGPT** and **Claude**) for generating healthcare diagnostics and recommendations.

---

## AI Tools Used:
1. **ChatGPT** (GPT-4)
2. **Claude** (Anthropic AI)

---
## Prompts Used:

### 1. **Straightforward Prompts**:
Objective: Directly ask the AI to provide a diagnosis or recommendation based on provided symptoms and patient information.

**Prompt Example**:
"Given the symptoms of high fever (39°C), persistent cough, and shortness of breath, provide a possible diagnosis and recommend treatment options."

---

**ChatGPT Output**:
"Based on the symptoms of high fever (39°C), persistent cough, and shortness of breath, a possible diagnosis is **pneumonia** or **COVID-19**. It is recommended to administer antiviral or antibiotic treatment depending on the suspected cause. A chest X-ray and blood tests are advised for confirmation."

**Claude Output**:
"The symptoms of high fever (39°C), persistent cough, and shortness of breath suggest **viral pneumonia** or **COVID-19**. The recommended course of action is to provide supportive care (fluids, fever management) and consider antiviral treatments. A CT scan and COVID-19 test are recommended."

---

## Evaluation:

| **Criteria**     | **ChatGPT**                                         | **Claude**                                       |
|------------------|----------------------------------------------------|-------------------------------------------------|
| **Accuracy**     | Both identified pneumonia or COVID-19 as likely diagnoses, which was appropriate. | Both identified pneumonia or COVID-19 as likely diagnoses, which was appropriate. |
| **Coherence**    | Provided a clear and concise response.            | Provided a coherent response, with a more specific recommendation for a CT scan. |
| **Simplicity**   | Response was straightforward and easy to follow.  | Response had more technical detail but was slightly less accessible. |
| **User Experience** | Used more general language, which was easy for a broader audience. | Response included more technical detail, which could be more suited for a clinical setting. |

---
## Final Summary:

- **ChatGPT** provided clear, simple, and user-friendly responses, ideal for general use cases.
- **Claude** delivered more detailed and technical responses, with a focus on more specific recommendations, which could be useful in clinical environments.

---
---

### 2. **Tabular Format Prompting**:
Objective: Present information in a tabular format for clarity, then ask the AI to analyze and interpret the data.

**Prompt Example**:
"Below is a table with patient symptoms and vital signs. Based on this, provide a diagnosis and suggest treatment options.

| Symptom              | Measurement   |
|----------------------|---------------|
| Temperature          | 39°C          |
| Heart Rate           | 105 bpm       |
| Respiratory Rate     | 22 breaths/min|
| Cough                | Persistent    |
| Shortness of Breath  | Present       |

Interpret the data and give a diagnosis."

---

**ChatGPT Output**:
"Based on the provided data:
- Temperature: 39°C
- Heart Rate: 105 bpm
- Respiratory Rate: 22 breaths/min
- Persistent Cough and Shortness of Breath

Diagnosis: Likely **pneumonia** or **viral infection**. Further tests such as a chest X-ray and blood cultures are required. Supportive care including hydration and fever control is recommended."

**Claude Output**:
"Analysis of the patient's vital signs and symptoms suggests the diagnosis of **respiratory infection** (potentially pneumonia or COVID-19). Immediate testing (X-ray and blood test) is essential to confirm the condition. Management includes supportive care and possibly antiviral treatment."

---

## Evaluation:

| **Criteria**     | **ChatGPT**                                         | **Claude**                                       |
|------------------|----------------------------------------------------|-------------------------------------------------|
| **Accuracy**     | Both outputs identified pneumonia or a viral infection as the most likely diagnosis. | Both outputs identified pneumonia or a viral infection as the most likely diagnosis. |
| **Clarity**      | Provided clearer, more structured recommendations. | Slightly more concise output but still accurate. |
| **Simplicity**   | Response had more thorough explanations, making it easier for non-experts. | More direct and to the point, may be better for experts. |
| **Speed**        | Quickly generated the response based on the tabular input. | Generated the response almost as quickly as ChatGPT. |

---

## Final Summary:

- **ChatGPT** provided a more detailed, user-friendly response, making it better for general users who require a deeper explanation.
- **Claude** delivered a more concise output, suitable for those seeking quick and direct answers without detailed elaboration.

---

### 3. **Missing Word Prompting**:
Objective: Present a partially completed sentence or data and have the AI complete it by filling in the missing words or information.

**Prompt Example**:
"The patient presents with a fever of 39°C and a respiratory rate of 22 breaths per minute. Based on these observations, the diagnosis is most likely ___ (options: pneumonia, influenza, asthma, etc.). Fill in the missing diagnosis and suggest next steps for treatment."

---
**ChatGPT Output**:
"The patient presents with a fever of 39°C and a respiratory rate of 22 breaths per minute. Based on these observations, the diagnosis is most likely **pneumonia**. Treatment should include antibiotics and supportive care, along with further diagnostic tests like a chest X-ray and blood work."

**Claude Output**:
"The patient presents with a fever of 39°C and a respiratory rate of 22 breaths per minute. Based on these observations, the diagnosis is most likely **viral pneumonia**. Immediate antiviral treatment should be considered, along with supportive care and a chest X-ray to confirm the diagnosis."

---

## Evaluation:

| **Criteria**      | **ChatGPT**                                                   | **Claude**                                                   |
|-------------------|--------------------------------------------------------------|-------------------------------------------------------------|
| **Accuracy**      | Both platforms correctly identified pneumonia as the likely diagnosis, with ChatGPT focusing on bacterial pneumonia and Claude emphasizing viral pneumonia. | Both platforms correctly identified pneumonia as the likely diagnosis, with ChatGPT focusing on bacterial pneumonia and Claude emphasizing viral pneumonia. |
| **Completeness**  | Both responses offered comprehensive next steps in treatment and diagnostics, ensuring no critical information was omitted. | Both responses offered comprehensive next steps in treatment and diagnostics, ensuring no critical information was omitted. |
| **Simplicity**    | ChatGPT provided a clearer and more concise recommendation, catering to a broader audience. | Claude offered a more specific recommendation, with a focus on antiviral treatment, which may be better suited for medical professionals. |
| **Coherence**     | Both responses were coherent and logically structured; however, Claude’s output exhibited a slightly higher degree of specificity, providing greater depth in certain areas. | Both responses were coherent and logically structured; however, Claude’s output exhibited a slightly higher degree of specificity, providing greater depth in certain areas. |


## Conclusion:

- **ChatGPT** demonstrated a more straightforward, user-friendly approach, offering clear and concise explanations suitable for general audiences.
- **Claude**, on the other hand, provided a response with increased specificity, particularly in terms of treatment details, which may appeal more to healthcare professionals seeking precise guidance.

---

## Final Comparative Evaluation:

| **Prompt Type**             | **Best Performing Platform** | **Strengths**                           | **Weaknesses**                                |
|-----------------------------|------------------------------|-----------------------------------------|------------------------------------------------|
| **Straightforward Prompts**  | **Tie** (ChatGPT & Claude)    | Both platforms provided accurate diagnoses and clear recommendations. | Claude was slightly more specific with test recommendations. |
| **Tabular Format Prompting** | **ChatGPT**                   | More structured and clear treatment recommendations. | Claude was concise but could have offered more clarity. |
| **Missing Word Prompting**   | **ChatGPT**                   | More concise, clear, and easy to understand. | Claude's recommendation for antiviral treatment was more specific. |

---

## Final Conclusion:

- **ChatGPT** performed well in terms of clarity, simplicity, and speed. It provided responses that were easy to understand and sufficient for general use.
- **Claude** provided more technical specificity, particularly in terms of test recommendations and treatments, which could be beneficial for a more clinical setting.

---

# Result
Thus, Both platforms were effective for the given healthcare use case, but **ChatGPT** was more user-friendly, while **Claude** offered more in-depth, technical insights.



