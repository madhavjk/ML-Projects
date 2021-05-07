Book Rental Recommendation
-
DESCRIPTION


#### BookRent is the largest online and offline book rental chain in India. The company charges a fixed rental fee for a book per month. Lately, the company has been losing its user base.
#### The main reason for this is that users are not able to choose the right books for themselves. The company wants to solve this problem and increase its revenue and profit.
---

#### Objective: You, as an ML expert, have to model a recommendation engine so that users get recommendations for books based on the behavior of similar users. This will ensure that users are renting books based on their individual tastes.

Actions to Perform:

- Read the books dataset and explore it.
- Clean up NaN values.
- Read the data where ratings are given by users.
- Take a quick look at the number of unique users and books.
- Convert ISBN to numeric numbers in the correct order.
- Do the same for user_id. Convert it into numeric order.
- Convert both user_id and ISBN to the ordered list i.e. from 0...n-1.
- Re-index columns to build matrix later on.
- Split your data into two sets (training and testing).
- Calculate the cosine similarity.
- Use the evaluation metrics to make predictions.
