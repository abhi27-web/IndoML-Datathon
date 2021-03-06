![Main Banner](https://res.cloudinary.com/pooja-gera/image/upload/v1639660453/Colorful_Modern_Abstract_Technology_LinkedIn_Banner_iv1zys.png)

# Introduction

India is home to more than 1.2 billion individuals who come from different regional backgrounds having different mother tongues. There are 1369 rationalized languages and dialects that are spoken across the country as per the data obtained in 2011. In addition to this, as per Statista’s report of 2020, India has also the second-largest (and possibly will have the largest) digital footprint. 

Even after such a humongous user base exists in the country, less research has been performed on these languages and the existing multilingual detection systems perform poorly considering the regional languages of India in particular.  

Moj - one of India’s largest short-video apps has its roots spread in various regions of the country offering videos in multiple regional languages. While people share their creativity, talent, and experiences on the application, a major issue that has been noticed is that the comments on the application are abusive, offensive, and hateful. It is imperative that since the videos are being made in regional Indian languages, the comments are also written in regional languages and/or are a mixture of two or more languages (multilingual). 

The challenge is to develop a solution with the help of Artificial Intelligence to tackle the problem of abusive comments in multilingual Indian languages and detect them.  

One important fact to be noticed is that this problem is not only limited to the Moj application. All social media platforms have the issue of abusive comments in multiple languages prevalent. Research is being performed in both areas - identification of multilingual text and detection of abusive and hateful speech contained within the content shared on social media. Unless we are able to detect the hateful content, it is impossible to stop it from spreading around. For making cyberspace a safe space for everyone alike, it is vital that everyone possesses the freedom of expressing their opinions without the fear of people thrashing or abusing them or passing on hateful comments. 

# How To Use This Repository?

- Step 1: Clone this repository 

```bash
git clone https://github.com/abhi27-web/IndoML-Datathon.git
```

- Step 2: Navigate to the file named ``` Final Submission Code.ipynb```

(Refer to the highlighted yellow portion in the image given below)
![](https://res.cloudinary.com/pooja-gera/image/upload/v1639662651/Navigate_to_file_l8vo9n.png)

- Step 3: Open [IndoML Multilingual Abusive Comment Detection Kaggle Challenge](https://www.kaggle.com/c/multilingualabusivecomment) in your browser 

![](https://res.cloudinary.com/pooja-gera/image/upload/v1639664143/2021-12-16_14_zzbkrd.png)

- Step 4: Navigate to "Code" on the webpage and click on New Notebook 

![](https://res.cloudinary.com/pooja-gera/image/upload/v1639664204/2021-12-16_15_vyidea.png)

- Step 5: Upload the ```Final Submission Code.ipynb``` notebook 

![](https://res.cloudinary.com/pooja-gera/image/upload/v1639664276/2021-12-16_16_njkdvm.png)

- Step 6: Run the cells of the notebook to get the desired results 

![](https://res.cloudinary.com/pooja-gera/image/upload/v1639664355/2021-12-16_17_astpsj.png)
# Conclusion 

In this project we have done the in-depth analysis of multilingual abusive comment detection problem with ML-models and NLP- Model, our investigation has shown the following results:
- Models like Logistic Regression, Random Forest, Decision Trees, K-Nearest Neighbors, Gradient Boosting were used with 2 types of vectorization, which were BOW approach and Tf-Idf Approach were used for ML models and BERT was used for NLP model
- The best performing models were BERT LR-TF-IDF and RF-TF-IDF with accuracies of 0.84, 0.83 and 0.81 respectively.
- The worst performing models were GB-BOW and KN-BOW with accuracies of 0.70 and 0.77 respectively.
- Finally we got the best accuracy of 0.93076 using the Logistic Regression Algorithm along with IndicNLP tokenized TFIDF.


# Standing In The Competition 

![Position](https://res.cloudinary.com/pooja-gera/image/upload/v1639661046/WhatsApp_Image_2021-12-16_at_4.51.02_PM_xcqruh.jpg)
