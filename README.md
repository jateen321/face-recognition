# Face-Recognition
**Code from paper: Composite Sketch+Text Queries for Retrieving Objects with Elusive Names and Complex Interactions**

[project page](https://ykapil897.github.io/face-recognition/) | [Report (report.pdf)

## Requirements
* Use **python >= 3.8.16**. Conda recommended : [https://docs.anaconda.com/anaconda/install/linux/](https://docs.anaconda.com/anaconda/install/linux/)

* Use **pytorch 1.13.1 CUDA 11.6**
* Other requirements from 'requirements.txt' 

**To setup environment**
```
# create new env face-recognition
$ conda create -n face-recognition python=3.8.16
```

```
# activate face-recognition
$ conda activate face-recognition

$ pip install -r requirements.txt

## Preparing dataset
- Download Labelled Faces in the Wild (LFW) dataset from [Kaggle](https://www.kaggle.com/datasets/jessicali9530/lfw-dataset)

Store the downloaded dataset in the `./data/` directory.

## BibTex
<div style="background-color: #f4f4f4; padding: 10px; border-radius: 5px;">
  <pre>
  @InProceedings{cstbir2024aaai,
        author    = {Sapkal, Vivek and Yadav, Kapil and Arsewad, Bagwan and Gavankar, Heramb and Patel, Raj and Suhani and Jateen},
        title     = {Face Recognition on Labelled Faces in the Wild (Dataset)},
        refs      = {https://www.analyticsvidhya.com/blog/2019/09/feature-engineering-images-introduction-hog-feature-descriptor/, 
        http://neuralnetworksanddeeplearning.com/chap2.html, https://medium.com/swlh/local-binary-pattern-algorithm-the-math-behind-it-%EF%B8%8F-edf7b0e1c8b3}
        year      = {2024},
    }      
  </pre>
</div>

## Acknowledgment
We would like to express my sincere gratitude to Anand Mishra, Assitant Professor, for this course project .
