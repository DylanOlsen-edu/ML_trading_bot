# Machine Learning Trading Bot
In this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.
The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.
Instructions:
* Use the starter code file to complete the steps that the instructions outline. The steps for this Challenge are divided into the following sections:
* Establish a Baseline Performance
* Tune the Baseline Trading Algorithm
* Evaluate a New Machine Learning Classifier
* Create an Evaluation Report
## What impact resulted from increasing or decreasing the training window?
Answer: I sliced out dates ranging past December 2019 due to Covid, and National Lockdown. This helped the machine learn without the unpredictabilty of a pandemic. 
## What impact resulted from increasing or decreasing either or both of the SMA windows?
Answer: Increasing the short window from 4 to 12, and the long window from 100 to 142 helped the SVM model out perform the actual returns.
## Evaluation Report
Report: I am pleased with the adjusted outcome of the svm.SVC model. It tracked along actual returns until it learned enough to take the leap and made amazing gains. I experimented with the AdaBoostRegression model. Although it perfrom great initially, when price rose it failed to make the adjustment and "flatlined". I tried LogisticRegression first but did not perform better than the SVM model. Would like to see how the SVM model produces with more information over time.
