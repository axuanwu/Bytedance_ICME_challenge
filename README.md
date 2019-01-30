REPO DESCRIPTION
-------  
Our FM implementation is based on tensorflow 1.12.0.  
You can run our reference training code on-the-fly using the following command:  

 *  ./train.sh <training_path> <validation_path> <save_model_dir> <batch_size> <embedding_size> <optimizer [adagrad, adam]> <lr> <task [finish, like]> <track [1, 2]>  
 

ALGORITHM: FACTORIZATION MACHINE
--------------------------------

![image](https://github.com/challenge-ICME2019-Bytedance/Bytedance_ICME_challenge/edit/master/images/fm.jpg)

BASELINE
-------  
Our baseline results with 5 features (user_id, user_city, item_id，author_id，item_city):   

  * track2 like task:   
    auc 86.5%   
    (params: embedding_size=40, adam lr= 0.0005)  
  * track2 finish task:  
    auc 69.8%  
    (params: embedding_size =40, adam lr=0.0001)



