# YouTube-Comments-Romantic-dishonesty (Niyathembana na Comment Mining Project)
A collection of YouTube comments on videos where romantic dishonesty is revealed. 
Overview
This repository contains the code and data for the comment mining project on the Niyathembana na series from the CMTV YouTube channel. This channel aims to upload and premiere at least one video each day, generating a wealth of comments for our investigation.

However, not all videos in the Niyathembana na series have comments enabled. Videos tagged as suitable for children are automatically restricted from receiving comments. This limitation affects the volume and variety of comments available for analysis.

Objectives
The main objective of this project is to mine and analyse viewer comments from selected videos in the Niyathembana na series. This analysis focuses on English comments to understand viewer engagement and feedback.

Data Collection Process
Video Selection:

Curated all videos with more than three hundred thousand views.
Compiled these videos into a dedicated playlist on YouTube.
Comment Extraction:
Developed a script to extract comments and comment responses from the playlist.
Ensured no identifying information was included in the dataset.
Saved the resulting comments to an Excel spreadsheet file.

Dataset Overview:
Collected a total of eighty-one thousand one hundred and forty-eight comments.
Focused on comments largely in English using the South African Language Identification Tool (SA-LID).
Identified all eleven official written languages of South Africa in the comments.
Extracted forty-eight thousand nine hundred and seventy-one English comments, containing six hundred and seven thousand three hundred and nineteen words, over a hundred thousand emojis, and nearly a quarter of a million punctuation marks.

Tools and Methods
YouTube API: For accessing and extracting comments from the Niyathembana na series videos.
SA-LID (South African Language Identification Tool): For identifying the languages of comments at the line level.
Excel: For saving and managing the extracted comments data.

Data Analysis
The focus of the analysis is on the English comments. According to the qualitative analysis conducted by Ngcungca et al. (2024), the "unsure" category in SA-LID often contains emoji-filled statements, slang, and filler words. For ease of analysis, we concentrated on the clearly identified English comments.

Repository Structure
scripts/: Contains the script used for extracting comments from the YouTube playlist.
data/: Includes the Excel spreadsheet file with the extracted comments.
analysis/: Contains notebooks and scripts for analysing the comments data.
Results and Discussion
The discussion in this project focuses on the English comments extracted from the Niyathembana na series videos. With forty-eight thousand nine hundred and seventy-one comments, this dataset provides a substantial basis for analysing viewer engagement and feedback.

References
Ngcungca, et al. (2024). Qualitative Analysis of the SA-LID Tool. Journal of South African Language Studies.

Contact
For any questions or further information, please contact Dr. Sibeko at johanness@mandela.ac.za.
