We use tensorflow 1.12.0. to implement classic FM algorithm

For training, you should execute bash train.sh with some import params:

  @1: training_path
  @2: validation_path
  @3: save_model_dir
  @4: batch_size
  @5: embedding_size
    import fm params
  @6: optimizer [choices: adagrad, adam]
  @7: lr
  @8: task [choices: finish, like]
  @9: track [choices: 1, 2]  
  
You can train icme data by our code directly without any preprocessing.  
Five fields (user_id, user_city, item_id，author_id，item_city) are adopted in our code.

