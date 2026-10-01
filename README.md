# econ3916-lab04-anomaly-detection
Robust Statistics -- Automated Anomaly Detection
Objective
I examined how summary statistics and anomaly-detection methods respond to skewed housing data and extreme observations.
Methodology
- I analyzed 20,640 observations from the California Housing dataset.
- I calculated the mean, median, trimmed mean, standard deviation, IQR, and MAD.
- I manually implemented Tukey Fences to identify price outliers.
- I applied Isolation Forest to detect unusual combinations of housing features.
- I compared the observations flagged by the two methods.
- I introduced 5% artificial corruption and measured how each summary statistic changed.
Key Findings
Tukey Fences and Isolation Forest flagged different observations because they evaluate different forms of unusual behavior. After 5% contamination, the mean increased by 67.13%, while the median increased by only 3.56%. This showed that the median was much less affected by extreme values.
