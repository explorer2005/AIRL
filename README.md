Q1

Run the all cells from start 

<img width="698" height="797" alt="image" src="https://github.com/user-attachments/assets/fff3f1b7-415b-48c6-9076-9d560b36a567" />
<img width="686" height="470" alt="training" src="https://github.com/user-attachments/assets/cc4aa8b8-865b-48bd-aadf-8a78e018fe9e" />

Q2

 Deep Learning Lab — Q2: Text-Driven Image Segmentation with SAM 2

🔍 Overview
Implements text-prompted image segmentation using *GroundingDINO* for object localization and *SAM 2* for precise segmentation.

 🧠 Pipeline
1. Upload image.
2. Enter text prompt (e.g., “a dog”).
3. GroundingDINO generates bounding boxes for text.
4. SAM 2 refines the segmentation mask.
5. Display final overlay.
6. (⭐ Bonus) Propagate segmentation mask across video frames.

 ⚙ How to Run
- Open q2.ipynb in *Google Colab*.
- Runtime → Change runtime type → GPU.
- Run all cells from top to bottom.

 🧾 Limitations
- Heavy model → slower inference on free-tier GPUs.
- May fail for very ambiguous text prompts.
