1. Introduction:<br />
   1.1 Problem Statement
      Customer churn is a critical challenge for businesses, as losing customers can significantly impact revenue and growth.         The objective of this project is to build a machine learning model that can predict customer churn based on historical data.<br />
   1.2 Objective:
       The primary objective of this project is to develop a model that can accurately predict customer churn. This will help businesses identify at-risk customers and take proactive measures to retain them.<br />
     <br />
2. Dataset Overview:
     The dataset used in this project contains information about customers, including their demographics, usage patterns, and whether they churned or not. It consists of the following features:

        customerID: Unique customer identifier.
        gender: Customer's gender .
        SeniorCitizen: Indicates senior citizen status .
        Partner: Indicates if customer has a partner .
        Dependents: Indicates if customer has dependents .
        tenure: Number of months with the company.
        PhoneService: Indicates phone service .
        MultipleLines: Indicates multiple lines .
        InternetService: Type of internet service .
        OnlineSecurity: Online security service .
        OnlineBackup: Online backup service .
        DeviceProtection: Device protection service .
        TechSupport: Tech support service .
        StreamingTV: Streaming TV service .
        StreamingMovies: Streaming movies service .
        Contract: Contract type .
        PaperlessBilling: Paperless billing .
        PaymentMethod: Payment method .
        MonthlyCharges: Monthly charges.
        TotalCharges: Total charges.
        Churn: Indicates if customer churned.
        
3. Methodology:<br />
    3.1 Data Preprocessing: Handled missing values and encoded categorical variables.<br />
    3.2 Data Visualization: Exploring variables and checking for insights<br />
    3.3 Model Selection and Training:Selected Logistic Regression, Random Forest, and Gradient Boosting as the models for churn prediction.
    <br />
    
4. Results:<br />
    4.1 Model Performance<br />
    
        Logistic Regression:<br />
            Accuracy: 0.8169<br />
            Precision: 0.6726<br />
            Recall: 0.5566<br />
            F1-Score: 0.6091<br />
            AUC: 0.732<br />
            
        Random Forest:<br />
            Accuracy: 0.7979<br />
            Precision: 0.6344<br />
            Recall: 0.4991<br />
            F1-Score: 0.5587<br />
            AUC: 0.7<br />
        
        Gradient Boosting:<br />
            Accuracy: 0.8146<br />
            Precision: 0.677<br />
            Recall: 0.5288<br />
            F1-Score: 0.5938<br />
            AUC: 0.721<br />
            <br />
    4.2 Comparison of Models:<br />
        -Logistic Regression performed the best overall, with the highest accuracy, recall, and F1-score.<br />
        -Gradient Boosting also performed well but had slightly lower recall compared to Gradient Boosting.<br />
        -Random Forest had the lowest performance metrics among the three models.<br />
