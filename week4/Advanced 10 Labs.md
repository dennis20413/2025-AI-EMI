## 📑 Labs Overview

| Lab No. | Lab Name                             | Objective                                    |
|:------:|:-------------------------------------:|:--------------------------------------------:|
| **1**  | Prompt Variables ⚙️                    | Design flexible AI prompts                  |
| **2**  | Automated Template Filling 📝          | Automate text generation                    |
| **3**  | Chain of Thought (CoT) 🔗              | Guide AI through reasoning steps            |
| **4**  | Multi-Step Math 🧮                     | Break down math problems step by step       |
| **5**  | Zero-shot CoT ⚡                       | Answer without prior training               |
| **6**  | Tree-of-Thoughts (ToT) 🌳              | Simulate multiple expert opinions           |
| **7**  | Variable Prompt Design 🔧              | Make prompts adaptable                      |
| **8**  | Historical Chain of Thought 🏛         | Analyze history step-by-step                |
| **9**  | Financial AI Analysis 💰               | AI-assisted calculations                     |
| **10** | Real-Time AI Automation ⏱             | AI-powered solutions                         |

---

# 1. Prompt Variables ⚙️

## Original
We often need flexible prompts that can accommodate different content placeholders. By designing prompts with variables (like `{Language}` or `{ProductName}`), we can quickly adapt to multiple scenarios.

## Prompt
Create a template to generate product descriptions using three placeholders.

## result
Introducing `{ProductName}`, the ultimate solution for all your `{UserNeed}`.  
Now available in `{Language}` for maximum clarity!

- **{ProductName}**: Insert your item name (e.g., “SuperCool Gadget”).  
- **{UserNeed}**: The core value or benefit (e.g., “home entertainment”).  
- **{Language}**: The language you want to use (e.g., “English”).

---

# 2. Automated Template Filling 📝

## Original
Sometimes we rely on a predefined structure for content (e.g., marketing copy or articles) and automatically insert specific data—like product names, features, or prices—into placeholders.

## Prompt
Please use the following template to write a product description for `[Laptop]`. “[Laptop]” is a `[Type]` with `[Feature1]` and `[Feature2]`, offering `[Advantage]`.

## result
“TechNova X2 is a lightweight laptop with a high-resolution display and ultra-fast SSD storage, offering unparalleled speed and clarity for working on the go.”

| Placeholder  | Example Value             |
|-------------:|:-------------------------:|
| `[Laptop]`   | TechNova X2              |
| `[Type]`     | lightweight laptop       |
| `[Feature1]` | high-resolution display  |
| `[Feature2]` | ultra-fast SSD storage   |
| `[Advantage]`| unparalleled speed and clarity |

---

# 3. Chain of Thought (CoT) 🔗

## Original
When asked, “If I have 10 apples, give 3 away, buy 5 more, and eat 1, how many remain?”, many AI systems can answer directly. But a step-by-step (Chain of Thought) approach reveals the reasoning clearly.

## Prompt
Show your reasoning steps to find how many apples remain.

## result
1. Start with 10 apples.  
2. Give away 3 → 10 - 3 = 7.  
3. Buy 5 → 7 + 5 = 12.  
4. Eat 1 → 12 - 1 = 11.  
5. **Answer**: 11 apples remain.

---

# 4. Multi-Step Math 🧮

## Original
A car travels at 60 km/h for 4 hours. We need to explain the calculation step by step to determine the total distance traveled.

## Prompt
Explain the distance traveled, breaking down each step.

## result
1. Speed: 60 km/h  
2. Time: 4 hours  
3. Distance = Speed × Time  
4. 60 × 4 = 240  
5. **Answer**: 240 km

| Step | Detail                          |
|-----:|:--------------------------------|
| 1    | Speed is 60 km/h               |
| 2    | Time is 4 hours                |
| 3    | Use Distance = Speed × Time    |
| 4    | 60 × 4 = 240                   |
| 5    | Total distance is 240 km       |

---

# 5. Zero-shot CoT ⚡

## Original
A student has \$20, buys a \$5 pen and a \$10 book. Without prior training or examples, we want to see the direct solution.

## Prompt
How much money remains?

## result
- **Initial money**: \$20  
- **Spent**: \$5 + \$10 = \$15  
- **Remaining**: \$20 - \$15 = \$5

---

# 6. Tree-of-Thoughts (ToT) 🌳

## Original
Simulating multiple “thought branches” allows the AI to explore various possibilities before concluding the best answer, much like a brainstorming session.

## Prompt
If a ball is dropped between two rooms, let three AI experts propose different ideas about where it might be.

## result
1. **Expert A**: It lands in the connecting hallway.  
2. **Expert B**: It stops at the threshold if a door is closed.  
3. **Expert C**: If there’s an open floor plan, it rolls midway.  

**Conclusion**: The ball’s final position depends on the physical layout and any barriers.

---

# 7. Variable Prompt Design 🔧

## Original
We need adaptable prompts that can handle numeric or contextual variables (e.g., speed, time, distance).

## Prompt
Create a prompt template to compute travel distance using `[Speed]` and `[Time]`.

## result
You have a travel speed of `[Speed]` km/h and a travel time of `[Time]` hours. Calculate the total distance and explain the steps.

| Variable  | Description          |
|:---------:|:--------------------:|
| `[Speed]` | Velocity in km/h    |
| `[Time]`  | Duration in hours   |

---

# 8. Historical Chain of Thought 🏛

## Original
Analyzing historical events often involves a step-by-step breakdown of economic, social, and military factors, such as the fall of the Roman Empire.

## Prompt
Explain the fall of the Roman Empire in a step-by-step manner.

## result
1. **Economic Strain**: Heavy taxes and inflation undermined financial stability.  
2. **Military Overreach**: Large territories drained resources.  
3. **Political Turmoil**: Corruption and internal power struggles.  
4. **External Invasions**: Various groups exploited weakened borders.  
5. **Outcome**: Central authority collapsed.

---

# 9. Financial AI Analysis 💰

## Original
A restaurant makes \$100 per seat, has 50 seats, and operates 7 days a week. We want weekly revenue and a breakdown.

## Prompt
Compute the weekly revenue and show each step.

## result
1. **Revenue per seat/day**: \$100  
2. **Number of seats**: 50  
3. **Daily total**: \$100 × 50 = \$5,000  
4. **Weekly total**: \$5,000 × 7 = \$35,000  
5. **Answer**: \$35,000 weekly

---

# 10. Real-Time AI Automation ⏱

## Original
We have a continuously updated dataset (e.g., temperature, humidity). Our goal is an AI-powered system that analyzes these updates in real time to provide a concise summary.

## Prompt
Automate data extraction and generate a daily summary of the provided data points.

## result
**Example Summary**  
- **Average Temperature**: 21.8°C  
- **Highest Humidity**: 88% at 2 PM  
- **Alerts**: 2 (filter replacement, high temp spike)  
- **Recommended Action**: Increase ventilation during peak hours
