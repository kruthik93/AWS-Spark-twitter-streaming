# AWS-Spark-twitter-streaming
Built architecture to capture, analyze and visualize trends across different words from twitter streaming data. Utilized AWS EC2 to run Spark for streaming and visualizing twitter hashtags for a topic.

1. Initialize an AWS EC2 instance 
 - You can use a free tier instance (we do not need much memory for running this code)


2. Install Spark, Python and get Jupyter notebook running on EC2 
 - You can follow this tutorial for help: https://medium.com/@josemarcialportilla/getting-spark-python-and-jupyter-notebook-running-on-amazon-ec2-dec599e1c297
 

3. Install tweepy package on Python
 - You can do pip install tweepy in pythons command prompt
 

4. Download the code TweetRead.py and run it on your AWS EC2 instance
 - Make sure you change the twitter credentials(which you can get by creating a free twitter app account @ https://apps.twitter.com/app/new) and change the host to the AWS EC2 machine address
 

5. Download the AWS_Spark_streaming notebook and run it on your AWS EC2 instance
 - Again, make sure you make necessary changes to your code
 

You have your twitter hashtag counts running on AWS!

(Major part of the code has been inspired from http://www.awesomestats.in/spark-twitter-stream/)
