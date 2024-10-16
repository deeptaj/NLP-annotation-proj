# Introduction
This notebook presents an overview of classifying the humor levels of Ted Talks. This project was designed as a final project for Info 159: Natural Language Processing at UC Berkeley, taught by Professor Behrang Mohit.
# Overview
Our task attempts to solve the question: “Are ted talks funny?” We analyzed a dataset found on Kaggle called "[TED-Talks topic models](https://www.kaggle.com/code/adelsondias/ted-talks-topic-models/input?select=transcripts.csv)" that contained transcripts of previous ted talks. We then broke down these transcripts into segments and annotated them using our guidelines to build a functioning model. This can be beneficial in a couple ways:
(1) It enhances educational content: Teachers can immediately have an understanding of the level of seriousness of a TED Talk to better prepare educational materials for students. The content can be hand-picked for different audiences (i.e. older vs younger students).
(2) It improves the quality of Ted Talks: TED organizers and speakers can use the insights gained from analyzing humor in TED Talks to improve the overall quality and effectiveness of future talks, making them more engaging and memorable for the audience.

We created a BERT classifier with variations such as an ALBERT classifier, baynesian optimization, augmented data/backtranslation, and layer adjustments to optimize accuracy.

