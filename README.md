## DEEP LEARNING - IMAGE CAPTIONING: A COMPARATIVE STUDY
To be Filled 

**Dataset**

[MS COCO Dataset](https://cocodataset.org/#home) is used in this project.

## ATTENTION MODEL + ResNet50 
##### MODEL DESCRIPTION:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 7,000                    | 6,000          | 30            |5                 |      30,000    | 64                |

View Detailed Results     |  View Detailed Epoch Results
:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%2BResNet%20Results/attentionResNetResults.pdf)  |  [Click To View]()

##### MODEL PERFORMANCE SUMMARY
 <p align="center">
  <img src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Images/model2res.png">
</p>

##### EXAMPLE: GOOD PREDICTION RESULT
 <p align="center">
  <img height="400" width="500" src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%2BResNet%20Results/good/good2.png">
</p>

##### EXAMPLE: FAIR PREDICTION RESULT
 <p align="center">
  <img height="225" width="630" src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%2BResNet%20Results/fair/fair2.png">
</p>

##### EXAMPLE: BAD PREDICTION RESULT
 <p align="center">
  <img height="250" width="700" src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%2BResNet%20Results/bad/bad1.png">
</p>


## ATTENTION MODEL + InceptionV3 : 
##### MODEL PERFORMANCE SUMMARY
 <p align="center">
  <img src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Images/model1res.png">
</p>

### MODEL 1: 
##### MODEL DESCRIPTION:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 5,000                    | 6,000          | 10            |5                 |      30,000    | 64                |

##### PREDICTION EXAMPLE
 <p align="center">
  <img  height="250" width="700" src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Images/predictions0.png">
</p>

View Detailed Epoch Results     |  View Folder Containing Image Results| View Report
:-------------------------:|:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%20Results/attention-model0/epochs/attention-model-0.pdf)  |  [Click To View](https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%20Results/attention-model0) |  [Click To View]()

### MODEL 2: 
##### MODEL DESCRIPTION:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 7,000                    | 6,000          | 30            |5                 |    30,000      | 64                |

##### PREDICTION EXAMPLE
 <p align="center">
  <img  height="250" width="700" src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Images/predictions1.png">
</p>

View Detailed Epoch Results     |  View Folder Containing Image Results| View Report
:-------------------------:|:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%20Results/attention-model1/epochs/attention-model-2.pdf)  |  [Click To View](https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%20Results/attention-model1) |  [Click To View]()

### MODEL 3: 
##### MODEL DESCRIPTION:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 7,000                    | 10,000         | 50            |5                 |    50,000      | 64                |

##### PREDICTION EXAMPLE
 <p align="center">
  <img  height="250" width="700" src="https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Images/predictions2.png">
</p>
 
View Detailed Epoch Results     |  View Folder Containing Image Results| View Report
:-------------------------:|:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%20Results/attention-model2/epochs/attention-model-3.pdf)  |  [Click To View](https://github.com/HemanthTejaY/Deep-Learning-Image-Captioning---A-comparitive-study/blob/main/Attention%20Results/attention-model2) |  [Click To View]()

## Authors
1. Hemanth Teja Y (New York University) <hy1713@nyu.edu>
2. Rahul Chinthala (New York University) <rc4080@nyu.edu>


## REFERENCES

[1] Shetty, Rakshith, et al. “Speaking the Same Language: Matching Machine to Human Captions by
Adversarial Training.” ArXiv:1703.10476 [Cs], Nov. 2017. arXiv.org, http://arxiv.org/abs/1703.10476 

[2] Hossain, Md Zakir, et al. “A Comprehensive Survey of Deep Learning for Image Captioning.”
ArXiv:1810.04020 [Cs, Stat], Oct. 2018. arXiv.org,http://arxiv.org/abs/1810.04020}{http://arxiv.org/abs/1810.04020 

[3] Tavakoli, Hamed R., et al. “Paying Attention to Descriptions Generated by Image Captioning
Models.” ArXiv:1704.07434 [Cs], Aug. 2017. arXiv.org, http://arxiv.org/abs/1704.07434}{http://arxiv.org/abs/1704.07434 

[4] Oriol Vinyals, Alexander Toshev, Samy Bengio, and Dumitru Erhan. Show and tell: A neural image caption generator. CoRR, abs/1411.4555, 2014.

[5] Kelvin Xu, Jimmy Ba, Ryan Kiros, Kyunghyun Cho,Aaron C. Courville, Ruslan Salakhutdinov, Richard S.Zemel, and Yoshua Bengio. Show, attend and tell: Neural image caption generation with visual attention. CoRR,abs/1502.03044, 2015. 

[6] Tsung-Yi Lin, Michael Maire, Serge Belongie, James Hays, Pietro Perona, Deva Ramanan, Piotr Dollar, and C. Lawrence ´Zitnick. Microsoft coco: Common objects in context. InDavid Fleet, Tomas Pajdla, Bernt Schiele, and Tinne Tuytelaars, editors, Computer Vision – ECCV 2014, pages 740–755, Cham, 2014. Springer International Publishing. 

[7] Polina Kuznetsova, Vicente Ordonez, Alexander C. Berg, Tamara L. Berg, and Yejin Choi. Collective generation of natural image descriptions. pages 359–368, 2012.

[8] Andrej Karpathy and Li Fei-Fei. Deep visual-semantic alignments for generating image descriptions. IEEE Trans. Pattern Anal. Mach. Intell., 39(4):664–676, Apr. 2017. 

[9] PyTorch. https://ml-cheatsheet.readthedocs.io/en/latest/loss_functions.html
