Astrocytoma XAI Analyzer 🧠

This is a deep learning-based medical image segmentation project to detect and highlight astrocytoma tumors in brain MRI images. The tool uses a U-Net model for segmentation and LIME for visual explanation of the prediction.

🔍 Features

MRI brain tumor segmentation using U-Net
LIME-based explanation for interpretability
Gradio-powered user interface with styled background
Easy upload, analyze, and visualize pipeline 🚀 Usage
Upload an MRI scan (PNG or JPG)
Click “Analyze”
View segmented output and LIME explanation side-by-side
🧠 Model Info

Model: U-Net trained on brain tumor dataset
Input: RGB image resized to 128x128
Output: Binary mask (tumor vs. non-tumor)
📦 Requirements gradio torch torchvision Pillow lime scikit-image numpy matplotlib
