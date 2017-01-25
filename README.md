# Marco Open data set
Microsoft is trying to help create machines that can have conversations by releasing a new set of data for free.

The data, called the Microsoft Machine Reading Comprehension dataset (MS MARCO) is a bundle of 100,000 English queries along with corresponding answers. It's supposed to help people build artificial intelligence systems that can understand human written language.

The queries in MS MARCO are based on anonymized questions that were submitted to Microsoft’s Bing search engine and Cortana virtual assistant. The answers are based on information found online, written by humans and checked for accuracy.

The data set can be downloaded from the [link](http://www.msmarco.org/dataset.aspx).

# HTC-Vive Demo Project


# Python Note-book Description


### Dealing without Imbalance class: ###
**Scoring history:**

|Model| Bag of Words | tf-idf |
|-----|-------------|-------|
|Gradient BM|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_gbm_scr.PNG>|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/tfidf_gbm_scr.PNG >|
|Deep Learning|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_dl_scr.PNG>|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/tfidf_dl_scr.PNG>|

**ROC:**

|Model| Bag of Words | tf-idf | 
|-----|-------------|-------|
|Gradient BM|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_gbm_roc.PNG>|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/tfidf_gbm_roc.PNG>|
|Deep Learning|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_dl_roc.PNG>|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/tfidf_dl_roc.PNG>|

**Aera Under the Curve:**

|Model| Bag of Words | tf-idf | 
|-----|-------------|-------|
|Gradient BM|*Training AUC:* 0.868, *Validation AUC:*  0.518|*Training AUC:* 0.987, *Validation AUC:*  0.526|
|Deep Learning|*Training AUC:* 0.927, *Validation AUC:*  0.556|*Training AUC:* 0.658, *Validation AUC:*  0.536|

### Dealing with Imbalance class: ###
**Scoring history:**

|Model| Bag of Words | tf-idf |
|-----|-------------|-------|
|Gradient BM|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_gbm_scr_imb.PNG>|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/tfidf_gbm_scr_imb.PNG>|
|Deep Learning|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_dl_scr_img.PNG>|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/tfidf_dl_scr_imb.PNG>|

**ROC:**

|Model| Bag of Words | tf-idf | 
|-----|-------------|-------|
|Gradient BM|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_gbm_roc_imb.PNG>|<img src= https://raw.githubusercontent.com/hamzafar/image_repo/master/marco/bg_dl_roc_img.PNG>|
|Deep Learning|<img src= >|<img src= >|

**Aera Under the Curve:**

|Model| Bag of Words | tf-idf | 
|-----|-------------|-------|
|Gradient BM|*Training AUC:* 0.954, *Validation AUC:*  0.742|*Training AUC:* 0.998, *Validation AUC:*  0.772|
|Deep Learning|*Training AUC:* 0.998, *Validation AUC:*  0.802|*Training AUC:* 0.763, *Validation AUC:*  0.614|

