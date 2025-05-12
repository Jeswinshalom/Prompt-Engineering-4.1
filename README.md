#  Experiment 3: Scenario-Based Report Using Diverse Prompting Techniques

##  Lab Scenario: Smart Health Assistant System – "MediGuide"

###  Background
You are part of a development team building **MediGuide**, an AI-based Smart Health Assistant for elderly patients managing chronic conditions like **diabetes**, **hypertension**, and **arthritis**. MediGuide offers:
- Personalized health tips
- Medication reminders
- Emotional support via natural conversation

---

###  Objective
Demonstrate how different **prompting techniques** improve MediGuide’s responses across various healthcare scenarios.

---

##  Prompting Techniques Demonstrated

-  Zero-Shot Prompting  
-  Few-Shot Prompting  
-  Chain-of-Thought Prompting  
-  Role-Based Prompting  
-  Multi-Modal Prompting

---

##  Use Case Scenarios with Prompts & Responses

### 1️. Zero-Shot Prompting
**Scenario**: Elderly user asks, *“Can I eat bananas if I have diabetes?”*

**Prompt**:  
Can a person with diabetes eat bananas?  

**Response**:
> Yes, people with diabetes can eat bananas in moderation. Bananas contain carbohydrates that can raise blood sugar, so portion size is important. Pair with a protein or healthy fat for better glucose control.

---

### 2️. Few-Shot Prompting
**Scenario**: User regularly seeks dietary advice.

**Prompt**:  
Q: Can I drink orange juice if I have diabetes?  
A: Orange juice contains natural sugars. It’s best consumed in small amounts or avoided.  

Q: What are healthy snacks for diabetics?  
A: Greek yogurt, boiled eggs, unsalted nuts, or carrot sticks.  

Q: Can I eat bananas if I have diabetes?  
**Response**:
> Yes, bananas can be part of a diabetic-friendly diet if eaten in moderation. Try smaller bananas and monitor your blood sugar.

---

### 3️. Chain-of-Thought Prompting
**Scenario**: User reports dizziness after hypertension medication.

**Prompt**:  
A user reports dizziness after taking hypertension medication. Think step-by-step and explain possible causes.  

**Response**:
> Dizziness may occur due to a sudden drop in blood pressure caused by the medication. Other factors include dehydration, standing quickly, or drug interactions. Regular episodes should be discussed with a doctor.

---

### 4️. Role-Based Prompting
**Scenario**: User feels lonely in the evening.

**Prompt**:  
You are MediGuide, a kind and supportive virtual assistant. Offer emotional comfort to an elderly patient feeling lonely.  

**Response**:
> I'm here with you. It's okay to feel lonely sometimes. Would you like to chat, hear a calming tip, or talk about something that makes you smile? You're not alone.

---

### 5️. Multi-Modal Prompting
**Scenario**: User uploads a breakfast photo and asks if it's diabetes-friendly.

**Prompt** (text + image):  
User uploads image of oatmeal, fruits, and green tea.  
Prompt: Is this breakfast okay for diabetes?  

**Response**:
> Your breakfast looks healthy! Oatmeal helps manage blood sugar, fruits are good in moderation, and green tea is a great choice. Avoid added sugars in oatmeal.

---

##  Algorithm (Conceptual Flow)  
Input (Text/Image) ➝ Identify Context ➝ Select Prompting Technique ➝ AI Response Generation ➝ Tone & Clarity Optimization ➝ Output  

---

##  Results  

| Prompting Type     | Scenario               | Response Quality | Tone       | Personalization |
|--------------------|------------------------|------------------|------------|------------------|
| Zero-Shot          | Basic Q&A              | Accurate         | Neutral    | Low              |
| Few-Shot           | Diet Tips              | Context-aware    | Informative| Medium           |
| Chain-of-Thought   | Symptom Analysis       | Logical          | Reassuring | High             |
| Role-Based         | Emotional Support      | Empathetic       | Warm       | Very High        |
| Multi-Modal        | Image Evaluation       | Interactive      | Supportive | High             |

---

## 📌 Conclusion
By leveraging diverse prompting techniques, MediGuide adapts its tone, accuracy, and support level based on the user's needs, making it a reliable companion for elderly health management.

---
