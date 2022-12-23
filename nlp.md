---
layout: default
---
# Exploring movie plots
To answer our research question on how plots are structured and if they differ across **industries**, **decades** and **genre**, we created an NLP piplinte to: 
1. Study the words using in plots
2. Compare them across the different diversity attributes 
3. Perform semantic analysis and check for summilarities 
4. Propose a method to extract keypoints from summaries. 

## Bag of words
Let's study the words used in formulating the plot summaries and starting by viewing the general word usage across all plots. 
![word cloud all](assets/img/wordcloudall.png)
hmm !! okay now from where are these words comming from 
<iframe src="https://giphy.com/embed/7kFiPRhn3aDYs" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/mrw-oc-informs-7kFiPRhn3aDYs"></a></p>

### Across decades
![word cloud 50](assets/img/50sword.png)
![word cloud 60](assets/img/60sword.png)
![word cloud 70](assets/img/70swords.png)
![word cloud 80](assets/img/80words.png)
![word cloud 90](assets/img/90swords.png)
![word cloud 200](assets/img/2000swords.png)
![word cloud 2010](assets/img/2021sword.png)

From ploting the wordcloud, we can make notice that he movies in the 50s, 60s, 70s are containing more action related words like escape, kill, dead where the 2000s are more into relationships and drama. We can investigate that further by excluding articles and common **empty** words and plot.
This is confirmed more once check the standirized distributions of top 20 words. 
![decade](assets/img/decadedist.png)

### Across industries
To make it brief and not to scroll endlessly in this page, we show directly the distribution of 40 most common words across the industries 
![40com](assets/img/40mostcom.png)
We notice one obvious result is that the indian industry is based around love and family relationship => Drama. For france, it is a mixture btween drama linked words/ crime. This will be more visible once analyzing the genres
