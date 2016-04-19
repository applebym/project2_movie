## Minimum Viable Product ##

![Coeff Plot](https://raw.githubusercontent.com/applebym/project2_movie/master/img/mvp_coefplot.png)

For this project, I am using linear regression to find if there is a relationship between the decay rate of a movie's weekly revenues (my independant variable) and a movie's attributes, and if there is, which attributes are most relevant. A model of this type would be able to add value to many players in the movies space, such as movie producers, studios, movie theaters, etc. 

Thus far, my best performing model has an adjusted R-squared of 0.23 on the variables month of release date, genre, runtime, and number of theaters. I do not feel comfortable with this model thus far, as the beta coefficients and confidence intervals do not show an intuitive picture. For example, the coefficients for the release months are all negative. I expected movies released during high demand periods (i.e. holidays and summer) would have a less negative decay rate (or more gradual/longer revenue tail). Below is a graph showing the decay rate by month, in which there appears to be a very slight relationship. 

![Decay Rate by Release Month]()

MVP - show that months have neg affect which makes no sense, thought that movies that came out in high demand times (holidays and summer) would have a shorter decay rate (i.e. longer tail); CI’s span pos and neg for most categories, which doesn’t tell us much, runtime and num theaters have little to no effect, which also makes sense as don’t take this into account when seeing a movie. next steps is to find better data to include, such as some measure of pre-launch popularity (which could skew decay rate downward due to overhype) or movie quality (such as reviews), or advertising dollars, frequency and time

However, as one can see from the chart above, the beta coefficients do not show an intuitive picture and thus I am seeking to improve upon this model with more information, such as advertising dollars pre-launch, movie ratings, and 
