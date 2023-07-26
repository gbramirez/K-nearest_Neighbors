# K-nearest Neighbors 
🏘️🧑‍🤝‍🧑🏘️🧑‍🤝‍🧑
## Business Question
<p> Can k-Nearest Neighbors be used to predict whether a patient will be readmitted to the hospital within 30-days of discharge?</p>

## Goal
<p>Using relevant labeled data points, develop a model to determine which patientrs will be readmitted to the hospital within 30 days of discharge.</p>

## Relevant Data Points
<p>The following data points from previously readmitted patients are relevant to the analysis:</p>
<ul>
  <li>The patient's age</li>
  <li>Whether the patient has been diagnosed with high blood pressure</li>
  <li>Whether the patient has been diagnosed with a stroke</li>
</ul>

## How k-Nearest Neighbors Works
<p>K-Nearest Neighbors(KNN) is used to find the most appropriate label for unlabeled data based on the label of nearest data points. According to <em>Practical statistics for data scientists</em>, KNN finds records in the data set that have "similar predictor values" and create a new record from the values. The KNN process will then "find the average" of the first set of records and "predict that average for the new record" (Bruce, Bruce, & Gedeck. 2020). The way KNN classifies related data makes it the best choice to identify variables closely related to patient readmittance.</p>

## Assumption of KNN
<p>KNN assumes that if two data points are close to each other, they must be related. KNN would also assume that the closer two data points are in proximity, the more closely related they must be.</p>

## Expected Outcomes
<ul>
  <li>A classification model will be created using KNN.</li>
  <li>The model will classify which data points can be used to predict patient readmittance.</li>
  <li>A stakeholder recommendation will be created using the results of the analysis.</li>
</ul>

## Packages and Libraries
  | Package | Justification |
  | :--- | :--- |
  | Pandas | Create and manipulate data frames for the analysis. <br> Manipulating the data frame is a critical part of the data cleaning process.|
  |  MatPlotLib |Create charts and reports on the data for visualization.<br> Charts and reports are vital to any data analysis project.|
  | SciKitLearn | Scale, test, train, and fit the data.<br> The package also includes the KNearestNeighbors tools.|
  | NumPy | Read, process, and evaluate the data. <br>The package also allows the creation of arrays for the classification process.|

<sub>Social preview photo by <a href="https://unsplash.com/@jontyson?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jon Tyson</a> on <a href="https://unsplash.com/s/photos/neighbors?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  </sub>
