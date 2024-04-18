Insurance fraud occurs when individuals or organizations make false claims to an insurance company with the intention of obtaining benefits or financial compensation they are not entitled to [1]. Insurance fraud can take many forms, such as:

(i) Fabricating accidents or injuries to collect insurance payments

(ii) Falsifying insurance claims by exaggerating damages or losses

(iii) Submitting forged documents or receipts to support claims

(iv) Providing false information about insured properties or individuals

(v) Failing to disclose all relevant information about the claim

Insurance fraud is an illegal act that can harm insurance companies. Insurance companies need to take steps to detect and prevent fraud, such as thoroughly investigating claims [1].

Various conventional efforts are also made such as blacklists and in-depth investigations to detect fraud, but these efforts tend to incur significant costs. Therefore, the use of machine learning is proposed as a decision support system to predict the potential for insurance fraud as a binary classification scenario with imbalanced class composition [2]. The issue of imbalanced classes is addressed by the Imbalance-XGBoost method through two modified objective functions from the XGBoost method, namely the weighted function and focal loss [3]. The performance of the Imbalance-XGBoost model with both objective functions will be compared with XGBoost without any handling, XGBoost with oversampling, and XGBoost with data weighting using the scale_pos_weight parameter as standard imbalance class handling.

Additionally, this project will also present decision rules, which are interpretations of decision tree approximations to detect and classify insurance fraud. Each classification made by the decision tree can be associated with the corresponding decision path. Furthermore, the hierarchical structure of the model as a whole can be easily visualized or explained to users with various levels of expertise [4]. Specifically, Gradient Boosting Decision Trees (GBDT) are an example of the type of model that will be used. GBDT models are considered state-of-the-art in many classification challenges as part of the XGBoost solution [5].

PROBLEM STATEMENT

1. What is the performance of the Imbalance-XGBoost model with weighted function and focal loss in detecting insurance fraud?

2. How does the performance of both Imbalance-XGBoost models compare to XGBoost without imbalance class handling, XGBoost with oversampling, and XGBoost with data weighting as standard imbalance class handling?

3. What are the classification results of the XGBoost interpretation in the form of decision paths (decision rules)?

OBJECTIVES

1. Analyze the performance of the Imbalance-XGBoost model with weighted function and focal loss in detecting insurance fraud.

2. Compare the performance of both Imbalance-XGBoost models to XGBoost without imbalance class handling, XGBoost with oversampling, and XGBoost with data weighting as standard imbalance class handling.

3. Create classifications from the XGBoost interpretation in the form of decision paths to detect insurance fraud.
