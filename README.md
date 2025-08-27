📌 Overview

This project fine-tunes DETR (DEtection TRansformer) on the Fashionpedia Dataset
 to perform object detection and instance segmentation in fashion images. The goal is to detect clothing items and attributes in complex fashion scenes using state-of-the-art Transformer-based models.

Implementation is provided as a single Jupyter Notebook (detr-fine-tuning-on-fashionpedia-dataset-v3-0.ipynb) for easy reproducibility.

🚀 Features

Fine-tunes Facebook’s DETR on a fashion-specific dataset

Supports bounding box detection and segmentation masks

End-to-end training & evaluation pipeline inside one notebook

Visualizes model predictions on sample images

Easily adaptable for custom datasets

🛠️ Technologies Used

Python 3

PyTorch

Hugging Face Transformers

Torchvision

Matplotlib for visualization

COCO-style Fashionpedia Dataset

📂 Project Structure
├── detr-fine-tuning-on-fashionpedia-dataset-v3-0.ipynb   # Main notebook
├── data/                                                 # Fashionpedia dataset
├── outputs/                                              # Model checkpoints & predictions
└── README.md                                             # Documentation

📊 Dataset

Fashionpedia: A large-scale dataset with 48 apparel categories and 92 attributes annotated in a COCO-style format.

Download: Fashionpedia

Place dataset in the data/ folder before running the notebook.

📈 Example Predictions

Input: Fashion image with multiple clothing items
Output: Detected bounding boxes + segmentation masks for apparel categories

(Insert example visualization screenshots here)

🤝 Contributing

Contributions are welcome—whether it’s improving training speed, tweaking augmentation, or experimenting with different Transformer backbones. Fork and PR away.

📜 License

This project is licensed under the MIT License.
