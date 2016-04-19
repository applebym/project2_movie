## Minimum Viable Product ##

![Coeff Plot](https://raw.githubusercontent.com/applebym/project2_movie/master/img/mvp_coefplot.png)

For this project, I am using linear regression to find if there is a relationship between the decay rate of a movie's weekly revenues (my independant variable) and a movie's attributes. Thus far, my best performing model has an adjusted R-squared of 0.23 on the variables month of release date, genre, runtime, and number of theaters. 

MVP - show that months have neg affect which makes no sense, thought that movies that came out in high demand times (holidays and summer) would have a shorter decay rate (i.e. longer tail); CI’s span pos and neg for most categories, which doesn’t tell us much, runtime and num theaters have little to no effect, which also makes sense as don’t take this into account when seeing a movie. next steps is to find better data to include, such as some measure of pre-launch popularity (which could skew decay rate downward due to overhype) or movie quality (such as reviews), or advertising dollars, frequency and time

However, as one can see from the chart above, the beta coefficients do not show an intuitive picture and thus I am seeking to improve upon this model with more information, such as advertising dollars pre-launch, movie ratings, and 
