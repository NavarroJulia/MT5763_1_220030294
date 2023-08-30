# MT5763_1_220030294

# Coursework 1 - Intro to Data Analaysis


## Abstract 

The purpose of this report is to statistically investigate, for the TfL, whether and
how the count of bikes rented in London, United Kingdom, depends on a variety
of factors including environmental influencers, such as temperature, windspeed and
humidity. The classification of days into either holidays, weekdays or workdays was
also examined in the analysis.

We began by considering a subset of the data which had counts of bike rents
less than 25,000 (made up around 43% of the data) and provided a 95% confidence
interval associated with this approximation. We calculated the proportions of days
with less than 25,000 rents in each season (e.g., 14% of the (original) data is such
that it accounted for <25,000 rents in spring). A hypothesis test was then used
to conclude that there was a significant difference between the proportion found
between spring and winter.

For the original data set we found changes in proportion of bike rents
throughout the seasons which a Tukey test determined (largest difference was between winter and summer, as one might expect). Making use of a t-test we found
that the expected number of rents between workdays and weekends does not differ
significantly.

This test had a power of roughly 88% for which it would predict correctly. For
a 90% accuracy we require roughly n = 234 observations. We lastly fitted a linear
model to the data, and attempted to predict the bike count based on different
predictors. R code used can be found in the Appendix.
