# Marketplace-Promotion-Recommendation-Challenge-
This was a challenge that predicts a marketplace promotion using a recommendation system prediction. 

# Overview
Marketplaces frequently have several promotion tools available at the same time, but not every tool is equally useful for every seller. In this challenge, your task is to rank candidate promotion tools for each seller snapshot so that the most relevant tools appear at the top of the list.

Each query corresponds to one seller at one weekly decision point. For that query, the dataset provides 8 candidate promotion tools along with seller context, commercial performance features, operational signals, and tool metadata. Your model should score every candidate row so that the best tools for a seller receive the highest scores. Strong solutions should use both seller-side and tool-side information, respect the temporal structure, and optimize the ranking objective rather than treating rows independently.
