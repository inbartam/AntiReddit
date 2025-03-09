# Anti_Reddit
This repository contains the code and datasets used for the analysis of antisemitic discourse on Reddit. The study leverages Natural Language Processing (NLP), Social Network Analysis (SNA), and Large Language Models (LLMs) to examine the spread, structure, and evolution of antisemitic narratives across online communities.

## Overview
With the rise of social media, antisemitic discourse has evolved, blending historical tropes like blood libel with modern digital narratives. This project provides a data-driven approach to detecting, analyzing, and visualizing antisemitic content on Reddit.

## Key Features
Hate Speech Detection: Uses RoBERTa and HateBERT models to classify antisemitic content.
Social Network Analysis (SNA): Constructs user interaction graphs to identify key actors, amplifiers, and spreaders of antisemitic discourse.
Temporal Trends Analysis: Tracks spikes in antisemitic activity following major geopolitical events.
Subreddit-Based Analysis: Identifies the primary communities responsible for generating and amplifying antisemitic narratives.
Centrality Metrics: Uses degree, betweenness, eigenvector centrality, and PageRank to determine influential users in hate speech dissemination.

## Methodology
#### Data Collection
Uses Reddit datasets (October–December 2023) and the IsamasRed dataset (8M+ comments).
Extracts posts/comments using keyword-based filtering.

#### Hate Speech Classification
Applies RoBERTa and HateBERT to generate antisemitism probability scores.

#### Network Graph Construction
Builds user interaction networks from Reddit discussions.
Nodes represent users, edges represent interactions (replies, upvotes, cross-posting).

#### Influence Analysis
Computes centrality metrics to detect top spreaders and amplifiers of antisemitic discourse.


#### Findings
October 7, 2023, marked a massive surge in antisemitic activity, followed by peaks on October 17 and November 19.
1% of users (heavy troop posters) generated the majority of antisemitic content.
4% of users (amplifiers) significantly spread antisemitic posts across subreddits.
Antisemitic discourse initially clustered in anti-Israel/anti-Zionist subreddits but later spread into mainstream Reddit communities.
Historical antisemitic tropes, such as blood libel, are still widely used but have evolved for digital narratives.
