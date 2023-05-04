
# NLP Project
## Team KLM - Team Number 20


> List of Files 

```

├── 20-Interim.pdf
├── 20-Presentation Team KLM.pptx
├── 20-ProjectOutline.pdf
├── 20-Team KLM-Project Report.pdf
├── codes
│   ├── Base_Model_1.ipynb
│   ├── Base_Model_2.ipynb
│   ├── siamese_english.ipynb
│   ├── Spanish_STS_CNN.ipynb
│   ├── STS_CNN.ipynb
│   └── test_sentence_score.py
└── README.md

1 directories, 11 files
``` 


> File name - Description

|      **File Name**     	|                  **Description**                  	|
|:----------------------:	|:-------------------------------------------------:	|
|    Baseline_1.ipynb    	|             Pre-trained model approach            	|
|    BaseModel_2.ipynb   	|                BOW based approach                 	|
|  siamese_english.ipynb 	|         Siamese based using BERT embedding        	|
|  Spanish_STS_CNN.ipynb 	|    CNN based (actual model) for Spanish dataset   	|
|      STS_CNN.ipynb     	|    CNN based (actual model) for English dataset   	|
| test_sentence_score.py 	| Used to predict STS score for 2 input sentences   	|

> Models in Drive
All models are upload in this [Spanish link](https://drive.google.com/file/d/1-EZcFDeQgpqy4HIvoWjd2E63Or1JKdt5/view?usp=sharing), [English Link](https://drive.google.com/file/d/1GhdhekOFUJ3nswXg_rxhzNmuc_0fAfNB/view?usp=sharing)
> Our project [GitHub Link](https://github.com/lakshmanpadigala/Team_KLM_STS)

> Embeddings Link
    English GloVe.6B.300d.txt : [Link](https://drive.google.com/file/d/10X6vI3quS-EZ7mRDyKzgpl59aHEblY01/view?usp=sharing)
    Spanish Word Embeddings : [Link](https://www.kaggle.com/datasets/rtatman/pretrained-word-vectors-for-spanish) 
    
> Running Script
```
python3 test_sentence_score.py
```
Takes input for Language and then promts to Enter sentences.

>eg:
>>**Enter 1 for English 2 for spanish :** 1

>>**Enter first sentence:** There are dogs in the forest.​

>>**Enter second sentence:** The dogs are alone in the forest.​

>>**STS Score Predicted:** 3.7

> Dataset Links for [English](https://drive.google.com/drive/folders/1JxJmeumM-0WZXbtLqJG-hHodt7Wj0bFm?usp=sharing),[Spanish](https://drive.google.com/drive/folders/1h9a52mIEBvADje-dsTnaZA4kqtEGwsL7?usp=sharing).
