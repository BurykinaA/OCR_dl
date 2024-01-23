# OCR-NN


## General Description
License plate recognition systems consist of two modules: detection and Optical Character Recognition (OCR). The detector identifies the rectangle with the license plate in the image, while OCR converts it into text. Let's assume that the detector is already implemented. As part of the project, an OCR model for license plates has been implemented and trained.

**Input Example:** 
![License Plate](https://algocode.ru/files/course_dlfall22/number.png)

**Output Example:** 皖AD16688

## Solution Architecture
The proposed solution involves implementing a model consisting of two blocks: Fully-convolutional CNN (FCNN) and Bi-LSTM. It is recommended to use Connectionist Temporal Classification Loss for the output.


Architecture:

![Architecture](https://algocode.ru/files/course_dlfall22/architecture.png)

## Dataset
The [CCPD2019](https://github.com/detectRecog/CCPD) dataset was utilized. The test set includes images from CCPD-weather. The prepared dataset can be downloaded [here](https://disk.yandex.ru/d/adjYzzNayB1pag).

