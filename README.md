# Sustainable-Sentiment-Analysis-of-Social-Media-Data-using-Lightweight-DL-Models-in-R

#  EcoSNN-Lite  
### *Energy-Efficient Sentiment Analysis using Hybrid Spiking and Gated Neural Networks*  

---

##  Overview

**EcoSNN-Lite** is an **energy-efficient sentiment analysis model** that fuses **Spiking Neural Networks (SNNs)** and **Gated Recurrent Units (GRUs)** to deliver high accuracy with low computational cost.  

Inspired by biological neurons, EcoSNN-Lite introduces **spike-based sparse activation** and **learned gating mechanisms** to perform efficient text understanding — making it ideal for **green AI** and **edge NLP systems**.  

>  *This project demonstrates how neuroscience-inspired deep learning can drive sustainability in artificial intelligence.*

---

##  Key Features

-  **Energy-Efficient Neural Design:** Combines spiking activation with GRUs for low-power computation.  
-  **Gated Attention Mechanism:** Focuses on important tokens while suppressing noise.  
-  **Multilingual & Unicode-Safe:** Handles diverse languages (English, Hindi, Tamil, Burmese, etc.) via `stringi`.  
-  **Full Visualization Suite:** Confusion matrix, precision/recall/F1 bar charts, word clouds, and efficiency plots.  
-  **Eco Metric (CES):** Introduces a *Computational Efficiency Score* balancing accuracy vs. time.  

---

##  Model Architecture
Input → Embedding → Gating Module → Spike Encoder
→ GRU Layer → Attention Pooling → Dense → Softmax (3-class output)

