# data-wizards
Submission regarding the Shaastra's L&amp;T Edutech Hackathon
The team data wizards have work on the Problem sttatement 3 of the Shaastra's L&T Hackathon, which was as following
Natural disasters and atmospheric anomalies demand remote monitoring and maintenance of naval objects especially big-size ships. For example, under poor weather conditions, prior knowledge about the ship model and type helps the automatic docking system process to be smooth. Thus, this set aims to classify the type of ships from an image data set of ships.

### Evaluation metrics
Kappa score = 0.951
Accuracy score = 0.962
```

from sklearn.metrics import accuracy_score, cohen_kappa_score
print(cohen_kappa_score(y_pred,y))
print(accuracy_score(y_pred,y))

0.951604915467337
0.9627319257837492
```
