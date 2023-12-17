# Endoscopy_UC_CD_Classification

## Overview
This project develops a Convolutional Neural Network (CNN) to classify endoscopic images, focusing on distinguishing between esophagitis (a manifestation of Crohn's disease) and ulcerative colitis. Though similar in symptoms, these conditions have different treatment approaches. Accurate and swift classification can aid significantly in diagnosis and treatment.

## Purpose
The project aims to:
- Utilize CNNs to differentiate esophagitis (a form of Crohn's disease) from ulcerative colitis in endoscopic images.
- Enhance diagnostic accuracy for medical professionals, reducing the complexity of identifying these conditions.
- Advance the application of machine learning in medical image analysis, particularly in gastroenterology.

## Dataset
The dataset for training the model is sourced from the Kvasir Dataset, available at Simula Research Laboratory. This dataset includes a diverse collection of endoscopic images and is widely used for benchmarking in the medical image analysis field.

## Prerequisites
**Required libraries:**
- cv2
- imghdr
- matplotlib
- numpy
- os
- tensorflow


## Conclusion
This project demonstrates CNNs' capabilities in distinguishing between closely related gastrointestinal diseases, offering a valuable tool for medical diagnostics and a foundation for further research in medical image analysis.

## Citation:
@inproceedings{Pogorelov:2017:KMI:3083187.3083212,
  title = {KVASIR: A Multi-Class Image Dataset for Computer Aided Gastrointestinal Disease Detection},
  author = {
     Pogorelov, Konstantin and Randel, Kristin Ranheim and Griwodz, Carsten and
     Eskeland, Sigrun Losada and de Lange, Thomas and Johansen, Dag and
     Spampinato, Concetto and Dang-Nguyen, Duc-Tien and Lux, Mathias and
     Schmidt, Peter Thelin and Riegler, Michael and Halvorsen, P{\aa}l
  },
  booktitle = {Proceedings of the 8th ACM on Multimedia Systems Conference},
  series = {MMSys'17},
  year = {2017},
  isbn = {978-1-4503-5002-0},
  location = {Taipei, Taiwan},
  pages = {164--169},
  numpages = {6},
  doi = {10.1145/3083187.3083212},
  acmid = {3083212},
  publisher = {ACM},
  address = {New York, NY, USA},
}

## Terms of use
The Kvasir dataset is restricted for research and educational purposes only. Using the Kvasir dataset for other purposes, including commercial purposes, is forbidden without prior written permission. In all documents and papers that use or refer to the Kvasir dataset or report experimental results based on the Kvasir dataset, a reference to the dataset paper has to be included.
