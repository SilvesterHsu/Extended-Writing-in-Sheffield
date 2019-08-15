## Describe some recent developments in Artificial Intelligence (AI) and evaluate some of the ways of testing its reliability

Artificial Intelligence was first mentioned in the Dartmouth Summer Research Project. Initially, it was cursorily defined as a machine runs in a brainy way, the way like a person acts (J. McCarthy, 1995). Now, Andreas Kaplan delicately defines AI as a system's capability to construe the input data correctly,  to learn from data and achieve particular goals and tasks by using this learning (Andreas Kaplan, 2019). In fact, AI performs well in the lab, but maybe overwhelmed when it encounters unknown data. Therefore, it is necessary to explore the reliability of AI. Regarding reliability testing, AI has many evaluation metrics such as threshold, MSE and AUC. Although threshold is a method commonly used by researchers, this paper suggests AUC is more suitable for testing AI reliability. In this study, recent developments of AI will be discussed. Then methods commonly used for testing will be explained and evaluated. Finally conclusions and limitations will be given in the end.

AI has a vigorous development and application in various fields.
**Stock market prediction :** Due to online trading and massive data collection, stock market forecasting has become possible. Specifically, AI is now able to predict future trends by learning stock market data. Recently, a brainy financial expert system designed by Bin Weng (Bin Weng, 2017), through learning stock market sequences and “knowledge bases” such as Google and Wikipedia, was able to successfully predict the AAPL stock movement in the one-day ahead stock price/volume with an accuracy of 85%.
However, B. Henrique implys that methods for obtaining, interpreting, and applying relevant data need to be explored. (B. Henrique, 2019) **Target tracking:** Similarly, the object
tracking algorithm proposed by Li Bo Chang also combines time series and CNNs,
which greatly improves the robustness of object occlusion. This
innovative idea combines CNN's ability to learn feature representations with
time continuity and solves a series of problems that are difficult to track due
to external changes, such as blur, occlusion, and background clutter. At the
same time, the accuracy of tracking reached 85%, and the AUC score (one of the
popular ranking type indicators) increased by 14.9% compared to the traditional
KCF method.
**Tomato quality grading:** AI also has a positive impact on agricultural development. Mohammad Saber Iraji assists agricultural production by designing high-accuracy intelligent systems using different artificial intelligence methods. Her well-designed intelligent system can accurately score and classify tomato quality, achieving 95.5% accuracy, and performance is much better than other algorithms.

By using evaluation metrics, the reliability of AI can be easily quantified. According to Hossin, the reliability of AI can be measured by the evaluation metric, which can be seen as a measurement tool. Moreover, he also asserts that almost all types of threshold, probability and ranking metrics could be used to assess the performance and capability of classifiers (Hossin, M, 2015). 

In the above evaluation metrics, accuracy as one of the popular threshold metric is often used as the gold standard for researchers, however, there is a limit to only use accuracy as an evaluation criterion. As Hossin observe, the threshold and ranking metric are the methods most commonly used by researchers to measure and summarize the ability of trained classifier when dealing with new data (Hossin, M, 2015). More and more researchers use it as a standard for evaluating their own AI models. However, Provost brings severe concerns about the use of accuracy. He strongly argues that accuracy is unsatisfactory both for making practical choices and for drawing scientific conclusions.
