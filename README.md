Our FM implementation is based on tensorflow 1.12.0.  

You can run our reference training code on-the-fly using the following command:  
./train.sh <training_path> <validation_path> <save_model_dir> <batch_size> <embedding_size> <optimizer [adagrad, adam]> <lr> <task [finish, like]> <track [1, 2]>  
  
track2 like task:   
  auc 86.5%   
  (params: embedding_size=40, adam lr= 0.0005)  
track2 finish task:  
  auc 69.8%  
  (params: embedding_size =40, adam lr=0.0001)



