# Deep-Learning-Image-Captioning---A-comparitive-study
Deep Learning Course @New York University

## DEEP LEARNING - IMAGE CAPTIONING: A COMPARATIVE STUDY
To be Filled 

## Study 1 : Attention Model + ResNet50  
##### Model Description:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 7,000                    | 6,000          | 30            |5                 |      30,000    | 64                |

View Detailed Results     |  View Detailed Epoch Results
:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%2BResNet%20Results/attentionResNetResults.pdf)  |  [Click To View]()

##### EXAMPLE 1
 <p align="center">
  <img src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/model2res.png">
</p>

##### EXAMPLE: GOOD PREDICTION RESULT
 <p align="center">
  <img height="400" width="500" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%2BResNet%20Results/good/good2.png">
</p>

##### BLEU SCORE, GLEU SCORE and WER (Word Error Rate) metric comparison between sentences:
 <p align="center">
  <img width="1040" height="180" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%2BResNet%20Results/good/print-goodres.png">
</p>

##### EXAMPLE: FAIR PREDICTION RESULT
 <p align="center">
  <img height="225" width="630" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%2BResNet%20Results/fair/fair2.png">
</p>

##### BLEU SCORE, GLEU SCORE and WER (Word Error Rate) metric comparison between sentences:
 <p align="center">
  <img width="950" height="210" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%2BResNet%20Results/fair/fair3-final.png">
</p>

##### EXAMPLE: BAD PREDICTION RESULT
 <p align="center">
  <img height="250" width="700" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%2BResNet%20Results/bad/bad1.png">
</p>

##### BLEU SCORE, GLEU SCORE and WER (Word Error Rate) metric comparison between sentences:
 <p align="center">
  <img width="900" height="180" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%2BResNet%20Results/bad/badRes-final.png">
</p>

##### CUMMULATIVE : BLEU SCORE, GLEU SCORE and WER (Word Error Rate) metric scores for model:

## Study 2: Attention Model + InceptionV3 : 
### MODEL 1: 
##### Model Description:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 5,000                    | 6,000          | 10            |5                 |      30,000    | 64                |

 <p align="center">
  <img src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/model1res.png">
</p>

 ###### BLEU Scores - Bilingual Evaluation Understudy
 
 <p align="center">
  <img width="740" height="180" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/res0.png">
</p>


WER- WORD ERROR RATE       |  PREDICTIONS
:-------------------------:|:-------------------------:
![](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/final0.png)  |  ![](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/predictions0.png)


View Detailed Epoch Results     |  View Folder Containing Image Results
:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%20Results/attention-model0/epochs/attention-model-0.pdf)  |  [Click To View](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/tree/main/Attention%20Results/attention-model0)

### MODEL 2: 
##### Model Description:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 7,000                    | 6,000          | 30            |5                 |    30,000      | 64                |

 ###### BLEU Scores - Bilingual Evaluation Understudy
 
 <p align="center">
  <img width="740" height="180" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/res1.png">
</p>


WER- WORD ERROR RATE       |  PREDICTIONS
:-------------------------:|:-------------------------:
![](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/final1.png)  |  ![](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/predictions1.png)

View Detailed Epoch Results     |  View Folder Containing Image Results
:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%20Results/attention-model1/epochs/attention-model-2.pdf)  |  [Click To View](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/tree/main/Attention%20Results/attention-model1)

### MODEL 3: 
##### Model Description:

| Attention Mechanism | Vocabulary(Unique Words) |Number of Images|Training Epochs|Captions per image|Total Datapoints|Training Batch Size|
|-------------------- | -------------------------|----------------|---------------|------------------|----------------|-------------------|        
|  Bahdanau Attention | 7,000                    | 10,000         | 50            |5                 |    50,000      | 64                |

 ###### BLEU Scores - Bilingual Evaluation Understudy
 
 <p align="center">
  <img width="740" height="180" src="https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/res2.png">
</p>


WER- WORD ERROR RATE       |  PREDICTIONS
:-------------------------:|:-------------------------:
![](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/final2.png)  |  ![](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Images/predictions2.png)

View Detailed Epoch Results     |  View Folder Containing Image Results
:-------------------------:|:-------------------------:
[Click To View](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/blob/main/Attention%20Results/attention-model2/epochs/attention-model-3.pdf)  |  [Click To View](https://github.com/HemanthTejaY/Image-Captioning-A-Comparative-Study/tree/main/Attention%20Results/attention-model2)

## REFERENCES


