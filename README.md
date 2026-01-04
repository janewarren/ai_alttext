# Identity-Based Description Bias in AI-Generated Alternative Text - Code Repository
This repository contains code and for the paper "Vision Language Models See Color: Racial and Gender Bias in AI-Generated Alternative Text," submitted for review to the Jan. 2026 ARR Cycle. It can be run entirely in Google Colab, or an IDE of your choice. 

```generate_images_alt_text.ipynb``` first generates 1200 images with GPT-image-1, and then calls GPT-4.1, Claude-Sonnet-4.5, and Gemini-2.5-Pro to generate an alt text for each image. This file was used to create our dataset, which is available on [Zenodo](https://zenodo.org/doi/10.5281/zenodo.17969599). 

```analyze_alt_text_pandas.ipynb``` performs the first part of the alt text analysis using Pandas, shown in section 4.1 of the paper.

```analyze_alt_text_pt2.ipynb``` performs the second part of the alt text analysis, shown in the remainder of the Results section of the paper. This includes embedding analysis, VADER sentiment analysis, token frequency imbalance, and multivariate energy distance. 

The authors acknowledge the use of generative AI tools to assist in writing this code and take full credit for the finished product.
