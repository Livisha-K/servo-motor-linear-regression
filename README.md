<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Servo Motor Mechanism Prediction using Linear Regression</h1>

<p>This repository contains a project for predicting the behavior of a servo motor mechanism using linear regression. The dataset provides configurations of the servo motor mechanism with attributes such as motor type, screw type, proportional gain, velocity gain, and a class label.</p>

<h2>Dataset Description</h2>
<ul>
  <p>Data Source: Kaggle - Servo Motor Mechanism Dataset | https://www.kaggle.com/datasets/sakshisatre/servo-motor-mechanism-dataset</p>  
  <li><strong>Motor:</strong> Type of motor used ('A', 'B', 'C', 'D', 'E').</li>
    <li><strong>Screw:</strong> Type of screw used ('A', 'B', 'C', 'D', 'E').</li>
    <li><strong>Pgain:</strong> Proportional gain setting for the servo motor.</li>
    <li><strong>Vgain:</strong> Velocity gain setting for the servo motor.</li>
    <li><strong>Class:</strong> Class label representing the performance or behavior of the servo mechanism.</li>
</ul>

<h2>Steps to Implement</h2>
<ol>
    <li>Load and explore the dataset.</li>
    <li>Preprocess the data by handling missing values and encoding categorical variables.</li>
    <li>Split the dataset into training and testing sets.</li>
    <li>Train a linear regression model to predict the class label based on motor type, screw type, Pgain, and Vgain.</li>
    <li>Evaluate the model using Mean Squared Error (MSE) and R-squared metrics.</li>
    <li>Make predictions for new configurations of the servo motor mechanism.</li>
</ol>

<h2>Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>Pandas</li>
    <li>NumPy</li>
    <li>Scikit-learn</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
</ul>


<h2>Contributions</h2>
<p>Contributions, questions, and feedback are welcome. Contact me at <a href="mailto:livisha83003@gmail.com">livisha83003@gmail.com</a> for inquiries or collaboration opportunities.</p>

</body>
</html>
