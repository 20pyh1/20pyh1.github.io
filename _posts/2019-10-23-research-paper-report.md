---
layout: post
Layout: post
Title: Research Paper Report
published: true
title: Research Paper Report
---

**Summary**

The paper I read, "Internet Recommendation Systems" by Ansari, Essegaier, and Kohli, examines the merits of two different types of recommendation systems most commonly used by online firms at the time of publication (August 2000). The first is comprised of collborative filtering, which "mimics word-of-mouth recommendations" and predict a person's preferences as a function of other people's preferences. The second is called content filtering and bases recommendations on user preferences for product attributes. There are at least five main information sources for making recommendations: expressed preferences among alternative products, preferences for product attributes, other people's preferences and choices, expert judgements, and predictive individual characteristics. Ansari, Essegaier, and Kohli use a hierarchical Bayesian approach to design a recommendation system that statistically integrates all five types of information. Their preference model accounts for preference heterogeneity across users and unobserved product heterogeneity through the interaction of product attributes and consumer characteristics. They tested their model on movie recommendation data and found that it performed better than collaborative filtering generally, since it would factor in any data regarding the user or the product, but still resulted in inaccurate predictions when there was a lack of information about a person or movie, as was to be expected.

I believe their results, since they included a lot of regression tables that showed their findings and in general their explainations made sense. For each equation they used in their model, there was a full explaination of the variables used.

**Application to Project**

After reading this paper, I don't think there is anything that I would have done differently for Clink! Our recommendation system is very similar to the content filtering method mentioned in the paper. We had actually considered having our recommender be more like their model and also taking into consideration what other users thought about certian events and what kind of person the user was based on information gleaned implcitly from their profile. We decided against it because it felt too much like FaceBook, which we were trying to avoid.

I don't think we can compare our product to the model Ansari, Essegaier, and Kohli designed because we didn't create a recommender model. We only know that it is something that we need to implement in order to complete our task of finding the perfect events for a user. The recommender system we plan to use is simpler than theirs; it takes in less data to make its predictions and so may be less accurate, as their tests showed. However, in the context of our app and its purpose, I don't think we need a recommender system that strong. We are only looking at the explicit user preferences for product attributes for our task. The current issue we are solving is that there is no method of recommendation at all in most listings of events, so I think it is ok that we are starting small. However, I will admit that accuracy never hurts, so if we were to actually implement this app, we might look into ways to improve the accuracy of our recommender system.

**Citation**
Ansari, Asim, et al. “Internet Recommendation Systems.” Journal of Marketing Research, vol. 37, no. 3, 2000, pp. 363–375., doi:10.1509/jmkr.37.3.363.18779.

**Link to Paper**
https://journals.sagepub.com/doi/pdf/10.1509/jmkr.37.3.363.18779
