# Survival-Analysys--HR-RR-OD
Hazard Ratio, Relative Risk, Odds Ratio. Survival analysys in R.

You can find data [here](http://theta.edu.pl/wp-content/uploads/2021/10/Dane.csv)


Survival analysis, also known as time-to-event analysis, is a statistical method used to analyze the time until an event of interest occurs. The event could be the occurrence of a specific outcome or the failure of a particular subject. This type of analysis is commonly applied in medical research, economics, engineering, and other fields where the timing of events is important.

Survival analysis is particularly useful when studying the duration until an event occurs, and when there may be censoring in the data. Censoring occurs when the event of interest has not occurred for some subjects by the end of the study or when subjects are lost to follow-up. Survival analysis takes into account both the observed event times and the censored data.

The key concept in survival analysis is the survival function, which represents the probability of an event not occurring (i.e., survival) beyond a given time point. The survival function is often estimated using a non-parametric estimator, such as the Kaplan-Meier estimator. The survival function can be visualized using a survival curve, which shows the probability of survival over time.

Survival analysis also involves the hazard function, which describes the rate at which events occur at a specific time, given that the subject has survived up to that point. The hazard function provides insights into the instantaneous risk of experiencing the event of interest.

Covariates or predictors can be incorporated into survival analysis using regression models such as the Cox proportional hazards model. These models allow for the examination of the relationship between covariates and the hazard of the event, while accounting for censoring.

Some common applications of survival analysis include:

Medical research: Analyzing the time until the occurrence of a disease, death, or relapse after treatment.
Customer churn analysis: Studying the time until customers stop using a service or cancel a subscription.
Failure analysis: Investigating the time until failure of a mechanical component or system.
Time-to-event analysis in clinical trials: Assessing the effectiveness of a treatment based on the time until a specific outcome, such as disease progression or recurrence.
Survival analysis provides valuable insights into the time dynamics of events, allowing researchers to estimate probabilities, identify risk factors, and make predictions about the future occurrence of events of interest.
