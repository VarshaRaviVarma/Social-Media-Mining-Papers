# “COVID-19 VACCINE MISINFORMATION ANALYSIS”

## Research Question
Considering the dire situation of COVID-19, how much of the information related to its vaccine has been misrepresented?

## Background
There is always hesitance following misinformation, and in the case of COVID-19, the situation is no different. False claims made regarding the COVID-19 vaccine may undermine public trust in current vaccination campaigns, endangering public health worldwide. In response to the outbreak of COVID-19, the internet has been flooded with misinformation. Additionally, anti-vaccine activists have begun to use social media platforms such as Twitter to promote their opinions. In order to fully understand the phenomenon of vaccine hesitancy and the massive spread of misinformation about these vaccines through the lens of social media, it is very important to collect all the appropriate data and perform a study/analysis on it.

## Data
In this study, a set (hundreds) of Twitter posts (tweets) and Twitter hashtags that publicly endorse vaccine and anti vaccine stance is used as the dataset. The datasets have been made freely accessible to the research community through various dataset websites as well as GitHub repositories. Using prominent hashtags, shared news sources, political viewpoints, and user tweets, we characterize stances and categorize them into groups for the purposes of comparing and determining the volume of misinformation being spread. The datasets are used for research/analysis purposes, while a manually collected dataset is used for testing and determining the final results of the study.

## Method
The study employs 'sentiment analysis' as its research method.
Utilizing the Twitter streaming application programming interface (API), we collected data based on a set of specific vaccine keywords. Secondly, the tweets which engage in spreading misinformation narratives will be analyzed. In order to create a list of keywords that indicates opposition to vaccines, snowball sampling will be used in which we select and store the phrases for and against in two separate categories. Using this approach, a small set of keywords is gathered that are used exclusively in the context of misinformation about vaccines that appears on Twitter, such as #vaccineupdate, #vaccinefacts, #vaccinemyths or #vaccinedamage. The sentimental and opinionated tweets can be classified with classifier models into vax and anti-vax categories, and then analyze how much of the information is true or false.

## References
1]	Hayawi, K et al. “ANTi-Vax: a novel Twitter dataset for COVID-19 vaccine misinformation detection.” Public health vol. 203 (2022): 23-30. doi:10.1016/j.puhe.2021.11.022

2]	W. Jennings, G. Stoker, H. Bunting et al., “Lack of trust, conspiracy beliefs, and social media use predict COVID-19 vaccine hesitancy,” Vaccine, vol. 9, no. 6, p. 593, 2021.

3]	S. W. H. Kwok, S. K. Vadde, and G. Wang, “Tweet topics and sentiments relating to COVID-19 vaccination among Australian twitter users: machine learning analysis,” Journal of Medical Internet Research, vol. 23, no. 5, article e26953, 2021. 
