# Image Categorizer: Deep Learning for Product Classification

## Overview
This project is a deep learning-based image classifier designed to categorize products based on images from the Torob e-commerce platform. It uses transfer learning with MobileNetV2 to classify products into 11 categories, such as men's jackets, hoodies, watches, and luggage. The model achieves high accuracy (target: >83%) on a dataset of real-world product images.

This serves as a portfolio piece demonstrating skills in computer vision, TensorFlow/Keras, data preprocessing, and model fine-tuning.

### Dataset
- **Source**: Provided by Torob (Iranian e-commerce search engine). Download from [this link](https://drive.google.com/file/d/1hZK1rshl4dJVEPkUPykU5cZs_ANyTWp-/view?usp=sharing) (~270 MB).
- **Structure**:
  - `train/`: Labeled images in subfolders (0 to 10).
  - `test/`: Unlabeled test images.
- **Categories**:
  | Category ID | Description |
  |-------------|-------------|
  | 0 | Men's Jackets, Raincoats, and Coats |
  | 1 | Men's Sweatshirts and Hoodies |
  | 2 | Analog and Digital Wristwatches |
  | 3 | Wall, Desk, and Decorative Clocks |
  | 4 | Accessories for Regular and Smart Watches |
  | 5 | Youth and Teen Sweatshirts and Hoodies |
  | 6 | Youth and Teen Jackets and Coats |
  | 7 | Men's Sports Sweatshirts |
  | 8 | Men's Sports Sweatshirts and Pants Sets |
  | 9 | Shopping Bags and Trolleys |
  | 10 | Suitcases and Travel Bags |

### Features
- Data augmentation for robustness.
- Class weighting to handle imbalanced data.
- Transfer learning with fine-tuning.
- Evaluation with accuracy, confusion matrix, and classification report.


"This project's dataset is provided by Torob, including a portion of the real data from this website. As you know, Torob is a shopping search engine that aggregates product information from various online stores and displays it on a single page. This allows users to easily find their desired product and compare different sellers. One of the most critical technical requirements for such a platform is the automatic detection of product information, as manual curation of this massive volume of data and extraction of information from them would be extremely time-consuming and costly. Product categorization can arguably be considered the most important information for a product, as it plays a crucial role in its searchability. Therefore, in this project, we assist Torob by designing a deep learning model that can classify products based on their images."
