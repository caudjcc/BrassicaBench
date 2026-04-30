# 🌱 BrassicaBench
**Fine-Grained Matters: A Multi-Scale UAV Benchmark for Similar Vegetable Classification**

## 📢 Announcement
🚀 The **BrassicaBench dataset will be released upon acceptance** of our paper.

---

## 📖 Overview
Fine-grained classification of similar vegetables (e.g., cabbage *Brassica oleracea* vs. Chinese cabbage *Brassica rapa*) is challenging due to:
- subtle inter-class differences  
- strong intra-class variability  
- complex field backgrounds (soil, shadows, weeds)

---

## 🛰️ Dataset
**BrassicaBench** is a **multi-scale, multi-modal UAV benchmark**.

- **Altitudes:** 30 m / 80 m / 120 m / 180 m  
- **Resolution:** 1.0–5.4 cm/pixel  
- **Modalities:** RGB + Multispectral (MS)  
- **Annotations:** pixel-level segmentation  

---

## 🧪 Benchmark
- 8 models evaluated: CNN / Transformer / multimodal fusion  
- Tasks: semantic segmentation, multi-scale analysis, cross-scale generalization  

---

## 📊 Key Findings
- **Transformer > CNN**  
  - +4.70% F1, +8.51% mIoU  
  - Best: Swin-UPerNet (F1: 98.23%, mIoU: 96.54%)

- **Scale effect**  
  - Stable (30–120 m), drop at 180 m  
  - −1.93% F1, −3.65% mIoU  

- **Modality**  
  - RGB performs best  
  - MS provides complementary info  
  - RGB+MS not consistently better  

- **Cross-scale**  
  - Severe drop (−50.87% mIoU avg)  
  - RGBX shows best robustness (−28.47%)  

---

## 🎯 Contribution
- Multi-scale UAV benchmark for fine-grained vegetables  
- Unified evaluation across models, scales, and modalities  
- Insights into resolution, fusion, and generalization  

---

## 📦 Release
📅 Available after paper acceptance:
- RGB + MS images  
- Annotations  
- Splits & evaluation code  

---

## 📄 Citation
```bibtex
@article{BrassicaBench2026,
  title={Fine-Grained Matters: A Multi-Scale UAV Benchmark for Similar Vegetable Classification},
  author={...},
  journal={...},
  year={2026}
}
