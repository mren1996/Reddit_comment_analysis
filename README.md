# Reddit_comment_analysis
Getting Reddit comments in real-time and inputting them into an NLP sentimental analysis pipeline for classification.

The first step of the pipeline is to get live comment from a particular subreddit. In this case, I picked r/politics due to its high traffic. The comments in its raw format including all information is shown in the image below:
![image](https://user-images.githubusercontent.com/64988580/104274711-567ec000-5456-11eb-94ac-f3c395d11cd3.png)

The second step of the pipeline to preprocess the raw incoming comments from the last step. This can include tokenization, changing character cases, getting rid of some long URLs and changing it to </URL>, etc. Some of the preprocessing functions are taken from other preprocessing libraries.
![image](https://user-images.githubusercontent.com/64988580/104274838-934ab700-5456-11eb-9483-d136c5e66acd.png)

The final step of the pipeline is to apply our processed Reddit comment data and use it in some NLP model. Here we first to name entity recognition and then sentiment analysis is conducted. The results are shown in the next two photos below. 
![image](https://user-images.githubusercontent.com/64988580/104274981-d73dbc00-5456-11eb-83d2-0040acf8cb0e.png)

![image](https://user-images.githubusercontent.com/64988580/104275128-1f5cde80-5457-11eb-8eb6-b00f707deff5.png)
