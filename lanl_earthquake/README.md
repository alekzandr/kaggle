# General Information

This Kaggle compeition sets out to answer when an earthquake will happen based on real-time seismic data produced in labratory.

<a href="https://www.kaggle.com/c/LANL-Earthquake-Prediction">Link to Competition</a>

<h3>Submission History</h3>
<ol>
  <li>2.871</li>
  <li>1.653</li>
  <li>1.534 - Kernel Version 13</li>
  <li>1.848 - Kernel Version 16</li>
</ol>
  
<h3>Notes</h3>
My current model uses a single LightGBM model. Some top public kernels use RNNs, Support Vector Regressors, and CatBoosting or an ensemble of these. This is worth exploring. //1-14-2019//

Implemented an SVR model. Cross Validation MAE on validation set reached 1.3782. The Version 13 LightGBM model had a CV MAE of 1.4526 on the validation set. //1-14-2019//

Single SVR model, Version16, returned a testing MAE score of 1.848. This is a lot worse than anticipated. Next step is to create an ensemble of the LightGBM and SVR.



<h3>References</h3>
Public kernels worth looking into:

<ul>
  <li><a href="https://www.kaggle.com/jazivxt/aftershock">Aftershock</a> by jazivxt</li>
  <li><a href="https://www.kaggle.com/mayer79/rnn-starter">RNN starter</a> by Michael Mayer</li>
  <li><a href="https://www.kaggle.com/artgor/earthquakes-fe-more-features-and-samples">Earthquakes FE. More features and samples</a> by Andrew Lukyanenko</li>
</ul>
