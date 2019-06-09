#### This work was accepted to publish to International Conference on Pattern Recognition and Artificial Intelligence 2018 (ICPRAI 2018) http://www.icprai2018.com/

# Facial Expression Recognition Using a Multi-level Convolutional Neural Network
Hai-Duong Nguyen*, Soonja Yeom**, Il-Seok Oh***, Kyoung-Min Kim****, Soo-Hyung Kim*  
(\*) School of Electronics and Computer Engineering, Chonnam National University, South Korea  
(\*\*) School of Engineering and ICT, University of Tasmania, Australia  
(\*\*\*) Department of Computer Science and Engineering, Chonbuk National University, South Korea  
(\*\*\*\*) Department of Electrical and Semiconductor Engineering, Chonnam National University, South Korea  
  
      @inproceedings{duongicprai18,
        author        = "Nguyen, Hai-Duong and Yeom, Soonja and Oh, Il-Seok and Kim, Kyoung-Min and Kim, Soo-Hyung",
        title         = "Facial Expression Recognition Using a Multi-level Convolutional Neural Network",
        booktitle     = "Proceedings of International Conference on Pattern Recognition and Artificial Intelligence (ICPRAI)",
        year          = "2018",
        pages         = "217--221"
      }
      
and
        
      @article{doi:10.1142/S0218001419400159,
        author = {Nguyen, Hai-Duong and Yeom, Soonja and Lee, Guee-Sang and Yang, Hyung-Jeong and Na, In-Seop and Kim, Soo-Hyung},
        title = {Facial Emotion Recognition Using an Ensemble of Multi-Level Convolutional Neural Networks},
        journal = {International Journal of Pattern Recognition and Artificial Intelligence},
        pages = {1940015},
        year = {2019},
        doi = {10.1142/S0218001419400159},
        URL = { 
            https://doi.org/10.1142/S0218001419400159
        }
      }
  
## Environment
1. Python 3.5
2. TensorFlow 1.1.0
3. Keras 2.0.6
3. CUDA 8.0
4. cuDNN v5
5. [matplotlib 1.5.3]

## Usage
1. Download [FER2013 testing set](https://drive.google.com/open?id=1YTsJc1taLBC-aHNJdrvMND3_I6EL8Gqn) and save 2 npy files to the root folder
2. Download [trained MLCNN model](https://drive.google.com/open?id=1UtppCc_WT6yqGMJ1RrD4PHJlAB-HiZfn)
3. Run fer2013_ensemble_mlcnns_testing_icprai2018.ipynb
