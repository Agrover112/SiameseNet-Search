# SiameseNet-Search
Search can be performed in various ways and using various architectures. In the following repository embeddings are created by using  an non-cnn **base embedding model** which is tuned using a *Siamese Neural Net*  with *Triplet Loss* inspired from [Facenet](https://arxiv.org/pdf/1503.03832.pdf) paper from Google , on **10K MNIST digits** images from train-set.The trained model is used to create embeddings for *entire* train-set and then Indexed using [Approx Nearest Neighbours](https://github.com/spotify/annoy) being faster than K-nn.
More like a prototype.

### Embedding Space Visualized
PCA used for visualizing the embedding space of **10K images** of different classes.
![](https://github.com/Agrover112/SiameseNet-Search/blob/main/download.png)
## References
- https://arxiv.org/pdf/1503.03832.pdf
- http://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf
- http://yann.lecun.com/exdb/mnist/
- https://github.com/spotify/annoy
- https://github.com/PotatoSpudowski/S.I.D.E
