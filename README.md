# HybriDroid

This project presents a hybrid approach, called HybriDroid, for automatic detecting data leakage vulnerabilities within a bundle of apps, allowing the end-users to check the apps installed on their device for data leakage vulnerabilities. It combines static- and dynamic-analysis methods to overcome the code coverage, dynamic feature, and scalability challenges in detecting. The evaluation results show  that HybriDroid is effective in analyzing the data leakage vulnerability both inter- and intra-component communication. It achieves a high precision in DroidBench 3.0 test suite.

# Evaluation Results 

&Chi; represents false positive; &Omicron; represents false negative; &radic; represents true positive;

| test cases    | DroidGuard    | IccTa  | HybriDroid |
| ------------- |:-------------:| ------:|:-----------|
| DynamicBoth1  | right-aligned | $1600 |&radic;
| DynamicSink1  | centered      |   $12 |&radic;
| DynamicSource1| are neat      |    $1 |&radic;
