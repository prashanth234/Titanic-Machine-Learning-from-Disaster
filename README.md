# Titanic-Machine-Learning-from-Disaster

This project is about predicting whether a passenger is survived or not based on his information.

I have explored the data, performed feature engineering and trained it on some  keras and tensorflow algorithms whose results are shown below.

<table>
    <thead>
      <tr>
        <th>Models</th>
        <th>Train-Accuracy</th>
<!--         <th>Validation-Accuracy</th> -->
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>DecisionTreeClassifier</td>
            <td>89.560000</td>
<!--             <td>89.560000</td> -->
        </tr>
        <tr>
            <td>RandomForestClassifier</td>
            <td>89.560000</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>KNeighborsClassifier</td>
            <td>86.200000</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>Neural network</td>
            <td>83.501684</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>LinearSVC</td>
            <td>79.120000</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>SVC</td>
            <td>78.230000</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>Perceptron</td>
            <td>74.970000	</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>GaussianNB</td>
            <td>74.300000</td>
<!--             <td></td> -->
        </tr>
    </tbody>
</table>

Overall Accuracy on test data when used DecisionTreeClassifier: 0.78947
