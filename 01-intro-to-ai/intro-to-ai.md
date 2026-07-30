# Introduction to Artificial Intelligence

**Meyssem Bouzaien** : Academic Year 2025-2026



---

## Outline

1. Introduction and Context
2. History of Artificial Intelligence
3. Fields and Applications of AI
4. Branches of Artificial Intelligence
5. AI, Machine Learning and Data Mining
6. Types of Learning in Machine Learning
7. Challenges and the Future of AI
8. Conclusion

---

## 1. What is Artificial Intelligence?

**Fundamental question:** Can we create machines capable of thinking and acting like humans?

| Human Intelligence | Artificial Intelligence |
|---|---|
| Learning from experience | Automated learning |
| Solving problems | Decision making |
| Adapting to new situations | Image recognition |
| Understanding language | Natural language processing |
| Recognizing patterns | Predictions and recommendations |

### Definition (John McCarthy, 1956)
Artificial Intelligence is "the science and engineering of making intelligent
machines," particularly intelligent computer programs.

### Definition (Modern definition)
AI is a set of **techniques** that allow machines to:
- Perform tasks that normally require human intelligence
- Learn from data
- Improve with experience
- Make decisions autonomously

---

## 2. Why AI Now?

**The Convergence of 3 Factors**

1. **Massive Data**
   - Internet
   - Social media
   - IoT sensors
   - Smartphones
2. **Computing Power**
   - Powerful GPUs
   - Cloud computing
   - Parallel computing
3. **Advanced Algorithms**
   - Deep Learning
   - Neural networks
   - New architectures

> **AI Revolution:** These three elements together enabled the explosion of AI in recent years.

---

## 3. History of AI: From Origins to Today

Timeline: **1950 → 1956 → 1980 → 1997 → 2012 → 2016 → 2022**

- Turing Test (1950)
- Birth of AI — Dartmouth Conference (1956)
- Expert Systems (1980)
- Deep Blue beats Kasparov (1997)
- AlexNet — Deep Learning breakthrough (2012)
- AlphaGo beats the Go world champion (2016)
- ChatGPT — LLMs (2022)

Three broad eras: **Beginnings → Renaissance → Explosion**

**Key milestones:**
- **1950-1970:** Optimism and early research
- **1980-2000:** Expert systems and symbolic AI
- **2000-2012:** Statistical Machine Learning
- **2012-today:** Deep Learning and generative AI

### The AI Winters

AI history saw two "winters" of reduced interest and funding:
- **1974-1980** (Winter 1)
- **1987-1993** (Winter 2)

**Why these "winters"?**
- Unfulfilled promises
- Technological limitations
- Lack of data
- Reduced funding

---

## 4. AI Applications in Everyday Life

**Everyday uses:**
- **Voice assistants:** Siri, Alexa, Google Assistant
- **Recommendations:** Netflix, YouTube, Spotify, Amazon, e-commerce
- **Social media:** Personalized feeds, facial recognition, content filters
- **Translation:** Google Translate, DeepL

**Professional applications:**
- **Healthcare:** Medical diagnosis, imaging analysis, drug discovery
- **Finance:** Fraud detection, algorithmic trading, credit scoring
- **Transportation:** Self-driving vehicles, route optimization
- **Agriculture:** Precision farming, crop yield prediction

### AI by Sector: Business Impact

Estimated business impact by sector:
- Healthcare: $3M
- Finance: $2.8M
- Retail: $2.5M
- Transportation: $2.2M
- Manufacturing: $2M

**Opportunities:** Automating repetitive tasks, and more, across every sector.

---

## 5. AI: An Ecosystem of Disciplines

```
Artificial Intelligence
├── Machine Learning
│     └── Deep Learning
├── NLP (Natural Language Processing)
├── Computer Vision
└── Robotics
```

**Relationship between the fields:** Machine Learning sits at the core of modern AI
and powers most of its other branches.

### Machine Learning: The Core of Modern AI

**Definition:** Machine Learning is a branch of AI that lets machines **learn from
data** without being explicitly programmed.

**General idea:** Instead of writing rules by hand, we feed data to the machine so
it learns automatically.

### Classical Programming vs Machine Learning

- **Classical programming:** Data + Rules → Results (the programmer writes the rules)
- **Machine Learning:** Data + Results → Rules (the machine learns the rules)

**Key difference:** In ML, we don't program the rules — we let the algorithm
**discover** them from the data!

### Deep Learning: A Revolution in ML

Deep Learning is a sub-branch of Machine Learning that uses artificial neural
networks with multiple layers to learn complex representations
(Input → Hidden Layer 1 → Hidden Layer 2 → Output).

**Applications:** image recognition, NLP, content generation (ChatGPT, DALL-E).

### Natural Language Processing (NLP)

**Definition:** NLP lets machines understand, interpret, and generate human language.

**Tasks:** machine translation, sentiment analysis, text summarization,
question-answering, text generation, speech recognition.

**Applications:** ChatGPT, Claude, Google Translate, grammar checkers, voice
assistants, chatbots, social media analysis.

