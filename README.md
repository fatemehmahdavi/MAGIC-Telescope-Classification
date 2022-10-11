## Classification of MAGIC Gamma Telescope Dataset
There are high energy particles hitting the Gamma Telescope and there's a detector that records certain patterns of how light hits the camera and I used properties of those patterns in order to predict what type of particle caused the radiation, wether it was a Gamma particle or Hadron.

I compared four different Classification Algorithms on the MAGIC Gamma Telescope Dataset from the UCI Machine Learning Repository to classify the particles :

Naive Bayes Classifier

Logistic Regression

upport Vector Machine (SVM)

K-Nearest Neighbour (KNN)

## Attribute Information:

1. fLength: continuous # major axis of ellipse [mm]
2. fWidth: continuous # minor axis of ellipse [mm]
3. fSize: continuous # 10-log of sum of content of all pixels [in #phot]
4. fConc: continuous # ratio of sum of two highest pixels over fSize [ratio]
5. fConc1: continuous # ratio of highest pixel over fSize [ratio]
6. fAsym: continuous # distance from highest pixel to center, projected onto major axis [mm]
7. fM3Long: continuous # 3rd root of third moment along major axis [mm]
8. fM3Trans: continuous # 3rd root of third moment along minor axis [mm]
9. fAlpha: continuous # angle of major axis with vector to origin [deg]
10. fDist: continuous # distance from origin to center of ellipse [mm]
11. class: g,h # gamma (signal), hadron (background)

