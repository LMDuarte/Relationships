## LGBT and Straight relationships

### Visualization
As scientists and statisticians,we must inform our community


We must find a way to appeal to the masses

![image](https://user-images.githubusercontent.com/69866550/100770508-f4488f00-33c2-11eb-8f90-ea136c911212.png)

In this study, I will use data from married couples in the United States, to go into detail on the strengths and weaknesses of different visuals.

### Same-sex and Different-sex Marriage
If we want to understand marriage's nuances, it is essential to investigate all forms of unions present in the United States. Marriage has long been defined in a rigid binary between men and women. Although, the reality has been that many same-sex couples have shared lives. Past studies of romantic relationships have neglected to include same-sex couples in their analysis

![image](https://user-images.githubusercontent.com/69866550/100771892-8f8e3400-33c4-11eb-91a8-a24af45a0bea.png)

This study aims to visualize and quantify differences between gay, lesbian, and straight relationships. This comparison will be approached by analyzing multiple variables such as: 

```
Coping with stress
Taking care of their sick partner
Positive communication between partners
Sharing of power in a relationship
            &
Happiness with the relationship
```

### Hypothesis

H1: Depending on the relationship type (gay, lesbian, and straight) there will be a significant difference between how participants indicate that their partner helps them with stress

H2: Depending on the relationship type there will be a significant difference between the level of care presented to sick spouses 

H3: Depending on the relationship type there will be a significant difference between participants indication that both partners have the same power in the relationship

H4: Gay, lesbian, and straight couples will not show a significant difference in how they score their happiness with the relationship

H5: There will not be a significant difference between the communication of gay, lesbian and straight couples


## Results
### Demographics

This study analyzed responses from 838 participants. 
The sample had an age range from 35 to 65, with a median age of 48.60 (SD =8.380246). The sample was divided into three relationship types that participants could fall under: Gay (Men with Men) (29.6%), Lesbian (Women with Women) (40.8%), and Straight (Men with Women) (29.6%). Most of the sample identified as White (90.1%), followed by Black (3.9%), and Asian / Pacific Islander (3.2%).  Additionally, a small number also reported being Hispanic/Latino (4.3%).

### Power Difference
Participants were asked to indicate if they agreed to the statement:

“My spouse and I have equal power in our relationship”

Participants had the option to select that they: Strongly disagree, Disagree, Neither agree nor disagree, Agree, or Strongly agree. A two-sample test of proportions was conducted between Lesbians’ (49.7%) and Gays’ (44.8%) indication that they strongly agreed, (1, N= 342,248) =1.2204, p=0.2693. Additionally, the same test of proportions was conducted between Lesbians’ (49.7%) and Straights’ (37.1%), indication that they strongly agreed to the statement, (1, N= 342,248) =8.7569, p=0.003.  

![image](https://user-images.githubusercontent.com/69866550/100772262-fdd2f680-33c4-11eb-912a-eee868824ce9.png)

![image](https://user-images.githubusercontent.com/69866550/100772302-05929b00-33c5-11eb-8ae4-bc8514b36ea5.png)

![image](https://user-images.githubusercontent.com/69866550/100772320-0c211280-33c5-11eb-8d4b-e65da77f44d2.png)

Figure1,2,3: Response to “My spouse and I have equal power in our relationship”

For this question, I decided to visualize the data with a waffle graph. The waffle does an excellent job at visualizing proportions. Additionally, it is visually appealing, colorful, and eye-catching. Its weakness lies when comparing groups. For this specific analysis, the sample contained an equal number of participants in a gay relationship and a straight relationship, which results in a comparable graph. However, the sample had a higher number of participants in a lesbian relationship, which results in a graph that, visually, does not easily convey the difference between the groups. 

The issue of sample size can be resolve by visualizing the data in a pie chart instead.

![image](https://user-images.githubusercontent.com/69866550/100772691-8ce00e80-33c5-11eb-905b-60f638237bb2.png)
![image](https://user-images.githubusercontent.com/69866550/100772716-936e8600-33c5-11eb-8859-66af0ece434f.png)

### Partner Care
The original survey implemented a scale that measured both positive and negative behaviors associated with caring for a sick spouse. Participants were asked to rate how often their spouses engaged in actions that would aid them.

Specifically, participants rated the following scenarios:
```
My spouse provided physical care for me
My spouse helped me get a better perspective on the situation
My spouse took care of tasks I normally do in order to help me
My spouse dealt with doctors or medical staff in ways that helped me
My spouse gave me the time and space that I needed.
```
They had the option of rating the scenario as happening:
```
often
sometimes
rarely
never.
```
The variable of partner care was divided between lesbian (M=14.75, SD= 6.55), gay (M=13.78, SD=6.24), and straight (M=13.34, SD=7.34) participants. A one-way ANOVA was performed between relationship types, F (2, 826) =13.46, P<0.000. Figure 7 visualizes the differences between the groups;The graph was built with “ggplot2”.

![image](https://user-images.githubusercontent.com/69866550/100773202-28717f00-33c6-11eb-8c24-3b229fd99c1a.png)

Figure7

###Happiness

The original study asked participants to rate their happiness with their relationships. Specifically, the question read: 

"Please indicate the degree of happiness, all things considered, of your relationship." 

Participants could rate their happiness as either: 
```
Extremely unhappy
Fairly Unhappy
A little Unhappy
Happy
Very Happy
Extremely Happy
Perfect
```
The happiness scores were compared between relationship types; Lesbian (M= 4.9, SD=1.96), Gay (M=4.61, SD=2.24), and Straight (M=4.14, SD=2.34). A one-way ANOVA was performed between relationship types, F (2, 828) =5.85, P = 0.003. The data is visualized in figure9; it was built with "ggplot2".

![image](https://user-images.githubusercontent.com/69866550/100773485-8f8f3380-33c6-11eb-9b2a-f4cbaa96a85f.png)

Figure9

###Communication

Similar to partner care, communication was measured by a scale. The scale was designed to rate positive behaviors related to communication. In the positive communication scale, participants rated how frequently they engaged in each behavior. 

The scale asked participants if they ever engaged in the following: 
```
Give your spouse space when they are troubled or stressed? 
Sense when your spouse is disturbed or bothered? 
Show with your behavior what you what or need from your spouse? 
Tell your spouse what you want or need from him/her? 
Tell your spouse what you want or need from him/her? 
```
Participants could answer by selecting that they engaged:
```
Never
Very Little
Occasionally
Somewhat Frequently
Very Frequently
```
The data was separated between Lesbians (M=18.71, SD=4.64), Gays (M=16.18, SD=7.92), and Straights (M=18.5, SD=4.97). A one-way ANOVA was performed between relationship types, F (2,834) =0.833, P = 0.435. The data is visualized in figure10; it was built with “ggplot2” 

![image](https://user-images.githubusercontent.com/69866550/100773871-0f1d0280-33c7-11eb-99b4-31aac71d7a39.png)
Figure10


### Coping with Stress
Similarly, partner care, coping with stress was measure with a Likert scale where participants rated their partners' behaviors. 

Participants rated the following scenarios: 
```
My spouse expresses that they are on my side
My spouse listens to me and gives me the opportunity to communicate what really bothers me
My spouse helps me to see stressful situations in a different light
My spouse takes on things that I normally do in order to help me out. 
```
Participants were given the option to rate scenarios as happening:
```
Very Rarely
Rarely
Sometimes
Often
Very Often
```
When looking at coping with stress, I decided to approach the visualization differently.  Using the "likert" package, I was able to visualize the whole scale in one graph. 

![image](https://user-images.githubusercontent.com/69866550/100774330-94081c00-33c7-11eb-9c38-3da2714a504e.png)

![image](https://user-images.githubusercontent.com/69866550/100774370-9c605700-33c7-11eb-81fb-745fc17dc6d7.png)

![image](https://user-images.githubusercontent.com/69866550/100774389-a2563800-33c7-11eb-8647-c92e7b8cecb4.png)

Figure15: Lesbian participants responses to the stress scale

The Likert bar graphs seen in figures 15 properly visualize all responses, to the “stress” Likert scale. These graphs can present a lot of information without being overwhelming to the reader, while also being visually impressive and colorful. By looking at the three graphs, it is evident that all groups score a lower frequency for both: “See stressful situations in a different light” and “Takes on things that I normally do.” Nevertheless, the graph cannot correctly convey if all groups score similarly; for that analysis, a box plot is still necessary.

The variable coping with stress was divided between relationship types
When the data was divided between Lesbians(M=14.38,SD= 5.47) , Gays (M=14.28, SD=4.71) , and Straights(M=13.51, SD=4.97) it was compare with a one-way ANOVA, F(2,835)=12.41, p<0.00.

![image](https://user-images.githubusercontent.com/69866550/100774767-0e38a080-33c8-11eb-8d7c-4545d44ed0af.png)

Figure16: Participants responses to the stress scale

![image](https://user-images.githubusercontent.com/69866550/100774973-45a74d00-33c8-11eb-8147-8082c4417ad9.png)


## Discussion
The purpose of this study was to visualize and quantify the difference between same-sex and different-sex couples. Additionally, the analysis of different scales and individual Likert questions served to showcase various visualization methods.

### Power in the Relationship
The data showed that Lesbians rated "strongly agree" in a higher proportion than straight participants. Yet, Lesbians were not significantly different from gay participants. Future studies should test if these results have to do with the rejection of social norms when entering a same-sex marriage.

### Partner Care
When observing the partner care scale results, it was visible that Lesbian participants scored the highest, and Straight participants the lowest. The one-way ANOVA test can tell us that lesbian, gay, and straight participants differed in their scores. These results are supported by what was previously known in the literature.

### Happiness
When observing the boxplot generated for "happiness with the relationship," it visible that gays, lesbians, and straights scored differently. The one-way ANOVA can only tell us that the three groups differ in their ratings; it is not clear if gay and lesbian participants differ from each other. Nonetheless, it is observable that straight participants scored the lowest. A single question measured the variable of happiness; future studies should go further in-depth to analyze reported happiness in same-sex and different-sex couples.

### Communication
The visual for "positive communication" in a relationship clearly shows the similarities between the groups. There was not a significant difference between either gay, lesbian, or straight participants. Although there is no significant difference between the groups, the lack of studies investigating same-sex couples gives weight to these findings. Further studies should go into communication styles in the LGBTQ community.

### Coping with Stress
Most participants in the study, regardless of the type of relationship, selected at least "often" in the scenarios presented in the "coping with stress" scale. When looking specifically at the average scores on the scale, it is visible that the groups differ. Lesbian participants score the highest and straight participants the lowest. The one-way ANOVA showed a significant difference between the groups. 

## Conclusion-Visuals
Every visual presented in this study has its strengths and weaknesses; 

it all comes down to the visual's intended purpose.

### Waffle and Pie
The waffle graph served to visualize a single Likert question. With the waffle, it was visible how participants' responses were mostly located in a higher level of agreement to the statement "My spouse and I have equal power in our relationship." Still, it was not visible that there was a significant difference between Lesbians' selection and Straights' selection of strongly agree. That is only conveyed with the proportion test that was conducted between Lesbian and Straight participants. 

Although the waffle failed to visualize the difference between groups, the pie graphs could visualize the comparison. The main issue that the pie graph resolves, is the differences in sample size between groups. The pie graphs visualize proportions, which results in comparable visuals. Both the pie and the waffle graphs present the data in a colorful, appealing, and informative manner.

### Box Plot
The Box plot serves to visualize Likert scales between multiple groups. The most significant advantage of the boxplot is visualizing a lot of data concisely and cleanly. A single boxplot can convey the distribution, the concentration, and outliers in the scores for a scale. Additionally, it showed how those scores varied between the three groups. However, to convey all that information, it needs to summarize some details from the data.

### Likert Bar Graph
Likert bar graphs can visualize either multiple groups answering the same question or one group answering numerous questions. In this specific analysis, three different visuals were generated, each showcasing the same scale, with the only difference being the participants' sexuality. The visual provided the distribution of responses for all questions in the scale. The liker bar graph also has the advantage of being colorful and provide information at a glance.


![image](https://user-images.githubusercontent.com/69866550/100775481-f57cba80-33c8-11eb-8650-3a0a21ae4842.png)






