# Multi-Model-Social-Media-Prediction

**We are proposing new dataset with additional information for the mentioned task**
<br /><br />
Task: **Popularity Prediction**<br />
The task is designed to predict the impact of sharing different posts for a publisher on social media. Given a photo (a.k.a. post) from a publisher, the goal is to automatically predict the popularity of the photo, e.g., view count for Flickr, Pin count for Pinterest, etc.<br /><br />

Original Competition SMP Challenge - ACM Multimedia 2017 T1 task<br />
https://social-media-prediction.github.io/MM17PredictionChallenge/index.html<br />
Dataset link: https://github.com/social-media-prediction/MM17PredictionChallenge/blob/master/README.md

Original dataset contains information about : pid, uid, postdate, commentcount, haspeople, titlelen, deslen, tagcount, avgview, groupcount, avgmembercount.<br />

We have extracted extra features and modified dataset for better social post understanding.<br />
Modified dataset : pid, uid, postdate, commentcount, haspeople, titlelen, deslen, tagcount, avgview, groupcount, avgmembercount, **alltags**, **title**, **description**, image_url<br />

Reasons for this New Dataset<br />
1. Extra features of '**alltags**', '**title**', '**description**' added. Please refer dataset.<br />
2. Many of the image links were broken from the original dataset, so the datasize is reduced significantly from 400K to 200K. In case required, images will be provided.
<br /><br />

CITATION<br />

If you intend to publish results that use the information and resources provided by this challenge, please include the following references:<br />
@inproceedings{Wu2017DTCN,
  title={Sequential Prediction of Social Media Popularity with Deep Temporal Context Networks},
  author={Wu, Bo and Cheng, Wen-Huang and Zhang, Yongdong and Qiushi, Huang and Jintao, Li and Mei, Tao},
  booktitle={International Joint Conference on Artificial Intelligence (IJCAI)},
  year={2017},
  location = {Melbourne, Australia}}<br />
@inproceedings{Wu2016TemporalPrediction,
  author = {Wu, Bo and Mei, Tao and Cheng, Wen-Huang and Zhang, Yongdong},
  title = {Unfolding Temporal Dynamics: Predicting Social Media Popularity Using Multi-scale Temporal Decomposition},
  booktitle = {Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence (AAAI)}
  year = {2016},
  location = {Phoenix, Arizona}}<br />
@inproceedings{Wu2016TimeMatters,
  author = {Wu, Bo and Cheng, Wen-Huang and Zhang, Yongdong and Mei, Tao},
  title = {Time Matters: Multi-scale Temporalization of Social Media Popularity},
  booktitle = {Proceedings of the 2016 ACM on Multimedia Conference (ACM MM)},
  year = {2016},
  location = {Amsterdam, The Netherlands}}<br />


For images please contact: <br />
**Mayank Meghawat (mayank.meghawat@gmail.com)** <br />
**Rajiv Ratn Shah (rajivratn@iiitd.ac.in)**
