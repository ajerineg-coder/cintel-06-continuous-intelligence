Continuous Intelligence Portfolio – Addie Gemmell
Overview

In this project, I built and modified a continuous intelligence pipeline to monitor system performance using real-time metrics. The goal was to detect anomalies and better understand how system behavior changes over time.

Techniques Used
Signal design (error rate and average latency)
Anomaly detection using thresholds
Rolling monitoring concepts
Drift awareness through changing system behavior
Dataset

The dataset included system performance metrics such as:

Requests
Errors
Total latency
Signals & Monitoring

I created key signals to evaluate system health:

Error rate (errors / requests)
Average latency (total latency / requests)
Custom Modifications

I created a custom pipeline file (custom_continuous_intelligence.py) where I:

Lowered the error rate threshold to 0.03
Lowered the latency threshold to 30.0
Results & Insights

After lowering the thresholds:

The system flagged more anomalies
More potential performance issues were identified

This showed that small changes in thresholds can significantly impact detection.

Conclusion

This project showed how important it is to tune thresholds correctly in continuous monitoring systems.
