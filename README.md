# AndroSafe
AndroSafe is an android based mobile app which is using flask backend, which a user can use to safeguard their devices from the most prevalent malwares such as malicious apps or phishing links.


Used machine learning approach for classification between malignant and benign samples for both applications and web-links.

- Intially started with finding the right labelled dataset from online sources which is catered to our need.

- Then extracted features from the samples using our feature_extration funtion and deciding on the most inferentials features to be used for classification.

- Mainly used two models for classification i.e Random forest(RF) and state vector machines(SVMs) as they yielded highest accuracy.

- Then incorporated it all in a flask app so as to have a working UI to it.

- Android studio was used to test out the functinality in an android environment.

  - UI is simple, starting with a load page asking the user to choose between classification for apps or urls.
  - User is then prompted to upload a file which needs to be classified.
  - Our model classifies the sample as benign or malignant using one of the two classifiers.


Steps for executions given in other file.
