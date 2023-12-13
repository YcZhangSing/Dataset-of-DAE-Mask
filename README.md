# Dataset-of-DAE-Mask
The self-constructed dataset employed in our publication of *Precision Agriculture* journal titled "*DAE-Mask: a novel deep-learning-based automatic detection model for in-field wheat diseases*", authored by Rui Mao and Yuchen Zhang et al., is hereby revealed.

# Citing DAE-Mask
Please consider citing DAE-MAsk if it proves useful in your work.
```

@article{mao_dae-mask_2023,
	title = {{DAE}-{Mask}: a novel deep-learning-based automatic detection model for in-field wheat diseases},
	issn = {1573-1618},
	url = {https://doi.org/10.1007/s11119-023-10093-x},
	doi = {10.1007/s11119-023-10093-x},
	abstract = {Wheat diseases seriously restrict the safety of wheat production and food quality. For farmers and agriculture technicians, diagnosing the disease with the naked eye is not suitable for modern precision agriculture. Deep learning has shown promise in crop disease diagnosis, but accuracy and speed remain a significant challenge in natural field conditions. In this study, a novel DAE-Mask method based on diversification-augmented features and edge features was proposed for intelligent wheat disease detection. DAE-Mask used Densely Connected Convolutional Networks (DenseNet) for preliminary feature extraction, and a backbone feature extraction network combining Feature Pyramid Network (FPN) and attention mechanism was designed to extract diversification-augmented features. To accelerate DAE-Mask, an Edge Agreement Head module based on Sobel filters was designed to compare edge features during training, which improved the model’s mask generation efficiency. We also built a multi-scene wheat disease dataset, MSWDD2022, containing images of wheat stripe rust, wheat powdery mildew, wheat yellow dwarf, and wheat scab. Our model achieved detection speed of 0.08s/pic. On MSWDD2022, our model with mean average precision (mAP) of 96.02\% outperformed YOLOv5s, YOLOv8x, SSD, EfficientDet, CenterNet, and RefineDet by 7.79, 1.32, 3.54, 4.79, 9.77, and 5.29 percentage points, respectively. On the public dataset PlantDoc, our model with mAP of 57.68\% outperformed YOLOv5s, YOLOv8x, SSD, EfficientDet, CenterNet, and RefineDet by 27.76, 6.48, 14.43, 11.79, 19.40, and 13.40 percentage points, respectively. Finally, the DAE-Mask was deployed on WeChat Mini Program to realize the real-time detection of in-field wheat diseases. The mAP reached 92.78\%, and the average return delay of each image was 1.43s.},
	journal = {Precision Agriculture},
	author = {Mao, Rui and Zhang, Yuchen and Wang, Zexi and Hao, Xingan and Zhu, Tao and Gao, Shengchang and Hu, Xiaoping},
	month = dec,
	year = {2023},
}

```
