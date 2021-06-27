# Movies-ETL

## Overview
In this exercise I took computer information from wikipedia and a movie rating website.  The goal was the make the data easy to use for a hackathon.  The following things were done to clean the data:
- Removed rows with lost of Null values
- Removed rows consisting of TV shows
- Combined columns that had similar meanings
- Created columns where all numbers had the same format.  If the number was tough to format, the row was removed

After these rows and columns were cleaned, the datasets were combined.  After combining the data from Kaggle and Wikipedia I looked at each set of data and chose which had the best information.  That information was kept, while the other was deleted.

The ratings information was pivoted so that it could easily be combined with the movie information.
