# PISA 2012 Data Analysis
## by Adrien Funel


## Dataset

The PISA study dataset record features about students across the world from different educational systems. More specifically, it looks at their level of preparation for life beyond school. It also provides features about the students background and attitude toward learning.
The records are made of information from about 510,000 students in 65 economies and the assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. 

Important: the whole dataset is not present in the repository. Instead I left a subset with the features we are insterested in, the enhanced data dictionary and the wrangling code to produce them.

Documentation about the plausible values (gauging performance): https://www.oecd-ilibrary.org/docserver/9789264056275-7-en.pdf?expires=1569153995&id=id&accname=guest&checksum=97184E3B4AE5AAC27E429626E5C512F7

Details about the PISA education levels equivalents: https://en.wikipedia.org/wiki/International_Standard_Classification_of_Education#ISCED_2011_levels,_categories,_and_sub-categories


## Summary of Findings

The work ethic coupled with a priviledge social background are two strong drivers of good performance at school. Indeed, persevering students are always rewarded with better results on average than their peers in the same social category. Although, the social background plays a role as a persevering student with a more modest background can have lower grades than his non-persevering peer with a better social background. Moreover, having parents with a high level of education helps to make the study time afficcient since the correlation between study time and results is stonger for their children.
Owning tech devices is proven helpful for persevering students but not nicessarily a factor of success overall.
The origin of the students also play a key role in their performance at school. The correlation between study time and results is stronger for students from a country member of the OECD. Moreover, students speaking a different language at home have consistently lower reading performances on average than their peers speaking the same language at home and at school.


## Key Insights for Presentation

For this research I explored the relationships between the students skills and three other groups of features:
- Their origins and core characteristics (gender...)
- Their social background and environment at home
- Their work ethic

For the presentation I focused on how the time spent on homeworks is converted to good reading performances in relation with the social background and the origins of the students. To start I use an histogram to display the distribution of the time spent on homeworks whick is quite skewed on the left. Then, I introduce a social background variable: the highest educational level of the parents and compare it with the perfomances of the student in reading. Finally, a multivariable visualization shows how the time spent on homeworks is correlated with the results in reading with a distinction on whether the test language is spoken at home by the student or not.