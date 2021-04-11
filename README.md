# Digital-Watermarking-For-Data-Security

With Internet rapidly developing, illegal copy of digital content poses a serious problem since it can be conveniently reproduced and modified by anyone with minimal technical skills. Most vulnerable to such attacks are the digital images published on websites. Digital Watermarking can be used as a means for discovering unauthorized content usage and also for copyright protection. It is basically a technique of embedding some unique identification mark also called as watermark into the digital image by its owner. After embedding, watermarked data is generated. A good Watermarking technique must have certain qualities such as robustness and imperceptibility. In the proposed method a watermark is hidden using a secret key in digital image which only the owners of that content can extract using the unique watermarking extraction algorithm.

The characteristics of the watermarking system are determined mainly by 2 important factors which are robustness and invisibility. These Watermarking techniques further can be categorized into spatial domain and frequency domain. Although experience has shown that spatial domain techniques need less hardware and have shorter execution time, but they are not much resistant against malicious attacks, while there are many techniques in frequency domains like DCT and DWT which prove to be more robust.

Following 2 images have been used as a part of the project - 

![image](https://github.com/AviKhandelwal/Digital-Watermarking-For-Data-Security/blob/main/Pictures/IITG_White.png)
![image](https://github.com/AviKhandelwal/Digital-Watermarking-For-Data-Security/blob/main/Pictures/IITG.jpg)

This project consists of five parts. First part consists of image pre-processing.
The second and third part revolves around the DCT and PCA application in watermarking. In fourth part, the proposed scheme is applied. Finally in part five, evaluation and performance metrics against various image processing attacks are discussed.

While middle frequency band has it’s advantages but on contrary low frequency band is more resistant against some attacks (low-pass filtering and JPEG compression ) but since hiding watermark in low-frequency DCT coefficients doesn’t really make watermark completely invisible, hence this technique is generally avoided.

In this project, in order to use the low frequency band a new method is proposed based on a combination of the DCT and PCA technique. PCA is dimension reduction technique but more importantly it makes dimensions linearly independent such that when watermark is hidden in these independent dimensions it becomes completely invisible whereas earlier since these dimensions were highly correlated, so hiding watermark in these correlated dimensions would not really make watermark invisible. So with this proposed scheme, the watermark is rendered invisible while the quality of the cover image is maintained.

![image](https://github.com/AviKhandelwal/Digital-Watermarking-For-Data-Security/blob/main/Pictures/table1.png)
![image](https://github.com/AviKhandelwal/Digital-Watermarking-For-Data-Security/blob/main/Pictures/table2.png)


