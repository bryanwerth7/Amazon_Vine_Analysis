# Amazon Vine Analysis

## Overview
This analysis was designed to get a quick overview of whether or not paid reviewers of Amazon's Vine program produced more 5 star reviews VS unpaid reviewers. 

## Results
 - I first had to determine how to get credible reviews from our data, I used only products that had over 20 reviews and at least 50% of them being voted as helpful. After this filtering I found that there were a total of 94 paid reviews and 40,471 unpaid reviews. Filtering shown below:

<img width="853" alt="Screen Shot 2021-11-01 at 8 39 31 PM" src="https://user-images.githubusercontent.com/86524863/139766116-5f26d5bb-661b-497f-a9fd-2d536cd23bba.png">


 - Of those credible reviews, 48 of the 94 paid reviews were 5 stars and 15,663 of the 40,471 unpaid reviews were 5 stars.
 - This showed that 51% were paid 5 star reviews VS 39% of unpaid reviews as summarized in the table below:

<img width="796" alt="Screen Shot 2021-11-01 at 8 27 19 PM" src="https://user-images.githubusercontent.com/86524863/139760135-42d495be-8b73-4d18-a90c-5b4078337d14.png">

## Summary
Just looking at the summary DataFrame it seems like there is some bias in the paid reviews having over 51% being 5 star reviews while unpaid reviews had only 39% 5 stars. There are a lot more reviews that are unpaid reviews so I would ideally like to get more reviews to make sure the bias is not due to a low sample size. We could run a t-test to help determine the statistical signifigance of these numbers. This would give us a more accurate look at the data rather than just the raw results. 
