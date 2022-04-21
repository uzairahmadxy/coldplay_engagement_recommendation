# Instagram Engagement Recommendation

## Overview
This project aims to look at what worked for Coldplay in the past and provide a recommendation based on what strategies have worked for engagement for [Instagram](https://www.instagram.com).

In this project, we look at **Coldplay 🎸** because of the author's appreciation for their music, but the same analysis can be done on any Instagram account.

## Methodology
1. We scrape the images from Instagram using [Instaloader](https://instaloader.github.io).
2. Use object recognition from Google Vision to extract the objects detected in the images.
3. Using Topic Modelling (Natural language processing technique) on the extract image labels. This involves using Topic Coherence & personal judgement to find the optimal number of topics.
5. Combine results with engagement data & see what themes were common in the best posts versus the words.
 
For the purpose of this exploratory project, comments were considered as engagement but a more complicated criterion should be defined involving likes, shares &amp; other social media metrics.

## Results
We have 3 dominant topics in our images:

- Music & Arists
- Musical Instruments
- Photography, Graphics & Art

Looking at the highest and lowest quartiles of posts in terms of engagement, we find that the most popular posts have the highest concentration of topic 1. Lowest performing posts have higher contributionsf of topics 2 & 3.

We would **suggest** that Coldplay focus on posting more pictures that contain the performing artists. Posts should show that they are playing music and entertaining people. These can include fancy lights, fonts and graphics, pictures taken at concerts under the sky as they have performed well. Colors like Blue and Violet are also dominant in these pictures and work well with the theme of the band.

These recommendations are based on what has worked well for Coldplay in the past (common themes in posts that got highest engagement) and further analysis should be made to ascertain if engagement is not caused by other factors e.g temporal heterogeneity.
