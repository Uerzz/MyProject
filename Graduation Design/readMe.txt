数据：
cascade_test.txt：
	<message_id>\tab<user_root_id>\tab<publish_time>\tab<retweet_number>\tab<retweets>\tab<increment retweets in 24hours>
	<retweets>: user a:user b:time user a:user b:time user a:user b:time ....

shortestpath_test.txt：
   <message_id>\tab<user_root_id:0>\tab<user_root_id,user_a,userb:time>\tab<user_root_id,user_a,userb:time>\tab<user_root_id,user_a,userb:time>....
   
  run preprocess_graph_signal-degree-weibo.ipynb  Extracting Characteristics of the graph.
  
  run run_model.ipynb Predicting future retweets.