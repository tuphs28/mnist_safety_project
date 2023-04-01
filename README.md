# Towards a "Safe" MNIST Classifier
### Exploring Tradeoffs Between Safety Metrics

Repo for some experiments I did investigating tradeoffs between various ways in which an image clasifier can be "safe" (e.g. robustness, calibration, ability to detect OOD inputs). This project begun as a final project for the Machine Learning Safety Scholars summer school and was extended in the Autumn of 2022.

Summary of results: minor tradeoffs seem to exist between various safety metrics, but model ensembles seem able to ameliorate the worst of this.

main.ipybn: notebook with experiments
Machine_learning_safety_scholars_final_project.pdf: report covering findings in greater detail
Models/ : folder containing various models used in experiments
Results/ : folder containing results of various experiments
