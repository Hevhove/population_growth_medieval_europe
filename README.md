# Creating an animated graph using Matplotlib


https://user-images.githubusercontent.com/17186736/115138974-a8c01600-a02f-11eb-9ecb-fda9a850f388.mp4

The data needed to create this animated graph was put together by myself, by merging data from several Wikipedia articles:

- https://en.wikipedia.org/wiki/Demographic_history

- https://en.wikipedia.org/wiki/List_of_countries_by_population_in_1600

- https://en.wikipedia.org/wiki/List_of_countries_by_population_in_1700 - Et cetera

I didn’t find any figures to separate Spain and Portugal pre-1600 which is why they are joined in this analysis. Similarly, population count of England, Scotland and Wales is merged pre-1600 and shown as UK. Northern Ireland is excluded.

Plot created with the matplotlib animation package. Initial data was augmented and smoothed with scipy function savgol_filter.
