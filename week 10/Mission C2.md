# 🛍️ AI-Driven Emotional Retail Analytics System (AERAS)  
> Using Camera-Based Emotion Recognition to Optimize Product Strategy and Customer Experience

---

## 💡 Concept Overview  
AERAS is an in-mall AI system embedded in existing security or smart retail cameras to detect and analyze customer emotional reactions when they interact with products. It focuses on identifying **positive intent (purchase or interest)** and **negative emotion signals (disgust, hesitation, disapproval)**. Based on these insights, the system informs **sales optimization** strategies and triggers **targeted product surveys** for items with high negative sentiment — thereby reducing costs, minimizing returns, and improving product-market fit.

---

## 🎯 Use Case Scenarios

- 🧍 A customer picks up a product, examines it, but puts it back with a slight frown or sneer.  
- 😐 Another customer holds a product for a long time while visibly hesitating — showing confusion or uncertainty.  
- 😄 A different shopper smiles and proceeds to checkout after engaging with a specific item.  

All these scenarios are captured, classified, and used to adjust merchandising, layout, and inventory planning.

---

## 🧬 Key System Features

| Feature | Description |
|--------|-------------|
| 🎥 **Emotion Tracking Camera Integration** | Uses OpenCV + DNN models embedded in mall CCTV to detect facial expressions in proximity to shelves. |
| 📦 **Product-Centric Emotion Mapping** | Matches facial emotion to specific product shelves via position correlation and item IDs. |
| 📊 **Negative Feedback Trigger Engine** | Flags items that consistently cause disgust or rejection for deeper investigation. |
| 🧪 **Targeted Customer Surveys** | Pushes mini-surveys (via kiosk, app, or QR) to customers who interacted with flagged items. |
| 📈 **Sales Heatmaps + Emotion Correlation** | Merges sales data and emotional response metrics to optimize layout and promotional effort. |

---

## 🛠️ Technologies Used

- 🤖 **Emotion Detection DNNs** – trained on FER+, AffectNet, or custom retail datasets.  
- 📍 **Shelf-to-Camera Spatial Mapping** – ensures facial data is matched to specific product positions.  
- 📹 **OpenCV / MediaPipe for Real-Time Facial Keypoint Extraction**.  
- 📶 **Retail Inventory APIs** – for real-time tracking of item sales and restocking.  
- 🗣️ **Survey Engine** – integrated into existing POS, membership apps, or mall apps.

---

## 🧠 Emotional Response Categories

| Emotion | Behavior Indicator | Business Insight |
|--------|--------------------|------------------|
| 😄 Happy / Excited | Likely to buy | Promote similar items |
| 😐 Confused / Hesitant | Wants more info | Improve labeling, staff assistance |
| 😠 Disgusted / Rejected | Likely to avoid | Flag for survey and product re-evaluation |

---

## 🧾 Workflow Diagram  
*To be inserted here: customer enters → interacts with shelf → emotion detected → item ID mapped → logged → action triggered*  
🖼️ `assets/aeras_flowchart.png`

---

## 📊 Survey Trigger Logic (Simplified)

```python
for each interaction:
    if emotion in ['disgust', 'rejection']:
        item_emotion_score[item_id] += 1
    if item_emotion_score[item_id] > threshold:
        trigger_survey(item_id)
```

---

## 📈 Analytics Dashboard Outputs

- 🧭 Emotion Heatmap Overlay (on store map)  
- 📉 High "rejection rate" product reports  
- 📋 Survey response summaries per item  
- 💬 NLP topic clustering from open-ended feedback

---

## 🔐 Ethical Safeguards

- 🙈 No personally identifiable data stored  
- 🎭 Blurred face + consent-based survey prompts  
- 🔍 Aggregated, anonymized behavior reporting only  
- 👥 Diverse dataset training to avoid expression bias

---

## 📘 Future Development Ideas

- 🤝 Integrate with AR smart mirrors for in-shelf feedback  
- 🛍️ Dynamic pricing triggers based on interest/emotion correlation  
- 🧑‍🤝‍🧑 Emotion clustering to improve group segmentation (e.g., teens vs. elders)  
- 🧠 Deep reinforcement learning to auto-adjust product placement based on emotion-sentiment response ratios  

---

> 🧠 Inspired by affective computing, shopper psychology, and camera-AI integration.  
> ⚠️ Ensure ethical compliance with local data privacy and AI use regulations.
