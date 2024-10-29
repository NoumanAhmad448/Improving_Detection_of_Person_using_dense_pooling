# Improving Detection of Person using dense pooling

<img width="1131" alt="04" src="https://github.com/NoumanAhmad448/Improving_Detection_of_Person_using_dense_pooling/assets/31096570/ca95239b-4bfd-4273-a88e-796b3e7c3b48">


### Abstract 
Lately, the continuous development of deep learning models by many researchers in the area of computer vision has attracted more researchers to further improve the accuracy of these models. FasterRCNN [32] has already provided a state-of-the-art approach to improve the accuracy and detection of 80 different objects given in the COCO dataset. To further improve the performance of person detection we have conducted a different approach which gives the state-of-the-art conclusion. An ROI is a step in FasterRCNN that extract the features from the given image with a fixed size and transfer into for further classification. To enhance the ROI performance, we have conducted an approach that implements dense pooling and converts the image into a 3D model to further transform into UV(ultra Violet) images which makes it easy to extract the right features from the images. To implement our approach we have approached the state-of-the-art COCO datasets and extracted 6982 images that include a person object and our final achievements conclude that using our approach has made significant results in detecting the person object in the given image

> [!TIP]
> **This model was trained on 100 epochs**

> [!TIP]
> Install required dependencies by running the following command

```
pip install -r requirements.txt
```

## Our Paper
> [!TIP]
> https://arxiv.org/abs/2410.20966 


## License
This repository is licensed under the [Apache-2.0 License](LICENSE).
