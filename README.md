# 📚 Data Mining — Course Notes
**Woraphon Pontri** | Student ID: `663020038-5`

> บันทึกสรุปเนื้อหาวิชา Data Mining แต่ละบทเรียน พร้อมคำอธิบายภาษาไทย

---

## 📋 Table of Contents

| Chapter | Topic |
|---------|-------|
| [Ch.1](#chapter-1-introduction) | Introduction |
| [Ch.2](#chapter-2-getting-to-know-your-data) | Getting to Know Your Data |
| [Ch.3](#chapter-3-data-preprocessing) | Data Preprocessing |
| [Ch.6](#chapter-6-mining-frequent-patterns-association-and-correlations) | Mining Frequent Patterns, Association and Correlations |
| [Ch.8](#chapter-8-classification-basic-concepts) | Classification: Basic Concepts |
| [Ch.9](#chapter-9-classification-advanced-methods) | Classification: Advanced Methods |
| [Ch.10](#chapter-10-cluster-analysis-basic-concepts-and-methods) | Cluster Analysis: Basic Concepts and Methods |

---

## Chapter 1: Introduction
`Slide: 01Intro`

- ✨ **Why Data Mining?** — ทำไมต้องมีการทำเหมืองข้อมูล?
- 🔍 **What Is Data Mining?** — การทำเหมืองข้อมูลคืออะไร?
- 🌐 **A Multi-Dimensional View** — มุมมองหลายมิติของการทำเหมืองข้อมูล
- 💾 **What Kinds of Data Can Be Mined?** — ข้อมูลประเภทใดที่สามารถนำมาทำเหมืองได้?
- 📊 **What Kinds of Patterns Can Be Mined?** — รูปแบบประเภทใดที่สามารถขุดค้นพบได้?
- 🛠️ **What Kinds of Technologies Are Used?** — มีการใช้เทคโนโลยีประเภทใดบ้าง?
- 🎯 **What Kinds of Applications Are Targeted?** — มีการประยุกต์ใช้ในด้านใดบ้าง?
- 🛑 **Major Issues in Data Mining** — ประเด็นสำคัญ/ปัญหาหลักในการทำเหมืองข้อมูล
- 📜 **A Brief History** — ประวัติโดยย่อของการทำเหมืองข้อมูลและสังคมการทำเหมืองข้อมูล

---

## Chapter 2: Getting to Know Your Data
`Slide: 02Data`

- 📊 **Data Objects and Attribute Types** — วัตถุข้อมูลและประเภทของแอตทริบิวต์
- 📈 **Basic Statistical Descriptions of Data** — การอธิบายทางสถิติพื้นฐานของข้อมูล
- 🖼️ **Data Visualization** — การแสดงข้อมูลด้วยภาพ
- 📏 **Measuring Data Similarity and Dissimilarity** — การวัดความคล้ายและความไม่คล้ายของข้อมูล

---

## Chapter 3: Data Preprocessing
`Slide: 03Preprocessing`

- 🛠️ **Data Quality & Overview** — ทำความเข้าใจมิติต่างๆ ของคุณภาพข้อมูล เช่น Accuracy, Completeness, และ Consistency
- 🧹 **Data Cleaning** — การจัดการ Missing values, Noise, Outliers และข้อมูลที่ขัดแย้งกัน
- 🔗 **Data Integration** — รวมข้อมูลจากหลายแหล่ง แก้ปัญหา Entity Identification และลด Redundancy
- 📉 **Data Reduction & Transformation**
  - *Reduction:* ลดขนาดข้อมูลด้วย Numerosity Reduction และ Data Compression
  - *Transformation:* ปรับรูปแบบข้อมูลด้วย Normalization และ Concept Hierarchy Generation
- 📐 **Dimensionality Reduction** — คัดเลือก/สกัดคุณลักษณะสำคัญ เช่น PCA และ Attribute Subset Selection

---

## Chapter 6: Mining Frequent Patterns, Association and Correlations
`Slide: 06FPBasic`

- 💡 **Basic Concepts** — Frequent Patterns, Association Rules, ค่า Support และ Confidence รวมถึง Closed Patterns และ Max-Patterns
- ⛏️ **Efficient Pattern Mining Methods**
  - *Apriori Algorithm:* ใช้หลัก Apriori Property เพื่อ Pruning
  - *FP-growth Algorithm:* ขุดค้นแพทเทิร์นโดยใช้โครงสร้าง FP-tree ไม่สร้าง Candidate
  - *Vertical Data Format (Eclat):* ขุดค้นในรูปแบบแนวตั้งด้วย Transaction ID lists
- 📉 **Pattern Evaluation** — วิเคราะห์ความน่าสนใจของกฎด้วย Lift และ Chi-square

---

## Chapter 8: Classification — Basic Concepts
`Slide: 08ClassBasic`

- 🧩 **Basic Concepts** — ความหมายของ Classification, Supervised vs. Unsupervised Learning
- 🌳 **Decision Tree Induction** — อัลกอริทึม ID3, C4.5, CART; ค่า Information Gain, Gain Ratio, Gini Index; Tree Pruning
- ⚖️ **Bayes Classification Methods** — Bayes' Theorem และ Naïve Bayes Classifier (Class Conditional Independence)
- 📈 **Linear Classifier** — Linear Discriminant Analysis (LDA)
- 🎯 **Model Evaluation and Selection** — Accuracy, Precision, Recall, F-measure, Cross-validation, ROC Curve
- 🚀 **Ensemble Methods** — Bagging, Boosting, Random Forest

---

## Chapter 9: Classification — Advanced Methods
`Slide: 09ClassAdvanced`

- 🕸️ **Bayesian Belief Networks** — ต่อยอดจาก Naïve Bayes ด้วยโครงสร้าง DAG (Directed Acyclic Graph)
- 🛡️ **Support Vector Machines (SVM)** — หา Hyperplane ที่มี Margin มากที่สุด, Kernel Trick สำหรับข้อมูลมิติสูง
- 🧠 **Neural Networks and Deep Learning** — Multilayer Feed-Forward Networks, Backpropagation, Deep Learning
- 🔍 **Pattern-Based Classification** — ใช้ Frequent Patterns สร้างกฎจำแนกประเภท (CBA, CMAR)
- 🐢 **Lazy Learners / k-NN** — เปรียบเทียบความคล้ายคลึงกับเพื่อนบ้าน k ลำดับ โดยไม่สร้างโมเดลล่วงหน้า
- 🛠️ **Other Methods** — Genetic Algorithms, Rough Set Approach, Fuzzy Set Approach

---

## Chapter 10: Cluster Analysis — Basic Concepts and Methods
`Slide: 10ClusBasic`

- 🧩 **Introduction** — Cluster คืออะไร, Clustering (Unsupervised) vs. Classification (Supervised)
- 📍 **Partitioning Methods** — k-means (ค่าเฉลี่ย) และ k-medoids (จุดข้อมูลจริงเป็นตัวแทน)
- 🌳 **Hierarchical Methods** — Dendrogram แบบ Agglomerative (ล่างขึ้นบน) และ Divisive (บนลงล่าง)
- 🌊 **Density-Based & Grid-Based Methods**
  - *Density-Based:* DBSCAN สำหรับกลุ่มรูปร่างอิสระ
  - *Grid-Based:* แบ่งพื้นที่เป็น Grid เพื่อความเร็วในการประมวลผล
- 📊 **Evaluation of Clustering** — วัดคุณภาพแบบ External (เทียบข้อมูลภายนอก) และ Internal/Cohesion

---

## 📖 Reference

> **Data Mining: Concepts and Techniques**
> https://drive.google.com/drive/folders/1SINn1m3GJRu4v6Ij3bp_1plbQMm-2IKf?usp=sharing
