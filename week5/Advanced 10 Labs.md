# 🚀 AI Lab Experiments Overview

## 📑 Lab Summaries

| Lab No. | Lab Name                            | Objective                                    |
|:------:|:----------------------------------:|:--------------------------------------------:|
| **1**  | Prompt Variables ⚙️                 | Design flexible AI prompts                  |
| **2**  | Automated Template Filling 📝       | Automate text generation                    |
| **3**  | Chain of Thought (CoT) 🔗           | Guide AI through reasoning steps            |
| **4**  | Multi-Step Math 🧮                  | Break down math problems step by step       |
| **5**  | Zero-shot CoT ⚡                    | Answer without prior training               |
| **6**  | Tree-of-Thoughts (ToT) 🌳           | Simulate multiple expert opinions           |
| **7**  | Variable Prompt Design 🔧           | Make prompts adaptable                      |
| **8**  | Historical Chain of Thought 🏛      | Analyze history step-by-step                |
| **9**  | Financial AI Analysis 💰            | AI-assisted calculations                     |
| **10** | Real-Time AI Automation ⏱          | AI-powered solutions                         |

---

## 1️⃣ Prompt Variables ⚙️
### 🔹 Description
Flexible prompts allow AI to generate adaptable content by inserting **variables** such as `{ProductName}` or `{Language}` into predefined templates.

### 🔹 Example Prompt
```
Create a template to generate product descriptions using 6 placeholders in English, Chinese, and Japanese.
```

### 🔹 Example Output
```
Introducing {ProductName}, the ultimate solution for {UserNeed}. Now available in {Language} for maximum clarity!
```
| Placeholder  | Example Value        |
|-------------|--------------------|
| `{ProductName}` | SuperCool Gadget    |
| `{UserNeed}`  | home entertainment  |
| `{Language}`  | English             |

---

## 2️⃣ Automated Template Filling 📝
### 🔹 Description
This approach allows AI to automatically fill structured templates with relevant content, ensuring consistency in generated outputs.

### 🔹 Example Prompt
```
Please use the following template to write a product description for [car]:
[Product Name] is a [Type] with [Feature 1] and [Feature 2], offering [Advantage].
```

### 🔹 Example Output
```
TechNova X2 is a lightweight laptop with a high-resolution display and ultra-fast SSD storage, offering unparalleled speed and clarity for working on the go.
```
| Placeholder  | Example Value             |
|-------------|-------------------------|
| `[Product Name]` | TechNova X2             |
| `[Type]`  | lightweight laptop      |
| `[Feature 1]`  | high-resolution display  |
| `[Feature 2]`  | ultra-fast SSD storage   |
| `[Advantage]`  | unparalleled speed and clarity |

---

## 3️⃣ Chain of Thought (CoT) 🔗
### 🔹 Description
AI is guided through a **step-by-step reasoning process**, enhancing logical thinking and improving complex problem-solving skills.

### 🔹 Example Prompt
```
If I have 10 apples, give 3 away, buy 5 more, and eat 1, how many remain?
```

### 🔹 Example Output
1. Start with **10 apples**.
2. Give away **3** → 10 - 3 = **7**.
3. Buy **5 more** → 7 + 5 = **12**.
4. Eat **1** → 12 - 1 = **11**.
5. **Final Answer:** 11 apples remain.

---

## 4️⃣ Multi-Step Math 🧮
### 🔹 Description
AI breaks down complex math problems into **step-by-step logical solutions** to enhance clarity and accuracy.

### 🔹 Example Prompt
```
A car travels 60 km/h for 4 hours. How far does it go? Explain step-by-step.
```

### 🔹 Example Output
1. Speed = **60 km/h**.
2. Time = **4 hours**.
3. Distance = Speed × Time.
4. **60 × 4 = 240 km**.
5. **Final Answer:** 240 km traveled.

---

## 5️⃣ Zero-shot CoT ⚡
### 🔹 Description
AI answers questions **without prior training** or provided examples, testing reasoning capabilities.

### 🔹 Example Prompt
```
A student has 20 dollars, buys a pen for 5 dollars, a book for 10 dollars. How much remains?
```

### 🔹 Example Output
1. Initial money: **$20**.
2. Expenses: **$5 (pen) + $10 (book) = $15**.
3. Remaining: **$20 - $15 = $5**.

---

## 6️⃣ Tree-of-Thoughts (ToT) 🌳
### 🔹 Description
AI explores **multiple thought processes** before converging on the best conclusion, simulating human-like analysis.

### 🔹 Example Prompt
```
Where is the ball if someone moves it between rooms? Let three AI experts analyze the answer.
```

### 🔹 Example Output
1. **Expert A**: It lands in the connecting hallway.
2. **Expert B**: It stops at the threshold if a door is closed.
3. **Expert C**: If there’s an open floor plan, it rolls midway.

**Conclusion:** The ball’s final position depends on room layout and movement constraints.

---

## 7️⃣ Variable Prompt Design 🔧
### 🔹 Description
AI-generated prompts **adapt dynamically** to different input values, making AI outputs **highly customizable**.

### 🔹 Example Prompt
```
Create a prompt template for computing travel distance based on [Speed] and [Time].
```

### 🔹 Example Output
You have a travel speed of `[Speed]` km/h and a travel time of `[Time]` hours. Calculate the total distance using Distance = Speed × Time.

---

## 8️⃣ Historical Chain of Thought 🏛
### 🔹 Description
AI analyzes **historical events step-by-step**, ensuring logical progression in complex historical analyses.

### 🔹 Example Prompt
```
Explain the fall of the Roman Empire step-by-step.
```

### 🔹 Example Output
1. **Economic Strain**: High taxes and inflation.
2. **Military Overreach**: Resources stretched too thin.
3. **Political Turmoil**: Corruption and leadership instability.
4. **External Invasions**: Weakened borders led to attacks.

---

## 9️⃣ Financial AI Analysis 💰
### 🔹 Description
AI performs **financial calculations** based on real-world business scenarios.

### 🔹 Example Prompt
```
A restaurant makes $100 per seat. If it has 50 seats and operates 7 days a week, calculate weekly revenue.
```

### 🔹 Example Output
Revenue per seat/day: **$100** × **50 seats** = **$5,000**
Weekly revenue: **$5,000 × 7** = **$35,000**

---

## 🔟 Real-Time AI Automation ⏱
### 🔹 Description
AI extracts and summarizes **real-time data**, enabling automation in reporting and analysis.

### 🔹 Example Prompt
```
Automate data extraction and generate a summary for the provided dataset.
```

### 🔹 Example Output
**Summary:**
- **Average Temperature:** 21.8°C
- **Highest Humidity:** 88% at 2 PM
- **Alerts:** 2 (filter replacement, high temp spike)
