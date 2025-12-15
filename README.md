<h1 align="center">
BarSight: Barcode & QR Code Detection and Decoding App
</h1>

<p align="center">
A computer vision project for robust barcode and QR code detection and decoding under challenging real-world conditions
</p>

---

## Project Background

Barcodes and QR codes are widely used in logistics, retail products, and tracking systems. However, many existing scanning systems struggle to accurately read codes that are **damaged, rotated, blurred, or captured under poor lighting conditions**.

**BarSight** was developed to address this challenge by applying **computer vision and deep learning techniques** to automatically detect the location of barcodes and QR codes in images and reliably decode their contents, even in non-ideal scenarios.

---

## Objectives & Target Users

### Objectives

This project aims to build an **end-to-end pipeline** that:

* Detects barcode and QR code locations in images using **YOLOv8**
* Decodes barcode and QR code content using **pyzbar** and **ZXing**
* Stores decoded results in **CSV format** for further analysis
* Visualizes detection results with **bounding boxes and labels**

### Target Users

* **Logistics and operations teams** requiring robust automated scanning systems
* **Developers and data practitioners** interested in building barcode/QR scanning solutions

---

## Dataset

The dataset consists of a combined collection of realistic barcode and QR code images with variations in:

* Rotation angles
* Lighting conditions
* Image quality (blur, partial damage, noise)

**Dataset size**: ~3,000 images
**Directory structure**: `images/labels/train-val-test`

---

## Tools & Technologies

| No | Stack                 |
| -- | --------------------- |
| 1  | Python                |
| 2  | OpenCV, Matplotlib    |
| 3  | Ultralytics YOLOv8    |
| 4  | pyzbar, ZXing CLI     |
| 5  | Pandas                |
| 6  | Google Colab, VS Code |
| 7  | Hugging Face Spaces   |

---

## Output & Results

* The **YOLOv8n** model successfully detects barcode and QR code regions with strong performance
* Detection results are visualized using bounding boxes and labels
* Barcode and QR contents can be decoded even when images are:

  * Rotated
  * Low-light
  * Partially damaged

---

## My Role & Contribution (Data Analyst)

> **Project Context**: BarSight is a *team-based project*. This repository is published as a **personal portfolio** to highlight my individual contributions as a **Data Analyst**.

In this project, I worked as a **Data Analyst**, focusing on data analysis, result evaluation, and translating technical outputs into actionable insights.

My key contributions include:

* Conducting **exploratory data analysis (EDA)** to understand data distribution, image quality, and potential data issues
* Supporting **data preparation and label validation** to ensure data quality for model training
* Analyzing model outputs (bounding boxes and decoding results) across multiple image conditions
* Structuring and exporting **decoded barcode results into CSV format** for analytical and business use
* Communicating **technical findings in a clear, non-technical manner** for stakeholders

This role highlights my ability to bridge **computer vision outputs** with **data analysis and business-oriented decision making**.

---

## Deployment

The application is deployed using **Hugging Face Spaces** and can be accessed via the link below:

[![Hugging Face Spaces](https://img.shields.io/badge/Click%20Here-FFD43B?style=for-the-badge\&logo=huggingface\&logoColor=black)](https://huggingface.co/spaces/frsszn/BarSight)

---

## Author

**Rajib Kurniawan**
Role: Data Analyst
GitHub: [https://github.com/RajibKurniawan](https://github.com/RajibKurniawan)

---

<p align="center">
<i>Turning computer vision outputs into structured data and actionable insights.</i>
</p>
