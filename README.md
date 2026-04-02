# DTI_Lite
DTI Lite is a foundational multimodal outfit recommendation system leveraging CLIP-based image-text embeddings to generate clothing combinations from user-provided apparel items. The project explores early-stage fashion compatibility modeling with plans for advanced visual and contextual coherence.
# 👕 DTI Lite

DTI Lite is an experimental multimodal machine learning project that explores outfit recommendation using image-text similarity.

The system uses CLIP (Contrastive Language–Image Pretraining) to understand relationships between clothing items and textual descriptions, enabling basic outfit combination generation from user-provided inputs.

---

## 🚀 Project Overview

This project is an early-stage prototype focused on:

- Understanding clothing items using image embeddings
- Matching them with textual outfit descriptions
- Generating simple outfit combinations from a given set of clothing items

Currently, the system works by:
1. Taking multiple clothing images as input
2. Encoding them using CLIP
3. Comparing them with predefined outfit descriptions
4. Returning the most relevant combination

---

## 🧠 Tech Stack

- Python
- PyTorch
- CUDA (GPU acceleration)
- OpenAI CLIP (Transformers-based model)
- NumPy / PIL

---

## ⚙️ How It Works

1. **Input**  
   A set of clothing item images (e.g., hoodie, blazer, pants)

2. **Feature Extraction**  
   Each image is converted into an embedding using CLIP

3. **Text Matching**  
   Predefined outfit descriptions are also embedded

4. **Similarity Calculation**  
   Cosine similarity is used to match clothing items with outfit descriptions

5. **Output**  
   The system suggests a combination based on highest similarity

---

## 📌 Current Limitations

This is a basic prototype and has several limitations:

- Outfit combinations are selected from a predefined list
- No real understanding of:
  - Color harmony
  - Fit or body type
  - Seasonal/contextual relevance
- No dynamic generation of outfits (only matching)

---

## 🔮 Future Improvements

The goal is to evolve this into a more intelligent recommendation system by incorporating:

- 🎨 Color compatibility analysis
- 👗 Shape and silhouette consistency
- 🌦 Context awareness (weather, occasion, time)
- 🧩 Dynamic outfit generation instead of static lists
- 📊 Learning-based ranking instead of fixed similarity scoring
- 🧠 Fine-tuning CLIP or using custom-trained models on fashion datasets
- 🛍 Integration with larger and diverse clothing datasets

---

## 📂 Project Structure
