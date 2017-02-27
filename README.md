Tensorflow implementation of [Pixel Recursive Super Resolution.](https://arxiv.org/pdf/1702.00783.pdf)

    We present a pixel recursive super resolution model that
    synthesizes realistic details into images while enhancing
    their resolution. A low resolution image may correspond
    to multiple plausible high resolution images, thus modeling
    the super resolution process with a pixel independent conditional
    model often results in averaging different details–
    hence blurry edges. By contrast, our model is able to represent
    a multimodal conditional distribution by properly modeling
    the statistical dependencies among the high resolution
    image pixels, conditioned on a low resolution input. We
    employ a PixelCNN architecture to define a strong prior
    over natural images and jointly optimize this prior with a
    deep conditioning convolutional network. Human evaluations
    indicate that samples from our proposed model look
    more photo realistic than a strong L2 regression baseline.