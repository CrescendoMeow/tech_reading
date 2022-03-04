# Neural Network Model Pruning and Quantization

## Equalization

The concept of `Equalization` is borrowed from the field of signal processing, i.e. To deal with the signal distortion incurred during transmission through a channel, the signal is proactively processed with the reversal of distortion at the Tx side before sending it out. Similarly, in the field of neural network quantization, we proactively introduce extra operators onto the original weights or activations to amortize the signal-to-quantizationnoise ratio (SQNR) introduced in the stage of quantization.

- [ICML 2019] [Same, Same But Different: Recovering Neural Network Quantization Error Through Weight Factorization](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nagel_Data-Free_Quantization_Through_Weight_Equalization_and_Bias_Correction_ICCV_2019_paper.pdf)
- [ICCV 2019] [Data-Free Quantization Through Weight Equalization and Bias Correction](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nagel_Data-Free_Quantization_Through_Weight_Equalization_and_Bias_Correction_ICCV_2019_paper.pdf)
