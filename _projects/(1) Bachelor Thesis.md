---
name: Bachelor Thesis. Tinder for your Home
tools: [Visual Similarity, Image Segmentation, Deep Learning, Mask R-CNN, CLIP]
image: ../pictures/bachelor_thiesis_header.png
description: This project focused on identifying visual product similarities for webshops with deep learning based models.
---

# Identification of visual product similarities for webshops with deep learning based models.

In today's e-commerce, visual stimuli significantly influence purchasing decisions. Product images are a crucial element in presenting items to potential buyers. This this bachelor thesis, conducted in collaboration with InnoFind GmbH, explores advanced methods for calculating product similarities in online shops using product images. The aim of this research was to enhance the existing recommendation system at InnoFind, making it more robust against disturbances such as background variations, different angles, and image resolutions.

To improve the calculation of product similarities, three different approaches were utilized in this thesis. The first approach used the Structural Similarity Index (SSIM) as a metric for calculating image similarities. The second approach employed an EfficientNet classification model, pre-trained on the ImageNet dataset, to extract embedding vectors from images, which were then used to compute similarities. The third approach replaced EfficientNet with the CLIP model to generate the embedding vectors.

Image segmentation was used in this thesis to improve the accuracy of product similarity recommendations by removing irrelevant background information from product images. By isolating the products from their backgrounds, the system could focus solely on the key visual features of the items, such as shape and texture, which are essential for accurately comparing products. This helped mitigate the effects of varying backgrounds, angles, and image resolutions, ensuring that the product similarity calculations were more consistent and reliable.

Now for a visual example: Imagine a customer is shopping online for a shirt. The first image displays various random shirts from the category, showcasing the range available but without specific similarities.

<p align="center">
  <img src="../pictures/shirt_random.png" alt="random images"/>
</p>

Next, if the costomer now interacts with a product it can be used as an indication of personal preferences in color, fit, and style. The following image shows a green top, which will now be used as a reference product.

<p align="center">
  <img src="../pictures/shirt_reference.png" alt="reference image" width="20%"/>
</p>

The model's prediction can then be used to recommend other visually similar products within the selected category, as demonstrated by the five best matches based on one of the model's results.

<p align="center">
  <img src="../pictures/shirt_clip_seg.png" alt="similar images"/>
</p>

The performance of the applied models was evaluated through a qualitative survey, comparing their results on both segmented and non-segmented images. The deep learning-based models outperformed the SSIM approach in terms of generating more accurate and relevant product recommendations in therms of the percieved visual similarity. The CLIP-based approach in particular performed well with different backgrounds and perspectives. At the end of the project, the knowledge and results gained were successfully used to extend the existing recommender system at InnoFind.
