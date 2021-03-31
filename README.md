# Vine_Review_Analysis
## ***Overview***
Our task was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Our main goal is to determine if there is any bias toward favorable reviews from Vine members or not.
## ***Results*** 
Having completed my analysis using PySpark I have come to the following conclusions:

- How many Vine reviews and non-Vine reviews were there?

Out of the total of **8409 reviews**, only **47** of them were from Vine mebers, while the remaining **8362** reviews were from non-Vine members. 

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

**15** reviews from Vine members were 5 star reviews, **4332** reviews were published by non vine members.  

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

**31.9% of Vine** members gave 5 stars based on their experience, compared to **51.8% of non-Vine members**, who gave the highest rating possible.

<img width="160" alt="Screen Shot 2021-03-31 at 4 28 29 AM" src="https://user-images.githubusercontent.com/73204192/113114799-b70dd580-91d9-11eb-95a4-66d8bd2fb2e1.png">.                                                 <img width="165" alt="Screen Shot 2021-03-31 at 4 30 36 AM" src="https://user-images.githubusercontent.com/73204192/113114970-ecb2be80-91d9-11eb-9ef6-9277d2400acc.png">



## ***Summary***
Based on our analysis there is no indication of any positivity bias for reviews from Vine members despite the incetive provided - **31.9% vs 51.8%**.  Percentage of reviews would be a reliable metric considering that the absolute ammount of Vine members was relatively low. In addition to that analysis, we could also include more reviews by not limiting our set to only 20 or more total votes - the result will most lkely be the same but customers are all different and some mgiht be more active than others.  
