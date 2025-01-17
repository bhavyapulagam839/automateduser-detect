# Digital Camouflage: Detecting Coordinated Inauthentic Activity in Military Social Media Networks
A computational framework for identifying and analyzing coordinated inauthentic behavior on social media platforms, with a specific focus on military-affiliated Twitter accounts.
📋 Overview
This research project presents a systematic approach to detecting coordinated inauthentic behavior on social media platforms. The framework integrates linguistic analysis, behavioral pattern recognition, and machine learning techniques to identify synchronized account activities through various metrics.
Key Features

Timeline activity analysis
Vector representation of account behavior
Automated account detection
Similarity analysis for linked accounts
Threshold-based group merging
Comprehensive validation methodology

🔍 Methodology
The framework employs a four-step approach:

Timeline Activity Analysis

Focuses on recent activity within 2023
Uses modified BLOC (Behavioral Language Online Characterization) framework
Filters inactive accounts


Vector Representation

Encodes daily activity patterns
Creates 364-day activity vectors
Enables efficient comparison of posting patterns


Automated Account Detection

Implements hard matching algorithm
Identifies identical or near-identical posting patterns
Groups accounts based on automation signatures


Similarity Analysis

Evaluates shared content features
Analyzes common domains, hashtags, and mentions
Uses threshold-based merging for group identification



📊 Dataset

Initial dataset: 769 Twitter accounts
Cleaned dataset: 602 active accounts
Time period: August-October 2023
Focus: Military-affiliated social media accounts

🛠️ Implementation
Dependencies

Python (version requirements TBD)
Modified BLOC framework
Data processing libraries
Network analysis tools

Key Components
pythonCopy# Similarity score calculation
similarity = |common_items| / max(|set1|, |set2|)

# Combined similarity score
score = (hashtag_similarity + domain_similarity + mentions_similarity) / 3
📈 Results

Successfully identified coordinated account clusters
Demonstrated temporal consistency in posting patterns
Validated findings through correlation matrix analysis
Confirmed group stability over extended time periods
Observed synchronized suspension patterns

🔬 Evaluation Methods

Domain similarity analysis
Hashtag correlation
Mention pattern analysis
Temporal consistency validation
Group stability assessment

🤝 Contributing
This is a research project, and we welcome contributions in the following areas:

Algorithm optimization
Feature enhancement
Dataset expansion
Validation methodology
Documentation improvements
