# ACM Research Coding Challenge (Spring 2023)

## The Problem
  - Are there any correlations between Temperature and Luminosity?
  - Are there any correlations between Star Type and Spectral Class?
  - Are there any correlations between Star Color and Spectral Class?
  - Analyzing a HertzSprung Russell Diagram to compare the characteristics?
  
## The Planning
  When I first saw the data set, I took a deep breath and went through each of the columns and saw the types of data marked under each characteristic. Personally, I found the following characteristics interesting: Temperature, Luminosity, Star Type, Spectral Class, and Star Color. I filtered each category one by one and compared the data to another of the categories that I found interesting. I would use ascending values of each category to try to find a trend between two characteristics. However, I also had to search up the definiton of certain categories, such as Spectral Class and the definition of the Star Types in order to truly grasp what I am working with. Next, I thought through what I wanted to do. I personally preferred to create dot plots because having discrete data between the categories could best help me regress a trend.
  
 ## The Solution
  I opened up Kaggle and created a Python notebook. Now, I have used Python for basic programming before, but I have never done data analysis with it. My plan was to find correlations between the characteristics I had picked
  
## The Analysis
  Starting with the correlation between Temperature and Luminosity, I saw the numbers from decreasing Temperature to increasing Temperature in the x-axis; I put the Luminosity from decreasing to increasing in the y-axis. I noticed that the higher K of temperature becomes, the Luminosity, or the light with respect to the sun increases, creating a linear trend. Which meant that that temperature and luminosity was increasingly correlated. Next, between the Star Type and Spectral Class, I saw that most of the giants and supergiants occupied the higher Spectral classes of K and M, whereas the white dwarfs mostly were in the lower O, B Spectral classes. In relation to the Star Types within the Spectral classes, I noticed that the Star Colors of Red or Yellow-Orange were mostly clustered around the higher G, K, M spectral classes, related to its warmer colors, and the cooler colors of the Dwarfs that were Blue or White were in the lower OBA Spectral classes. Finally, I combined all the characteristics I selected into a HertzSprung Russell Diagram to see which traits are constantly grouped among the stars. I found that higher Temperature and Luminosity correlates with a warmer color such as Red or Yellow-Orange, and therefore is likelier to occupy the G, K, M spectral classes as SuperGiants. Lower Temperature and Luminosity correlates with a cooler color like white or blue, and is likelier to occupy the O, B Spectral Classes as Dwarf stars.

## Reflection
  This exercise was one of its first that I have tried in my life. As somebody who is interested in data and data analysis, I loved getting a taste of using Python for data analysis in Kaggle. Learning new commands to create graphs helped me realize I can do this with any type of data in the world, and manipulate to my will to see what trends or patterns I get to predict newer datas. Furthermore, it was great going through a massive data set to learn what I want to do with the data. If I had more time, I would have loved to run more analyses and even use Machine Learning to train the model to predict newer stars or create different types of graphs with Python commands. 
  
## Citations
  - https://www.kaggle.com/code/stas2328/dot-plot-graph-in-python
  - https://www.kaggle.com/code/salmanhiro/hertzsprung-russell-diagram
  
