Our client is looking to promote Ed Sheeran's new album - and want to be both targeted with their customer communications, and as efficient as possible with their marketing budget.

As a proof-of-concept they would like us to build a classification model for customers who purchased Ed's *last* album based upon a small sample of listening data they have acquired for some of their customers at that time.

If we can do this successfully, they will look to purchase up-to-date listening data, apply the model, and use the predicted probabilities to promote to customers who are most likely to purchase.

The sample data is short but wide.  It contains only 356 customers, but for each, columns that represent the percentage of historical listening time allocated to each of 100 artists.  On top of these, the 100 columns do not contain the artist in question, instead being labelled *artist1, artist2* etc.

We will need to compress this data into something more manageable for classification!
