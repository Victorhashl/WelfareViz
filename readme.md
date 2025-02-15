# **WelfareViz: Automating Visual Representation of Welfare Schemes**

## 📌 Background and Motivation

In a diverse country like ours, **language barriers** can prevent people from accessing essential information about **welfare schemes** that could significantly improve their lives. **Visual representations** (such as posters) can transcend these barriers and communicate complex information effectively.

This project aims to **leverage NLP techniques** to process welfare scheme documents, create **descriptive image prompts**, and evaluate **AI-generated images** to ensure accessibility for all.

## 🎯 Objectives

- **Information Extraction** – Extract key details from welfare scheme documents to generate concise and meaningful write-ups.
- **Image Prompt Generation** – Convert extracted information into detailed text prompts suitable for **text-to-image generation models**.
- **Entity Consistency** – Ensure that people, objects, and locations remain consistent across all generated images for a given welfare scheme.
- **Image Generation and Evaluation** – Generate images using AI models and assess their **coherence, relevance, and accuracy**.
- **Automation Pipeline** – Develop a **Python-based workflow** that integrates all the above steps seamlessly.

## 🏆 Levels of Implementation

### **Level 1: Basic Implementation**

- Develop the **core pipeline** for text extraction, prompt generation, and image evaluation.
- **Fine-tune T5** on **BillSum** and **DailyMail** datasets to improve summarization for better prompt generation.

### **Level 2: Innovation Task**

- Explore and integrate **state-of-the-art NLP techniques** to enhance efficiency, accuracy, and robustness of the solution.
- Conduct independent research to incorporate **advanced NLP methods** into the pipeline.
- Optimize text-to-image generation using insights from **"[Optimizing Prompts for Text-to-Image Generation](https://arxiv.org/pdf/2212.09611)"** paper.

## 🛠 Tech Stack

- **Natural Language Processing (NLP)** – Information extraction & prompt generation
- **Text-to-Image Models** – Stable Diffusion, Midjourney (or any applicable model)
- **Python & Machine Learning** – Automation of the pipeline
- **Evaluation Metrics** – Consistency, coherence, and relevance checks

## 📌 Workflow

1️⃣ **Preprocessing** – Extract key data from welfare scheme documents  
2️⃣ **Prompt Generation** – Convert extracted data into structured text prompts  
3️⃣ **Image Generation** – Use AI-based **text-to-image** models to create posters  
4️⃣ **Evaluation** – Assess the images based on coherence and information accuracy
