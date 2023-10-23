Project-1-Pandas
Overview
This aim of this project is to clean and format a dataset containing information about shark attacks, and use the data to produce visualizations that will either prove or disprove my hypotheses.

Requirements/Libraries Used:
This code was written in Python/Jupyter Notebook, using the following libraries:

Numpy
Pandas
matplotlib.pyplot
Seaborn

Hypotheses:

1- South Africa is a save country to practice water sports
2- Summer is the best season to go to South Africa
3- Analyse each region most dangerous activity and when are shark attacks happening

1 - South Africa is a save country to practice water sports:

The first part of the analysis has been focused on searching which are the most dangerous coutnries in the world, in other words, were have been more attacks througout the times. The study has revelead that USA is the country with more attacks, Australia is in the second position and South Africa is ranked 3rd. As we wanted to travel to South Africa this summer, we will take a closer look to its region and the times when the attacks happened

plot 1 countries
plot 2 regions



2- Summer is the best season to go to South Africa:

We would like to travel there in the summer (December, January and February). We are hoping that the attacks are produced in the winter, as we know sharks like the cold water. Surprisingly as we can see on the plot below those are the months with higher number of attacks. Know that we know that summer is not a safe season we would like to know wich activity is the most dangerous in each region and when we should avoid doing it.

Plot months


3- Analisis of each region most dangerous activity and when is happening

In the third part of the analysis we will focus on each region of South Africa (Eastern Cape Province, Western Cape Province, KwaZulu-Natal). 
a
- Eastern Cape Province: After the analisis we have found that the activity with a higher number of attacks in Eastern Cape Province is Surfing with 58 registered attacks. In this region we should take care doing this activity in the months of July with 14 attack, May with 8 attack and February with 6 attacks.

- Western Cape Province: The activity with higer reported attack numbers is Spearfishing with 27 reported shark attacks. If we want to do this activity safely we should take care in the months of September with 4 attack reports, December wih also 4 and February with a total of 3 attacks.

- KwaZulu-Natal: For the region of KwaZulu-Natal, we have found that the most dangerous activity is Swimming, with a total of 34 reported shark attacks in the history of the region. If we want to go for a swim in this region we should take care in months like January with 9 attacks reports, November with 5 reports nd February with also 5 reports.


In conclusion if we want to travel to South Africa we should know that is a dangerous country ranked 3r on most shark attacks. If you still want to travel there keep in mind to NEVER do it on the summer, as we have seen that is the most dangerous season. If you do it try not to practice Surf in Eastern Cape Province, Spearfishing in Western Cape province and Swimming in KwaZulu-Natal.







In this first inquiry, we recieved conclusive results, albeit with some caveats. An important thing to note when looking at this data: the general reporting of shark attacks between 1900-1950 is not very thorough.

Therefore, our conclusions about the nature of fatal shark attacks before 1980 should be taken with a grain of salt. That being said, the data is clear: all of the shark attacks recorded before 1920(in our dataset) were fatal, with a signficant portion of the attacks before 1980 also being fatal (but not all)

year_plot

In the violinplot above, we can see that there are NO non-fatal attacks prior to roughlt 1930 (that were recorded). We can also see that there is a significant increase in (reported) attacks overall after 1930, with non-fatal making up the majority of the newer reported attacks

year_swarm

The swarm chat we see here provides a little bit more detail about the ratio of fatal shark attacks per year. Here we can see that 1940 is really the cutoff date for "fatal-only" shark attacks.

Shark attacks in the Southern Hemisphere
This inquiry was probably the most conclusive of all my 4 hypotheses.

hemisphere_heatmap

In this heatmap, we can see very clearly that there is a huge difference is total number of fatal shark attacks per hemisphere, with the southern hemisphere being by far more life-threatening.

hemisphere_bar

We can also see that there is a significant difference in overall total attacks; with the Northern hemisphere being largely safer than the South when we look at non-fatal attacks

Shark attacks on the West vs East Coast of the USA
My intitial thought was that West Coast sharks would be as mellow as their land locked neighbors in California and Oregon. However, the numbers proved that my initial expectations were far from correct:

us_attack_heatmap

In fact, we can very clearly see two things:

There is no difference in fatal shark attacks when we look at both coasts
West Coast sharks attack more frequent overall, meaning that while you're more likely to get attacked on the west coast, you're less likely to die because of it
us_attack_bar

As we can see in this graph, the West Coast represents a much larger proportion of overall shark attacks in the US. From this data we can also see that the ratio of fatal:non-fatal attacks is WORSE in the East, meaning a East Coast shark is more likely to kill you. (this kind of proves my theory, but not really)

Shark attacks in Australia have the highest chance of fatality.
We already know that the sharks in the Southern hemisphere are way more likely to kill you. It stands to reason that sharks from Australia (also known as the country where everything wants to kill you) are more likely to be involved in fatal attacks. And the survey says....

dangerous_waters

The answer should come as no surprise: If you're a human and you live in Australia....leave. Interestingly, the United States has a much higher frequency of shark attacks, but the sharks take pity on American swimmers at a much higher rate than Australian sharks.

In Conclusion
Be glad you were born in this era, otherwise you'd probably be dead already due to shark attack
If you live south of the Ecuator, reconsider swimming
If you live in the US, move to the West Coast: the sharks are friendlier ;)
If you're Australian, don't trust any sharks