# Data Privacy Final Project

Our group decided to use the “High School Student Performance and Demographics” dataset to base queries on for the final project. This dataset had both quantitative and qualitative variables to look at, all of which seemed straightforward to make logical conclusions with whatever query asked on the data. Meaning that logical assumptions could also be made which we’ll expand upon when we get into the code itself.

Looking at the first chunk of code we defined the different mechanisms that would be used throughout the rest of the code as well as just printing the first five rows of the data here to get a glimpse of what the data set looks like to reference along the way.

From there, calculated the lower and upper bound of absences which is a quantitative column in the dataset. As mentioned previously, many of the fields in the dataset are logical. This makes it easier to put the conclusions into perspective such as max 75. This just means the maximum number of absences of a student was 75.

So taking those values we found the clipping parameter for the mean here in this cell. Then we decided to compare the average both by itself and with the laplace mechanism and also with the gaussian mechanism. Just quantitatively as epsilon increased the mean absence decreased and then plateaued around 5.6 when using the laplace mechanism. As for gaussian, there were increases there’s a steady increase in the mean as the epsilon increases at a greater rate in comparison.

Dataset: https://www.kaggle.com/code/marosz/math-final-grade-correlation-and-comparison#Comparisons:-the-students-whose-final-grade-is-75%-or-better-vs.-the-students-whose-final-grade-is-50%-or-worse

Final Grade: 95%
