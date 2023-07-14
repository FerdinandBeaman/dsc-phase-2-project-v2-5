# Kings County Home Assessments

**Author**: [Ferdinand Beaman](mailto:ferdinand.beaman@gmail.com)

## Overview

This project analyzes the the homes sold in King's County Seattle in an effort to direct a renovation company in how they should project the value of their work to customers.

## Business Problem

Beyond merely wanting a more comfortable living space, customers may want to perform renovations on homes in order to increase their value on the open market. This is where we are going to focus our efforts: What kind of work can be done to best increase the value of a home, while also remaining realistic?

## Data

Over 30,000 homes were analyzed, and various features of those homes were provided by Kings County ranging from the age of the house all the way down to the kind of heating it has. Explanations for those features can be found in the data folder. 

## Methods

This project makes heavy use OLS regression, including attempts to transform the data in various ways, such as through log transformation and higher order regressions. This provides a way to ascertain what features are most relevant when predicting a prospective sale price in the near future.

## Results

Presumably, without better location data, the predictive power of the data that was analyzed is somwhat weak, with the best models barely approaching 50% explanatory power. However,  houses with "grade"s of 4 out of 7 or higher seem to have their prices increase by over 200,000 dollars with every subsequent increase in grade.

Installing a new bathroom also seems to raise a home's value by 70,000 dollars.

## Conclusions

This analysis leads to one strong and one soft recommendation for the client:

- **Focus on renovations that will increase the "grade" of the home** While vague, this was the primary way to increase a home's value without extensive work, such as would be the case if the living room would be extended into property that doesn't have foundation underneath it yet.
- **If feasible, installing a new bathroom may not be a bad idea.** I have a limited but nonzero amount of experience in this field, but I believe small bathrooms can be installed in some houses under some circumstances reasonably.

### Next Steps

Additional insight could be found if we had:

- **Better understanding of the "grade" metric.** It is unclear even at info.kingcounty.gov what factors go into "grade", and it's downright baffling what is going on with the houses graded as a 1. Their average price seems far, far too high.
- **Better location data.** Latitude and longitude are not useful without a map, if even then. Specific neighborhood information would be very useful.