**Example:** "I went to the bank to withdraw money" — the machine must understand
that "bank" refers to a financial institution here, not a riverbank.

### Computer Vision: Seeing Like a Human

**Definition:** Computer Vision lets machines extract information from images and videos.

**Main tasks:** image classification, object detection, segmentation, facial
recognition, object tracking, 3D reconstruction.

**Applications:** self-driving vehicles, medical diagnosis (X-rays, MRI),
surveillance and security, Instagram/Snapchat filters, industrial quality control,
precision agriculture.

### The Relationship: AI ⊃ ML ⊃ DL

**Key takeaway:** Deep Learning is a subset of Machine Learning, which is itself a
subset of Artificial Intelligence.

---

## 6. Data Mining vs Machine Learning

| Data Mining | Machine Learning |
|---|---|
| **Goal:** Discover hidden knowledge | **Goal:** Build predictive models |
| **Focus:** Data exploration | **Focus:** Automated learning |
| **Question:** "What does the data tell us?" | **Question:** "How do I predict Y from X?" |
| **Process:** Full KDD pipeline | **Process:** Model training |
| **Uses:** ML techniques + statistics | **Provides:** Algorithms to Data Mining |

**Analogy:**
- **Data Mining = Archaeology:** searching for hidden treasures in the data
- **Machine Learning = Digging tools:** the techniques used to dig

### The Full Process: From Data to Action

Raw Data → **(Exploration)** → Data Mining → **(Learning)** → ML Models →
**(Prediction)** → Decisions

**Integrated view:**
- Data Mining uses Machine Learning techniques
- Machine Learning supplies the algorithms
- Together, they turn data into business value

---

## 7. The 3 Major Types of Learning

- **Supervised:** Labeled data → Prediction (Classification, Regression)
- **Unsupervised:** No labels → Discovery (Clustering, Dimensionality reduction)
- **Reinforcement:** Rewards → Optimal actions (Games, Robotics)

**Choosing the type of learning depends on:**
- Whether labels are available
- The goal (predict vs explore vs optimize)
- The nature of the problem

### Supervised Learning: Learning by Example

**Definition:** Supervised learning uses **labeled data** (examples with known
answers) to learn to make predictions.

**Example — Spam Detection:**
- **Input (X):** Email
- **Output (Y):** Spam or Not
- **Training:** 10,000 labeled emails
- **Result:** A model that classifies automatically

**Main tasks:**
- **Classification:** Predict a category (spam/not spam, cat/dog)
- **Regression:** Predict a numeric value (price, temperature)

### Unsupervised Learning: Discovering Without a Guide

**Definition:** Unsupervised learning works with **unlabeled data** and seeks to
discover hidden structures.

**Example — Customer Segmentation:**
- **Data:** Purchase history
- **No labels:** The groups are not known in advance
- **Algorithm:** K-Means
- **Result:** 4 discovered customer segments

**Main tasks:**
- **Clustering:** Grouping similar objects
- **Dimensionality reduction:** Simplifying the data (PCA)
- **Anomaly detection:** Identifying outliers

---

## 8. Current Challenges in AI

**Technical challenges:**
- **Data quality:** Bias in the data, missing data, noisy data
- **Interpretability:** Black boxes, difficulty explaining decisions
- **Generalization:** Overfitting, performance on unseen cases

**Ethical challenges:**
- **Algorithmic bias:** Discrimination, fairness
- **Privacy:** Data protection, GDPR
- **Social impact:** Employment, misinformation, security

> These challenges must be addressed for the responsible development of AI.

---

## 9. The Future of AI: Emerging Trends

**Emerging technologies:**
1. **Generative AI** :content creation (ChatGPT, DALL-E, Midjourney)
2. **Multimodal AI** : Text + Image + Audio (GPT-4V, Gemini)
3. **Edge AI** : AI on local devices (smartphones, IoT)
4. **AutoML** : automating ML, democratization

**Long-term perspectives:**
- **AGI (General AI):** full human-level intelligence — still far off
- **Explainable AI:** transparency, trust
- **Responsible AI:** ethics by design, regulation
- **Human-AI collaboration:** human augmentation, co-creation

---

## 10. Why Learn AI and ML Today?

**Career opportunities:**
- Strong market demand
- Attractive salaries
- Diverse fields
- Constant innovation

**AI careers:** Data Scientist, ML Engineer, AI Researcher, Data Analyst, AI Product Manager

**Key skills:**
1. Programming (Python)
2. Mathematics — linear algebra, statistics, probability
3. Machine Learning
4. Data Engineering
5. Communication

---

## Summary

**Course recap:**
1. AI: definitions, history, and context
2. The branches of AI: ML, DL, NLP, Vision
3. The relationship between AI, ML, and Data Mining
4. Types of learning: supervised, unsupervised, reinforcement
5. Concrete applications across sectors
6. Technical and ethical challenges
7. The future of AI

> **Key point:** AI isn't magic — it's mathematics + data + computation

---

## Next Step: Machine Learning

Next class, we dive into Machine Learning:
- The complete ML process
- How machines learn
- Basic algorithms
- Model training and evaluation
- First contact with Python code
