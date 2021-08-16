# Soccer ds Project
This project has been submitted as the QSTP final project held during the summer of 2021

## Problem Statement
You are appointed as the Sporting Director of a newly established football club that aims to be competitive among the top European clubs of the world. You have been assigned to make signings for the main lineup squad of 11 players that must match up to those standards but you have been allotted only with a limited budget of 150 million Euros for the same. You are also required to predict the annual wage of the squad that you have signed from the same dataset.

## Dataset Used:
This project uses FIFA 2020 dataset available on Kaggle by Stefano Leone

Link: https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset

## Methodolgy
This problem's solution can be solved using the methodology of 'MoneyBall' introduced by the book, Moneyball: The Art of Winning an Unfair Game by Michael Lewis. The book argues that there are statistics of players that are very important for their performance but are generally overlooked. This method uses those overlooked attributes to sign players who are undervalued.

For feature selection, this project uses Mutual info regression to calculate the dependency of the players with their overall rating to detect the most important features

Then, a normalized score is generated for the players according to their performance in those features which is used to shortlist the players and a value-for-money squad is chosen by considering other external factors like age, position, etc.,

As final part of the problem, the dataset is used to predict the wages of the players using XGReggressor with pipeline processing

## Result:
A competitive squad has been signed with limited budget
