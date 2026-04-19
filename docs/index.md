# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
- I used the provided system metrics dataset with requests, errors, and latency values.

### Signals
- I used error rate and average latency as key signals to evaluate system health.

### Experiments
- I lowered the thresholds for anomaly detection (error rate to 0.03 and latency to 30.0) to make the system more sensitive.

### Results
- The system detected significantly more anomalies when using stricter thresholds.

### Interpretation
- This suggests the system may be experiencing performance issues more frequently than expected. Lower thresholds help catch potential problems earlier, but may also increase false alarms.
