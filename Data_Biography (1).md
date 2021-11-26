# Data Biography

### Declaration of Authorship

I, [Jie Shi], confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

[Jie Shi]

Date of signature: 26/11/2021
Assessment due date: 26/11/2021
Student Number: 19106963

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?
Murray Cox, an independent digital storyteller, community activist and technologist, conceived the project, compiled the data and analyzed the data with the help of collaborators[1].

### 2. Why did they collect it?
They collected the data with the objected to: 

Provide the data that quantifies the impact of short-term rentals on housing and residential communities. It also creates a platform with the data to support advocacy for policies to protect cities from the impacts of short-term rentals[1].

### 3. How was it collected?
The data of the "Inside Airbnb site" is sourced from the Airbnb site[1]. They use python scripts to scrape listing information available to users of Airbnb website.

The data scraped from Airbnb website are stored as csv file, which is a delimited text file. It has many columns including the listing ID. In Airbnb website, each listing has a unique listing ID which enable the access of additional information about a listing.

### 4. What useful information does it contain?
There are three parts and contain detailed information about 74,189 listings.

The first part is host information which includes the host name, host photography, a brief profile description, host response condition, host acceptance rate, the date in which the user registered as a host on Airbnb, whether the host is superhost and the numbers of private room listings the host has.

The second part is the basic condition of property, which is composed of name, location, price, the guest capacity, amenities in the property, room type, the number of bathrooms or bedrooms, how long time the renters can book, etc.
The final part is review consisted of the numbers of review, review scores and frequency.

### 5. To what extent is the data 'complete'?
When we say the data is ‘complete’, there are several requirements need to meet. It needs data to be complete without the systematic omission of data[2] and accurate without incorrect data attributed to systemic errors. The data of Inside Airbnb have deficiency on both sides.

On the one hand, according to the discussion in Q.4, we can find that the data is lack of characteristics information of users such as age, race, income, gender, nationality, sexual orientation, social class, physical condition etc. The omission of these fields will lead to significant structural defects in our data. Because for people in the dominant group, their gender, race, age, sexual orientation or class are so normalized that they are not regarded as a sign of difference. But these will make us ignore the needs and behavior of marginalized groups[3].

On the other hand, the data scraped from Airbnb in Inside Airbnb also has critical limitations. Airbnb claims that the Cox’s scraped data are inaccurate, because not all listings are active[4]. And there is evidence that the data of Inside Airbnb has an issue of incorrect data attributed to systemic errors in the data collection process[5]. 

### 6. What kinds of analysis would this support?
With the dataset we can have several topics to discuss.

We can focus on the spatial distribution issues. In this topic, we can discuss the spatial distribution of Airbnb accommodation and pay attention to the distribution of price, quantity, comments, and landlord of Airbnb accommodation in different parts of London. For example, we can make research that Airbnb accommodation spatial distribution and estimates the key factors of its location choice[6].

In addition, pricing issues and influence of the sharing economy is an interesting topic. We can use the fields listed in the data such as host’s characteristic information, neighbourhood description, amenities etc. to make analysis to find the relationship between them with price. 

What’s more, we can analyze and study the reasons behind the best-selling accommodation. The fields like availability can reflect the reservation condition for each property. It means we can find which factor such as host race, host gender, host age, amenities, the number of bathrooms, location etc. have impact on reservation condition. 

### 7. Which of the uses presented in Q.6 are _ethical_?
Just as the data has systematic omission mentioned in Q.5, the analysis we proposed based on this data are likely to only represent the choice of mainstream privileged groups and ignore the needs and characteristics of marginal groups. There are quantities of scholars show that the data which has systematic omission can caused data bias. Data-driven decision-making can be just as easily used to amplify the inequities already entrenched in public life[8]. For example, when we analyze the factors related to the popularity of accommodation, we should note that the data of popularity of accommodation itself is the product of the unequal conditions of social group structure. Airbnb is sharing economy platform, which creates opportunities for users to choose or reject potential owners and customers based on race, gender and sexual orientation. Many studies have shown that the hosts of Airbnb will cancel the reservations of people of color, and users are more inclined to ignore the hosts of people of color when booking Airbnb[7]. Therefore, analysis based on this data will further limit the future potential and basic rights of marginalized groups. In addition, many social groups have no access to the Internet, such as people with visual impairment, the elderly and people with low economic status. Based on the analysis of Airbnb data, we will not be able to get their needs[8].

There is also an issue of privacy leakage. Private information such as personal identity information, behavior information, location information, and social relationships may be disclosed. In 2012, a young girl was told by a company that she was pregnant. The company detected the pregnancy of the female customer by combining the customer's purchase history with the purchase timeline. This is a very terrible thing. The girl lost her privacy about her body and health[9]. The same privacy disclosure problem will also occur on Airbnb. When we use Airbnb based data to analyze, we will obtain the location information and personal characteristic information of hosts and customers. Their behavior data and personal data can be easily mined.

## Bibliography


## Appendix 
[1]	‘Inside Airbnb. Adding data to the debate.’, Inside Airbnb. http://insideairbnb.com (accessed Nov. 23, 2021).

[2]	D’Ignazio C. and Klein L., ‘Chapter Eight: Teach Data Like an Intersectional Feminist!’, in Data Feminism, 2018. Accessed: Nov. 26, 2021. [Online]. Available: https://mitpressonpubpub.mitpress.mit.edu/pub/c5vkehnm/release/5

[3]	D’Ignazio C. and Klein L., ‘Chapter Seven: The Power Chapter’, in Data Feminism, 2018. Accessed: Nov. 26, 2021. [Online]. Available: https://mitpressonpubpub.mitpress.mit.edu/pub/7ruegkt6/release/4

[4]	‘Inside Airbnb’, Wikipedia. Oct. 22, 2020. Accessed: Nov. 26, 2021. [Online]. Available: https://en.wikipedia.org/w/index.php?title=Inside_Airbnb&oldid=984922122

[5]	A. Alsudais, ‘Incorrect data in the widely used Inside Airbnb dataset’, Decision Support Systems, vol. 141, p. 113453, Feb. 2021, doi: 10.1016/j.dss.2020.113453.

[6]	J. L. Eugenio-Martin, J. M. Cazorla-Artiles, and C. González-Martel, ‘On the determinants of Airbnb location and its spatial distribution’, Tourism Economics, vol. 25, no. 8, pp. 1224–1244, Dec. 2019, doi: 10.1177/1354816618825415.

[7]	V. Kakar, J. Franco, J. Voelz, and J. Wu, ‘Effects of Host Race Information on Airbnb Listing Prices in San Francisco’, Mar. 10, 2016. https://mpra.ub.uni-muenchen.de/69974/ (accessed Nov. 25, 2021).

[8]	M. Cheng and C. Foley, ‘The sharing economy and digital discrimination: The case of Airbnb’, International Journal of Hospitality Management, vol. 70, pp. 95–98, Mar. 2018, doi: 10.1016/j.ijhm.2017.11.002.

[9]	D’Ignazio C. and Klein L., ‘Chapter One: Bring Back the Bodies’, in Data Feminism, 2018. Accessed: Nov. 26, 2021. [Online]. Available: https://mitpressonpubpub.mitpress.mit.edu/pub/zrlj0jqb/release/6


