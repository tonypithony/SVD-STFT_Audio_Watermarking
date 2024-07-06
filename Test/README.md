![](https://raw.githubusercontent.com/tonypithony/SVD-STFT_Audio_Watermarking/master/Test/melspec.PNG)
 
When the DFT is computed for purely real input, the output is Hermitian-symmetric, 
i.e. the negative frequency terms are just the complex conjugates of the corresponding
positive-frequency terms, and the negative-frequency terms are therefore redundant. 
This function does not compute the negative frequency terms, and the length of the transformed axis of the output is therefore n//2 + 1.

![](https://raw.githubusercontent.com/tonypithony/SVD-STFT_Audio_Watermarking/master/Test/original.jpg)
![](https://raw.githubusercontent.com/tonypithony/SVD-STFT_Audio_Watermarking/master/Test/audiowm.PNG)
