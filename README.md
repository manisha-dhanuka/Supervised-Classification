<p align="center"> 
  <img src="images/android app.jpg" alt="" width="200px" height="200px">
</p>
<h1 align="center"> Andoid App Authenticator</h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://certificates.almabetter.com/en/verify/99124074888726"> AlmaBetter Certificate </a> </h5>

<p align="center"> 
<img src="images/Malware.jpg" alt="" height="382px">
</p>

<p>I have developed a Malware detector program in Python which classifies given apps as benign or malware using the Gradient Boosting Algorithm.</p>

# :floppy_disk: Project Files:
This project contains three directories, one model as follows:
<ul>
 <li><b> notebooks: </b> This Folder contains .ipynb for the project</li><br>
 <li><b> data: </b> This folder contains</li>
	<t><b>final_data.csv : </b>The data used for modelling purposes.</t>
  <li><b> reports: </b> This contains the powerpoint presentation and technical documentation related to the project.<br>
<li><b> model: </b> The model is joblib file of Gradient Boosting model. </li>
 </ul>
 
<h2> :book: Gradient Boosting </h2>
Gradient Boosting is based on boosting algorithm of ensemble techniques. s a machine learning algorithm that is used for both regression and classification tasks. It is an ensemble method that combines multiple weak learners (usually decision trees) to create a strong predictive model. The algorithm works by iteratively adding new models to the ensemble, with each new model correcting the errors made by the previous models.<br><br>
<b>1. </b> The algorithm starts by initializing the ensemble with a simple model.The initial predictions of this model are made based on the average value of the target variable (for regression) or the class distribution (for classification).<br>
<b>2. </b> The next step involves computing the residuals. For regression tasks, the residuals represent the errors, while for classification tasks, they represent the negative gradients of the loss function.<br>
<b>3. </b>In this step, a new weak learner, often another decision tree, is trained to predict the residuals or negative gradients computed in the previous step.<br>
<b>4. </b>The newly trained weak learner is added to the ensemble with a weight that determines its contribution to the final prediction. The weight is typically determined using an optimization algorithm, such as gradient descent, which minimizes the loss function with respect to the ensemble's predictions and the new weak learner's predictions.<br>
<b>5. </b>Steps 2 to 4 are repeated iteratively until a predefined number of weak learners have been added to the ensemble or until a certain stopping criterion (e.g., maximum number of iterations) is met.

<h2> :books: References</h2>
<ul>
	<li> Google: www.google.com</li>
	<li> Analytics Vidhya: https://www.analyticsvidhya.com/blog/2021/09/gradient-boosting-algorithm-a-complete-guide-for-beginners/</li>
</ul>
