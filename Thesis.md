## Describe some recent developments in Artificial Intelligence (AI) and evaluate some of the ways of testing its reliability

## Introduction

Artificial Intelligence was first mentioned in the Dartmouth Summer Research Project. Initially, it was simply defined as a machine runs in a smart way, the way it behaves like a person (J. McCarthy, 1995). Now, it was defined as a system that learns from data and uses this learning to achieve specific goals and tasks (Andreas Kaplan, 2019). In fact, AI performs well in the lab, but may be overwhelmed when it encounters unknown data. Therefore, it is necessary to explore the reliability of AI. Regarding reliability testing, AI has many evaluation metrics such as threshold, MSE and AUC. Although threshold is a method commonly used by researchers, AUC is more suitable for testing AI reliability. This paper will first introduce the recent developments of AI, then explain the methods commonly used to test the reliability of AI, and finally evaluate these methods, and give conclusions and limitations.

## The recent developments in AI

AI has excellent development in many fields. However, this article will only select three thought-provoking examples of AI development to introduce.

**Stock market prediction :** With the advancement of technology, stock operations have changed from the initial on-the-spot transaction to online trading, and more and more stock market data has been collected, and stock market forecasts have gradually become possible. In other words, AI predicts future trends by learning stock market data. Recently, the financial expert system designed by Bin Weng, through learning stock market sequences and “knowledge bases” such as Google and Wikipedia, was able to successfully predict the AAPL stock movement for the next day with an accuracy of 85%.

**Target tracking:** Similarly, the object
tracking algorithm proposed by Li Bo Chang also combines time series and CNNs,
which greatly improves the robustness of object occlusion. This
innovative idea combines CNN's ability to learn feature representations with
time continuity and solves a series of problems that are difficult to track due
to external changes, such as blur, occlusion, and background clutter. At the
same time, the accuracy of tracking reached 85%, and the AUC score (one of the
popular ranking type indicators) increased by 14.9% compared to the traditional
KCF method.

**Tomato quality grading:** AI also has a positive impact on agricultural development. Mohammad Saber Iraji assists agricultural production by designing high-accuracy intelligent systems using different artificial intelligence methods. Her well-designed intelligent system can accurately score and classify tomato quality, achieving 95.5% accuracy, and performance is much better than other algorithms.

## Evaluate the ways testing AI reliability(Evaluation Metrics)

