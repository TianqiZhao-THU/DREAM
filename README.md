# CVPR 2026 paper ID 41755

[![Paper](https://img.shields.io/badge/Paper-PDF-red.svg)](#) [![Dataset](https://img.shields.io/badge/Dataset-DreamDoc-blue.svg)](https://drive.google.com/drive/folders/1nA5FXrleUefUy9vM40__jypc5TwO6PBx?usp=sharing) 

*(Note: The codebase is currently being updated for full public release. We are progressively uploading the core modules and scripts.)*

---

## 🗂️ DreamDoc Dataset

To thoroughly evaluate document recognition models on complex layouts and diverse stylistic patterns, we introduce **DreamDoc**, a comprehensive bilingual (Chinese-English) dataset constructed specifically for this work.

### ✨ Dataset Highlights
* **Scale & Diversity**: Contains 4,908 high-quality document images (4,800 for training, 108 for testing) sourced from real-world scenarios. The dataset covers 7 distinct categories: listed-company announcements, handwritten notes, slide pages, primary/secondary school textbooks, university textbooks, magazines, and newspapers.
* **Complexity**: Features challenging layouts including single-column, double-column, complex image-text mixed pages, and diverse font styles, which heavily rely on explicit structural context.
* **High-Quality Transcripts**: Annotations are generated via a semi-automatic pipeline. Initial OCR results from Chandra are manually verified and corrected by trained annotators to ensure content integrity, correct reading order, and accurate handling of dense typesetting and complex layouts.

### 📥 Download Links
You can download the full DreamDoc dataset from the following platforms:

* ☁️ **[Google Drive](https://drive.google.com/drive/folders/1nA5FXrleUefUy9vM40__jypc5TwO6PBx?usp=sharing)**

### 📂 Data Structure
After downloading and extracting the dataset, you will find the images organized by category, with all text annotations consolidated in a single JSON file. The directory structure is as follows:

```text
DreamDoc/
├── announce_plus/      # Additional announcements
├── announcement/       # Listed-company announcements
├── jiaocai/            # University textbooks
├── newspaper/          # Newspapers
├── notes/              # Handwritten notes
├── ppt/                # Slide pages
├── times/              # Magazines
├── yiwujiaoyu/         # Primary/secondary school textbooks
├── addnoise.py         # Utility script for adding noise/augmentations
└── label.json          # Ground truth transcripts and metadata for all images

## 🚀 Release Status

To facilitate future research, we are releasing the comprehensive **DreamDoc** dataset and the associated project codebase. The repository is currently being updated to ensure full reproducibility and transparency.
