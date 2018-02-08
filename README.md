# Multimodel-Social-Media-Prediction

**First, we propose a new multimodal dataset which is derived from the dataset provided as the part of ACM Multimedia Grand Challenge 2017 (T1 Task: Popularity Prediction). Next, we proposed a multimodal approach to Predict Social Media Popularity. Our experiments confirm that we are able to achieve comparable performance by just using half of the training dataset.**
<br /><br />
The task is designed to predict the impact of sharing different posts for a publisher on social media. Given a photo (a.k.a. post) from a publisher, the goal is to automatically predict the popularity of the photo, e.g., view count for Flickr, Pin count for Pinterest, etc. Additional information on the task and original dataset are as follows:
<br /><br />
Original Competition SMP Challenge - ACM Multimedia 2017 T1 task
https://social-media-prediction.github.io/MM17PredictionChallenge/index.html<br />
Dataset link: https://github.com/social-media-prediction/MM17PredictionChallenge/blob/master/README.md<br />
Original dataset contains the following fields: <pid, uid, postdate, commentcount, haspeople, titlelen, deslen, tagcount, avgview, groupcount, avgmembercount>.
<br /><br />
We have extracted additional features and updated dataset for a better understanding of social posts.
The proposed multimodal dataset consists the following fields: <pid, uid, postdate, commentcount, haspeople, titlelen, deslen, tagcount, avgview, groupcount, avgmembercount, alltags, title, description, image_url>
The reasons for creating this new dataset are as follows:
1. Additional information on photos such as '**alltags**', '**title**', '**description**' are added to the proposed dataset. Such information is much useful in popularity detection since the original dataset does not provide much content information. 
2. Many of the image links were broken from the original dataset (probably users have deleted photos or changed visibility settings), so the data size is reduced significantly from 400K to 200K photos. In order that other researchers working on this problem and would like to utilize content information such as '**alltags**', '**title**', '**description**', and '**image content**' without facing the broken link problem, we collected actual images and above-mentioned text information.

CITATION<br />
If you intend to publish results that use the information and resources provided by this challenge, please include the following references:<br />
@inproceedings{Wu2017DTCN, title={Sequential Prediction of Social Media Popularity with Deep Temporal Context Networks}, author={Wu, Bo and Cheng, Wen-Huang and Zhang, Yongdong and Qiushi, Huang and Jintao, Li and Mei, Tao}, booktitle={International Joint Conference on Artificial Intelligence (IJCAI)}, year={2017}, location = {Melbourne, Australia}}<br />
@inproceedings{Wu2016TemporalPrediction, author = {Wu, Bo and Mei, Tao and Cheng, Wen-Huang and Zhang, Yongdong}, title = {Unfolding Temporal Dynamics: Predicting Social Media Popularity Using Multi-scale Temporal Decomposition}, booktitle = {Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence (AAAI)} year = {2016}, location = {Phoenix, Arizona}}<br />
@inproceedings{Wu2016TimeMatters, author = {Wu, Bo and Cheng, Wen-Huang and Zhang, Yongdong and Mei, Tao}, title = {Time Matters: Multi-scale Temporalization of Social Media Popularity}, booktitle = {Proceedings of the 2016 ACM on Multimedia Conference (ACM MM)}, year = {2016}, location = {Amsterdam, The Netherlands}}
<br /><br />
Due to size limitation, we do not upload image content of our proposed dataset in GitHub. However, such images would be provided on request by contacting the following people.<br />
Mayank Meghawat (mayank.meghawat@gmail.com)<br />
Rajiv Ratn Shah (rajivratn@iiitd.ac.in)
