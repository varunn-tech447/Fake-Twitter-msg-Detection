# FakeNewsTracker: Analyzing and Detecting Fake News on Twitter

## Overview

**FakeNewsTracker** is a project focused on identifying and analyzing
potentially misleading or fake news shared on Twitter (now X). The
project explores how natural language processing (NLP), machine
learning, deep learning, and tweet-related metadata can be used to
detect misinformation and help users make more informed decisions.

The project emphasizes timely detection because misleading posts can
spread rapidly across social media. It also considers visualization and
user awareness as supporting measures for understanding and limiting
misinformation.

## Objectives

-   Detect and analyze potentially fake news shared on Twitter.
-   Reduce users' exposure to misleading information and support trust
    in online content.
-   Explore text, image, and metadata-based analysis.
-   Assess detection performance using precision, recall, and F1-score.
-   Support the understanding of misinformation trends through
    visualizations.

The presentation identifies **85% detection precision** as a target
metric.

## Project Scope

-   **Platform:** Twitter.
-   **Language:** English-language tweets.
-   **Data considered:** Tweet text, images, and metadata.
-   **Analysis:** Text preprocessing, feature extraction, machine
    learning/deep learning-based classification, and trend
    visualization.

The presentation notes that language variation, account differences,
ambiguous content, sarcasm, and emerging misinformation topics can limit
detection performance.

## Proposed Workflow

1.  **Data collection**\
    Collect tweets using relevant keywords, hashtags, or user accounts.
    The presentation describes API-based filtering as one way to focus
    the dataset.

2.  **Preprocessing**\
    Clean tweet content by removing URLs, mentions, and special
    characters.

3.  **Feature extraction**\
    Extract useful signals such as sentiment, tweet length, and
    user-engagement metrics. The project also considers user behavior
    and network propagation.

4.  **Detection and classification**\
    Explore machine learning classifiers such as Support Vector Machines
    (SVM) and Random Forest, along with deep learning models such as
    Long Short-Term Memory (LSTM) networks.

5.  **Evaluation**\
    Assess the detection approach using precision, recall, and F1-score,
    and validate predictions against real Twitter data and manual
    verification.

6.  **Visualization**\
    Use visual representations such as heatmaps and timelines to help
    identify misinformation trends, spikes, and possible sources.

## Detection Methods

The project presentation discusses the following methods and signals:

-   **Natural Language Processing (NLP):** Analyze textual patterns in
    tweets.
-   **Support Vector Machine (SVM):** A supervised learning approach for
    classification.
-   **Random Forest:** An ensemble learning approach for classification.
-   **Long Short-Term Memory (LSTM):** A deep learning model considered
    for text-related pattern analysis.
-   **Metadata and engagement signals:** Consider tweet length,
    sentiment, user engagement, and user behavior.
-   **Network and propagation analysis:** Examine how content spreads
    across the platform.

These are the methods explored or proposed in the presentation; the
presentation does not provide source code or a reproducible
implementation specification.

## Evaluation Metrics Reported

The presentation gives the following performance figures:

  Metric                                                   Reported value
  ------------------------------------------------------ ----------------
  Precision                                                           82%
  Recall                                                              78%
  F1-score                                                            80%
  Identification accuracy on real Twitter datasets                    79%
  Alignment with manual verification and user feedback                81%

The presentation also identifies a **22% false-negative rate** as a
limitation when dealing with emerging topics.

> **Note:** The 85% precision figure is stated as a project target,
> while 82% precision is reported in the evaluation slide. These figures
> represent a target and a reported result, respectively.

## Visualization and Mitigation

The project presentation highlights:

-   Heatmaps and timelines for exploring misinformation trends.
-   A user-friendly interface with straightforward navigation and
    customizable views.
-   Automated detection combined with human moderation.
-   User awareness and education to help people recognize
    misinformation.
-   Collaboration and information sharing between social media
    platforms.

## Limitations and Future Improvements

Potential limitations identified in the presentation include:

-   The current scope is limited to English-language tweets.
-   Sarcasm, ambiguous wording, and rapidly changing topics can affect
    classification.
-   Emerging misinformation can be missed.
-   Differences in languages and accounts make reliable detection more
    difficult.

Suggested improvement areas include incorporating temporal analysis and
user-behavior patterns, strengthening validation, and combining multiple
information sources.

## References and Fact-Checking Resources

The presentation lists the following resources:

-   [Snopes](https://www.snopes.com/)
-   [PolitiFact](https://www.politifact.com/)
-   [Media Bias/Fact Check](https://mediabiasfactcheck.com/)
-   [Lead Stories](https://leadstories.com/)
-   [The Washington Post Fact
    Checker](https://www.washingtonpost.com/news/fact-checker/)
-   Research on fact-checking recommendation systems and
    misinformation-detection models.
-   A multilingual dataset of fact-checked COVID-19 news from 92
    websites (as referenced in the presentation).

## Repository Contents

This README describes the project presented in the accompanying project
presentation. Add the implementation files, dataset information,
notebooks, and screenshots to this repository as they become available.

## Disclaimer

This project is intended for academic exploration of misinformation
detection. Automated classification should not be treated as definitive
proof that a post is true or false. Important claims should be checked
against reliable sources and human fact-checking.
