# ConvRS
## Convolutional Reconstruction-to-Sequence for Video Captioning

![Task](https://github.com/AmingWu/ConvRS/blob/master/pic/LSTM%20decoder.png "Illustration of LSTM Decoder")
For video captioning, the commonly used method is LSTM decoder with an attention mechanism. Although LSTM owns a memory cell to memorize history information, it is still limited to several time steps. The reason is long-term information is gradually diluted at each time step. To alleviate this problem, we propose a convolutional reconstruction-to-sequence model for video captioning.
