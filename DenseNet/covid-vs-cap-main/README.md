# DenseNet121 trained on COVIDx CX3 and Pnemonia CXR using GCP A100 40 GB GPU

Go to the Heroku app [HERE](https://covid-vs-cap.herokuapp.com/docs).

Accuracy on train: 0.9879046082496643

Loss on train: 0.03283184394240379

Accuracy on test: 0.9839955568313599

Loss on test: 0.05539374426007271

Correct predictions: 3559

Wrong predictions: 65


| Group  | Precision | Recall | F1 score | Support |
|--------|-----------|--------|----------|---------|
| COVID  | 0.98      | 0.99   | 0.98     | 1628    |
| NORMAL | 0.98      | 0.98   | 0.98     | 1574    |
| CAP    | 1.00      | 0.97   | 0.98     | 422     |

