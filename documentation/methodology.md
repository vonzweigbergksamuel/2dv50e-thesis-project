# Methodology

We will complete these tests with the following face detection model: MTCNN. That is the same our related work article uses.

We need to normalize the dataset to be able to use it with the `DeepFace` framework. In this way we have the name of the person and also a person can have multiple images.

Suggestion: 
- 📁 photos
  - 📷 person-name_001.jpg
  - 📷 person-name_002.jpg
  - 📷 person-name_003.jpg
  - 📷 ...

One of the related work articles have split the data set into 50/50 for training and testing. The seccond article of the related work uses 5,000 images out of 13,000 images. However it is still unkown if they trained on 13,000 images and tested on 5,000 images. We will use either use a 80/20 split or 70/30 split. In this way we will get much more use cases. We will get an image of a person that aldready exist in the DB, And we will also get images on persons that does not exist in the DB. In our DB we will also have images of persons that will not be in the testing set. This way we will get a more realistic test.

Should we run it multiple times with the same split?

## Plan

1. Normalize the dataset to be able to use it with the `DeepFace` framework.
2. Split the dataset into training and testing.
3. Run the tests with the `DeepFace` framework.
4. Calculate the accuracy, sensitivity, precision, F1-score and confusion matrix.
5. Analyze the results.

## Technical Plan

1. Read in every image in the dataset and place it in a Dataframe, with image and name of the person.
2. Split the dataset into training and testing.
3. Place every image in the correct folder. 
4. Run the tests with the `DeepFace` framework.
5. Save the results in an array.
6. Get the confusion matrix from the results.
7. Calculate the accuracy, sensitivity, precision, F1-score.
8. Analyze the results.

## Scores

To be able to calculate the scores correct we need to save every result in an array which we later can send to the confusion matrix. The confusion matrix is a needed to calculate the scores correct.

*We can use scikit-learn to get the training and testing set. We can also use the confusion matrix from scikit-learn.*

TP = True Positive
TN = True Negative
FP = False Positive
FN = False Negative

[Read more about the Confusion Matrix](https://www.geeksforgeeks.org/machine-learning/confusion-matrix-machine-learning/)

### Sensitivity / Recall

Hur ofta systemet korrekt nekar igenkänning när ansiktet inte tillhör någon i databasen.

```markdown
Sensitivity=TP/(TP+FN)
```

### Specificity

Hur ofta systemet korrekt nekar igenkänning när ansiktet inte tillhör någon i databasen.

```markdown
Specificity=TN/(TN+FP)
```

### Accuracy

Om det finns många fler negativa än positiva fall kan accuracy vara hög även om modellen är dålig på det viktiga.

```markdown
Accuracy=(TP+TN)/(TP+TN+FP+FN)
```

### Precision

Hur ofta systemet har rätt när det säger att två ansikten matchar.

```markdown
Precision=TP/(TP+FP)
```

### F1-score

Den visar hur väl modellen presterar överlag, utan att gynna bara precision eller bara sensitivity.

```markdown
F1=2∗(Precision∗Sensitivity)/(Precision+Sensitivity)
```