---
layout: post
title:  "Machine Learning Capstone Assessing Meaning of School"
categories: code
---

Executing text mining techniques in R studio. 

# PROJECT BACKGROUND
Wesleyan University Professor Steven Stemler and Dr. Damian Bebell of Boston College spearhead an ongoing project to determine the purpose of schooling through qualitatively analyzing school mission statements. Their work aims to address the fundamental question of why school is significant in the first place. Considering that the goal of a mission statement is to capture the overall essence and purpose of a given institution, these statements are utilized to determine the values held by each given school. Raters were trained with a coding rubric to spot the presence of particular constructs in each mission statement; this rubric detailed the constructs that appeared at high rates (ex, emotional development), or that were judged somehow significant (ex, physical education).

As their research is still ongoing, additional school information is being gathered for data analysis. The project also looks to expand internationally, with opportunity to derive much insight from the information readily available on school websites at the global scale. However, classifying this information is significantly time consuming for the missions project team, due to the necessity of human raters individually categorizing each statement.

# WHERE I COME IN
Utilizing machine learning approaches on the available missions data, my capstone aims to develop a tool optimizing and automating such classification. This project will revisit the presence of particular constructs in the body of missions data, reaffirming the coding instrument. Additionally, an exploration will be conducted for the best classification approach for the data at hand, and wrapped in an application that can later be utilized by the lab on new data for coding at a significantly reduced amount of time. This capstone is supervised by Professor Pavel Oleinikov.

# METHODOLOGY
Verification of Existing Rubric. The existence of different topics will be explored utilizing the unsupervised learning technique Latent-Dirichlet Allocation through the gensim Python library, with optimization performed through the minimization of KL divergence.

Classification. A supervised text classification approach will subsequently be used with the topics optimized in the previous step.

Automation. Finally, this project will wrap the machine learning algorithm in a stand alone application (using Orange, a Python based software) to make automated classification more accessible for the lab going forward.
