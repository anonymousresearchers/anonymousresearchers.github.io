## Summary

This website contains our source code and datasets used in the submission for ASE 2020.

### Source Code

The six customizable components in our framework and all data structures are implemented in Python, totaling
1,300 SLOC. [[Link]](https://drive.google.com/file/d/14NMWaDFK03hmULENhCoQ0g2XaA8ZH7xp/view?usp=sharing)

### Test Results
The results of each of the 7 million prediction models are stored as `final_data.RData` file, including the following information. [[Link]](https://drive.google.com/file/d/1FMuvddoRjXpo0q_8NKrA0rFKt96dura3/view)
- the anonymized user ID
- the number of requests sent by the user
- the number and percentage of the repeated requests
- the prediction algorithm used
- the statistics of the Test Result (i.e., the output of the Test Engine as shown in Algorithm 1, Line 17): *cache* size, the number of requests in the *hit set*, the number of requests in the *miss set*, the number of *prefetched* requests, the number of *hit* requests, the number of *miss* requests
- the accuracy results: static precision, static recall, dynamic recall
- the runtime of training the prediction model and evaluating the model

### Data Analysis R Script
All the data analyses are performed through R scripts based on the Test Results stored in `final_data.RData`, totaling 500 SLOC. [[Link]](https://drive.google.com/file/d/1JN94KycYOG-xGkxsjkp2WipgMI-kgUxq/view?usp=sharing)


