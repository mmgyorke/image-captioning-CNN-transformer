## Image Caption Generation

Image captioning is a very useful task seen in many applications today. It sits on the intersection of computer vision and natural language processing, using both linguistic and visual kernels. Its purpose is to generate a textual description of a given image. Its applications include usage in virtual assistants, recommendations in editing applications, social media, etc.

This particular model uses a CNN and a transformer, with multi-head attention. The visual attention mechanism is widely used in current state-of-the-art image captioning models and allows the models to selectively concentrate on objects of interest. It computes the spatial relationship between tokens, as the sequence passes through the encoder stack. This stack ranks the images and sentences, while the decoder stack generates the descriptions for the images from scratch.

The model is trained on the Flickr8k dataset, which consists of over 8,000 images, each paired with five different captions. All models were trained and tested using available GPUs from Google Colab. Open source code was used from keras.io documentation. To reach optimal performance, the model was tuned to explore alternate configurations.


# References:

1. H. Aldabbas, M. Asad, M. H. Ryalat, K. R. Malik, and M. Z. Qureshi, "Data Augmentation to Stabilize Image Caption Generation Models in Deep Learning," in *International Journal of Advanced Computer Science and Applications (IJACSA)* vol. 10, no. 10, 2019.

2. K. Papineni, S. Roukos, T. Ward, and W. J. Zhu, "Bleu: a method for automatic evaluation of machine translation," in *Proceedings of the 40th annual meeting on association for computational linguistics.* Association for Computational Linguistics, 2002, Conference Proceedings, pp.311-318.

3. K. Simonyan and A. Zisserman, “Very deep convolutional networks for large-scale image recognition,” *arXiv: 1409.1556,* 2014.

4. A. Karpathy and L. Fei-Fei, “Deep visual-semantic alignments for generating image descriptions,” in *Proceedings of the IEEE conference on computer vision and pattern recognition*, 2015, Conference Proceed- ings, pp. 3128–3137.

5. A. Nagarajan, A. Raghunathan, S. Sen, and J. R. Stevens, "Optimizing Transformers with Approximate Computing for Faster, Smaller, and more Accurate NLP Models," *arXiv: 2010.03688,* 2020.

6. V. Atliha and D. Šešok. "Text Augmentation Using BERT for Image Captioning" *Applied Sciences* 10, no. 17: 5978, 2020. https://doi.org/10.3390/app10175978

7. Doshi, Ketan (2021, April 23). Image Captions with Deep Learning: State-of-the-Art Architectures. *towardsdatascience.* https://towardsdatascience.com/image-captions-with-deep-learning-state-of-the-art-architectures-3290573712db

8. Doshi, Ketan (2021, January 16). Transformers Explained Visually (Part 3): Multi-head Attention, deep dive. *towardsdatascience.* https://towardsdatascience.com/transformers-explained-visually-part-3-multi-head-attention-deep-dive-1c1ff1024853
