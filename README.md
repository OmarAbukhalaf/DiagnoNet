# DiagnoNet
An intelligent, multimodal AI-powered medical assistant designed to support clinicians and researchers by processing medical texts and images for diagnostic insights and classification. This tool combines state-of-the-art NLP and computer vision models to enhance decision-making in healthcare.

📌 Features
🩺 Multimodal Input: Processes both medical images (e.g., CT, MRI) and clinical notes/reports.

🧬 Disease Classification: Predicts diseases using deep learning models trained on annotated medical datasets.

🖼️ Image Encoder: Utilizes DenseNet121 to extract features from TAC and MRI scans.

📄 Text Encoder: Uses BiomedBERT to process and understand clinical text.

⚗️ Late Fusion: Combines predictions at the probability level for optimal performance.

🚀 Augmentation Pipeline: Includes synonym replacement, back-translation, and sentence reordering to improve model robustness.

🔬 Explainability (Optional): Visualizes attention maps or highlights key text features for interpretability.

🧪 Tech Stack
Type	Technology
Language	Python 3.10
Framework	PyTorch, HuggingFace Transformers
Models	DenseNet121, BiomedBERT
Augmentation	NLTK, TextBlob, Google Translate API
Utilities	NumPy, Pandas, OpenCV, Scikit-learn
