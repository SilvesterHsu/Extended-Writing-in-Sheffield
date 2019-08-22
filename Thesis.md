## Describe some recent developments in Artificial Intelligence (AI) and evaluate some of the ways of testing its reliability

Artificial Intelligence was first mentioned in the Dartmouth Summer Research Project. Initially, it was cursorily defined as a machine runs in a brainy way, the way like a person acts (J. McCarthy, 1995). Now, Kaplan delicately defines AI as the capability of a system to construe the input data accurately,  to gain knowledge or skill from data and achieve particular goals and tasks by using this learning (Kaplan, 2019). In fact, AI performs well in the lab, but maybe overwhelmed when it encounters unknown data. Therefore, it is necessary to explore the reliability of AI. Regarding reliability testing, AI has many evaluation metrics such as threshold, MSE and AUC. Although the threshold is a method commonly used by researchers, this paper suggests AUC is more suitable for testing AI reliability. In this study, recent developments of AI will be discussed. Then methods commonly used for testing will be explained and evaluated. Finally, conclusions and limitations will be given in the end.

AI has a vigorous development and application in various fields.
**Stock market prediction:** Due to online trading and massive data collection, stock market forecasting has become possible. Specifically, AI is now able to predict future trends by learning stock market data. Recently, a financial expert system designed by Weng (Weng, 2017), through learning stock market sequences and “knowledge bases” such as Google and Wikipedia, is able to successfully predict the AAPL stock movement in the one-day ahead with an accuracy of 85%. While the algorithm may be correct, Weng's study is incomplete because they do not consider other sources of stock information. Henrique suggests that Weng's methods for obtaining, interpreting, and applying relevant data need to be explored. (Henrique, 2019). Besides, the reliability of the data sources is also suspectable because everyone can add information to Google and Wikipedia, and using such data may introduce false data and affect AI performance, or even get the opposite results compared with the ground truth. Batra argues despite Weng's accuracy of 85%, they don't define any mechanism to verify the external data, such as the data collected from Google or Wikipedia which can be unsubstantiated (Batra, 2018). Thus, although the stock market forecasting algorithm involving AI can achieve higher accuracy, a more comprehensive and reliable stock market database needs to be collected. **Target tracking:** Similarly, the object
tracking algorithm proposed by Li Bo Chang also combines time series and CNNs,
which greatly improves the robustness of object occlusion. This
innovative idea combines CNN's ability to learn feature representations with
time continuity and solves a series of problems that are difficult to track due
to external changes, such as blur, occlusion, and background clutter. At the
same time, the accuracy of tracking reached 85%, and the AUC score (one of the
popular ranking type indicators) increased by 14.9% compared to the traditional
KCF method (Chang, 2019).
**Tomato quality grading:** AI also has a positive impact on agricultural development. Iraji assists agricultural production by designing high-accuracy intelligent systems using different artificial intelligence methods. Her well-designed intelligent system can accurately score and classify tomato quality, achieving 95.5% accuracy, and performance is much better than other algorithms (Iraji, 2019).

The Turing test does not necessarily test the reliability of the AI. And there is no clear literature showing a specific correlation between the Turing test and AI stability. It seems possible that these results are due to the initial aim of the Turing Test is to imitate human rather than evaluating the quality of AI. According to Turing's study, he raised a question of whether machine can think and tries to convert this problem in a more concrete way and proposed an imitation game (Turing, 1950). Additionally, the Turing test has not been quantified and scored for AI reliability, more is cognitive research. Moor also asserts Turing test has little value in guiding research (Moor, 1976). 

Therefore, evaluation metrics, a more quantitative way, are needed to assess the reliability of intelligent systems. These metrics are suitable for assessing the reliability of an intelligent system. According to Hossin, the reliability of AI can be measured by the evaluation metric, which can be seen as a measurement tool (Hossin, 2015). Evaluation metrics can be divided into three main categories. In order to more easily compare the performance of various evaluation metrics, in Caruana's visionary research, he astutely divided the nine common evaluation metrics into precise three groups: threshold metrics, probability metrics, and rank metrics (Caruana, 2004).

In the above evaluation metrics, accuracy as one of the popular threshold metric is often used as the gold standard for researchers. More and more researchers use it as a standard for evaluating their own AI models because of its convenience. As Hossin observe, the threshold and ranking metric are the methods most commonly used by researchers to measure and summarize the ability of trained classifier when dealing with new data (Hossin, 2015). In Japkowicz review of the accuracy, he claims that researchers compare different intelligent system based on accuracy which counts the number of mistakes. This is the simplest and most directive evaluation measure (Japkowicz, 2006). However, there is a limit to only use accuracy as an evaluation criterion. Provost brings severe concerns about the use of accuracy. In his convincing work, he points out that accuracy is unsatisfactory both for making practical choices and for drawing scientific conclusions (Provost, 2011). Japkowicz mentions another argument for the accuracy's assessment ability is limited. He emphasizes the accuracy does not distinguish between the types of errors it makes, and in some cases ignoring the problem can lead to catastrophic consequences, such as cancer discrimination (Japkowicz, 2006). Thus, accuracy can not be the only one to evaluate the testing reliability of the AI system.

