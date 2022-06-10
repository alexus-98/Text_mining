## Text_mining

This repo contains two ipynb files (jupyter notebooks), that are final reports for the [Text Mining and Social Media Mining](https://usosweb.wne.uw.edu.pl/kontroler.php?_action=katalog2/przedmioty/pokazPrzedmiot&kod=2400-DS2TMS) class. I prepared the reports together with Aleksandra Tomczak.  

#### 1. Fake News classification
Aim of the first project was to classify real and fake news about US politics. Along with classification, after data was appropriately preprocessed, we conducted text clustering with k-means and PCA methods.

#### 2. Sentiment Analysis of Tweets
During Covid-19 pandemic many people tweeted their opinions about governmental policies and vaccines that were introduced to help the situation with the virus. We decided to investigate what kind of language is used by tweeter useres who are pro and against the vaccines. This way we wanted grasp what kind of emotions they want to convey through their tweets. 

For this purpose we scraped 5000 thousand tweets which contained hashtags such as #VaccinesWork, #GetVaccinatedNow for pro-vaxxers and #VaccineSideEffects, #Antivaxx for anti-vaxxers. We assessed the sentiment of the two groups using the VADER compound score, we visualized the most frequent words used by the two groups of users and finally we performed LDA and tried to name the resulting topics.
