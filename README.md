# FinancialDistress

Over the past decades, financial distress prediction has been an important topic of finance
that gains significant interest from many researchers. Initially, statistical models were
used to predict financial distress based on financial ratios. After that, machine learning
techniques have been developed and applied in many studies. However, there is no
consistent theory that one specific technique is better than another (Hung and Chen,
2009; Wang et al., 2014). Through empirical studies, researchers across various countries
persist in seeking the most effective way to assess the financial health of a firm. Overall,
increasing model accuracy, choosing appropriate variables, improving the prediction time
and interpreting models continue to be main problems in financial distress prediction.
Bellovary et al. (2007) reviewed 165 financial distress studies and an interesting question
has been raised ‘why do we continue develop new techniques in financial distress
prediction while many of which achieved good performance?’. The researchers suggested
that future research should investigate in the application of these models and refine them
if necessary.

The most challenges aspect of machine learning models are their lack of interpretability.
In Viet Nam, banks and credit institutions have to filter the credit requirers and clarify
their assessment of financial risks for corporate borrowers. However, du Jardin (2018)
concluded that artificial intelligent cannot be used as a tool for decision-making because
they cannot be explained. Besides, Son et al. (2019) implied that while machine learning
models’ accuracy is not significantly higher than statistical models, their results cannot be
interpreted. This leads to the reason why they are not used in practice. The most
challenging aspect of machine learning models is their lack of interpretability. In Viet
Nam, banks and credit institutions have to filter the credit requirers and clarify their
assessment of financial risks for corporate borrowers. However, du Jardin (2018)
concluded that artificial intelligent cannot be used as a tool for decision-making because
they cannot be explained. Besides, Son et al. (2019) implied that while machine learning
models’ accuracy is not significantly higher than statistical models, their results cannot be
interpreted. This leads to the reason why they are not used in practice.

As a result, many studies have been conducted to explain machine learning models
using interpretability methods. Overall, there are three kinds of explainable method:
interpretable models, neural network interpretation and model-agnostic methods. In
recent years, many studies have used model-agnostic methods such as Local Interpretable
Model-agnostic Explanations (LIME), Partial Dependence Plot (PDP), and Shapley
Additive Explanations (SHAP). Among these techniques, SHAP stands out due to its
strong theoretical foundation and ability to explain clearly the machine learning models at
both local and global levels. Currently, there are studies of machine learning corporate
financial distress prediction models using SHAP (Perboli and Arabnezhad, 2021; Sigrist
and Hirnschall, 2019; Zhang et al., 2022). However, these studies remain some gaps.
Some studies compare the efficiency of different models and use SHAP to explain the
importance of features to the prediction result but the local explanation for each ratio in a
company has not been examined. Moreover, financial ratios in some studies were not
clearly identify, leading to no further comparison with financial distress theories.
In Vietnam’s emerging economic landscape, enterprises are confronted with huge risk
of financial challenges. Vietnam is a rapidly developing economy, which faces challenges
such as bad debts and market volatility. Besides, Vietnam also has some specific factors
such as dependence on exports and foreign investment, along with changes in financial
policies. These characteristic makes forecasting financial distress in Vietnam different
from others. According to General Statistics Office of Vietnam, in 2023, there are 89,060
businesses that temporarily ceased operations due to financial difficulties, increases
20.7% compared to 2022. As figure 1, the number of financial distress firms in Vietnam
increased significantly in the past 8 years and these financial distress situations
underscore the critical need for effective solutions.

To address knowledge gap, our study will explain both the individual impacts and the
combined impacts of the financial ratios on the predictive ability of the model and
compare the results with the previous studies. Secondly, we assess the performance of
machine learning compared to traditional models, giving the reasons to believe in
applying machine learning models of financial distress prediction in Vietnam. Finally, we
clarify our variables, explain the performance of these factors using financial theories and
compare with previous studies.
Overall, this paper used both machine learning and traditional models for financial
distress prediction with a sample of 1177 listed firms from 6 sectors (Industry, Mining,
Logistic, Forestry and fisheries, Trade and services, Construction) over the period of
2020-2022, with a total of 3531 firms to predict the financial situation of the firm in
2023.

Our study has significant contributions to both theorical foundation and Vietnam
economy. Firstly, we analyze financial distress prediction based on the overall importance
of ratios with SHAP visualization. Secondly, our study using SHAP to investigate in
impacts of financial ratios in each firm. Finally, by clarifying important factors, our study
both improves transparency of predicting models and lays the foundation for intergrating
modern techniques into financial risk management system.