The probability metrics are mainly determined by the predicted value, it is a measure of the difference between the predicted value and the ground truth. Probability metrics give the most intuitive gap. According to Liu's research, probability metrics are extensively used in regression problems by calculating the bias and can be used to evaluate the reliability of intelligent systems. But he also points out that unlike other metrics, It cannot be compared directly to threshold metrics nor the ranking metrics (Liu, 2014). Probability metrics can still not effectively handle the task of assessing reliability. In Hossin's case study of probability metrics, he states that like the defect of accuracy, the probability metrics cannot effectively provide information between different classes. He also wisely realized that the probability metrics depends to a large extent on the weight of the initialization (Hossin, M, 2015). In some cases, the probability metrics may not matter. According to Caruana's finding, he reveals that in the case where the two evaluation metrics, threshold and ranking, perform extremely well, probability metrics may not perform well (Caruana, 2006).

The area under the curve (AUC) can be used to evaluate the stability of intelligent systems. It's not as simple as accuracy, it only reflects the overall performance of the system. In Flach's thoughtful research, he points out that it makes sense to use the area under the curve as a comprehensive performance indicator (Flach, 2019). Similar, Japkowicz emphasizes, unlike other metrics, its great advantage is that it separates the algorithm’s performance of each class, avoiding the shortcomings of the two evaluation metrics mentioned above (Japkowicz, 2006). Additionally, Hossin mentions the area under the curve (AUC) reflects the overall performance of the AI system. Nevertheless, he also accepts that although AUC is very good at evaluation and discrimination, the cost of calculating AUC is too high. However, considering its excellent ability in evaluating the reliability of an ai system, in today’s era of doubling computing power annually, such high computing consumption is affordable.

The measurement of AI system reliability may need to be further explored. Two interesting points are mentioned. On the one hand, in Flach's research, he suggests the ability of the AI system and the difficulty of the relationship between data are not likely to be observed directly (Flach, 2019). On the other hand, Liu's finding shows that excellent ai system does not necessarily need to achieve the best in every evaluation metric, as long as the system meets the performance requirements of an application (Liu, 2014). Thus, in some cases, the current evaluation metrics may not be able to test AI reliability directly.

In conclusion, these results suggest that the area under the curve (AUC) might be more suitable for testing AI reliability at present. This essay objectively analyzes three types of assessment metrics used to test AI reliability. Their advantages, disadvantages and reliability are analyzed separately. However, it still needs further investigation because it does not cover all aspects of testing the reliability of an intelligent system. Therefore, it may not be possible to take into account the stability of the AI test in other aspects.



### References

*   Batra, R., & Daudpota, S. M. (2018, March). Integrating StockTwits with sentiment analysis for better prediction of stock price movement. In *2018 International Conference on Computing, Mathematics and Engineering Technologies (iCoMET)* (pp. 1-5). IEEE.

*   Chang, L. B., Zhang, S. B., Sedky, M., Du, H. M., & Wang, S. Y. (2019). SiaMemory: Target Tracking. *Procedia Computer Science*, *154*, 146-153.

*   Caruana, R., & Niculescu-Mizil, A. (2005). *An empirical comparison of supervised learning algorithms using different performance metrics*. Technical Report TR2005-1973, Cornell University, 2005. Available at http://www. cs. cornell. edu/∼ alexn.

*   Caruana, R., & Niculescu-Mizil, A. (2004, August). Data mining in metric space: an empirical analysis of supervised learning performance criteria. In *Proceedings of the tenth ACM SIGKDD international conference on Knowledge discovery and data mining* (pp. 69-78). ACM.

*   Flach, P. (2019). Performance Evaluation in Machine Learning: The Good, The Bad, The Ugly and The Way Forward. In *33rd AAAI Conference on Artificial Intelligence*.

*   Henrique, Sobreiro, & Kimura. (2019). Literature review: Machine learning techniques applied to financial market prediction. *Expert Systems With Applications,* *124*, 226-251.

*   Hossin, M., & Sulaiman, M. N. (2015). A review on evaluation metrics for data classification evaluations. *International Journal of Data Mining & Knowledge Management Process*, *5*(2), 1.

*   Japkowicz, N. (2006, July). Why question machine learning evaluation methods. In *AAAI workshop on evaluation methods for machine learning* (pp. 6-11).

*   Kaplan, A., & Haenlein, M. (2019). Siri, Siri, in my hand: Who’s the fairest in the land? On the interpretations, illustrations, and implications of artificial intelligence. *Business Horizons*, *62*(1), 15-25.

*   Liu, Y. , Zhou, Y. , Wen, S. , & Tang, C. . (2014). A strategy on selecting performance metrics for classifier evaluation. *International Journal of Mobile Computing and Multimedia Communications,* *6*(4), 20-35.

*   McCarthy, J., Minsky, M. L., Rochester, N., & Shannon, C. E. (2006). A proposal for the dartmouth summer research project on artificial intelligence, august 31, 1955. *AI magazine*, *27*(4), 12-12.

*   Moor, J. H. (1976). An analysis of the Turing test. *Philosophical Studies*, *30*(4), 249-257.

*   Provost, F. , Fawcett, T. , & Kohavi, R. . (1997). The Case Against Accuracy Estimation for Comparing Induction Algorithms. *Fifteenth International Conference on Machine Learning*.

*   Saber, I. M. . (2018). Comparison between soft computing methods for tomato quality grading using machine vision. *Journal of Food Measurement and Characterization*.

*   Turing, A. M. (2009). Computing machinery and intelligence. In *Parsing the Turing Test* (pp. 23-65). Springer, Dordrecht.

*   Weng, B., Ahmed, M. A., & Megahed, F. M. (2017). Stock market one-day ahead movement prediction using disparate data sources. *Expert Systems with Applications*, *79*, 153-163.