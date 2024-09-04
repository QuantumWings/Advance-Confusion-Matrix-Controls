<h1>Advanced confusion matrix console</h1>
<h2>Introduction</h2>
<p>The Advanced Confusion Matrix Console is a powerful, interactive tool designed for machine learning and data science researchers. It provides an intuitive interface to explore and understand the performance of classification models, especially in handling confusion matrices, various performance metrics, and decision boundaries. This tool combines theory and practice, allowing users to adjust parameters in real time and see results immediately, thereby gaining a deep understanding of the behavior of machine learning models. </p>

Check out the demo [here](https://quantumwings.github.io/Advance-Confusion-Matrix-Controls/).

<h2>Main functions</h2>
<ol>
<li>Confusion matrix parameter adjustment: Use the sliders to dynamically adjust the values ​​of true positives (TP), true negatives (TN), false positives (FP) and false negatives (FN). </li>
<li>Calculation of multiple performance indicators: Instantly calculate and display accuracy, precision, recall, F1 score and other indicators. </li>
<li>Multiple classification algorithms supported: including SVM, logistic regression, decision tree, random forest and other algorithms. </li>
<li>3D data visualization: Use Plotly.js to create interactive 3D scatter plots to display classification results and decision boundaries. </li>
<li>Visualization of decision boundaries: Show and hide decision boundaries, and adjust the size of boundary points. </li>
<li>Color customization: allows users to customize the colors of positive and negative categories. </li>
<li>Animation effect: Provides rotation animation of 3D graphics to enhance the data exploration experience. </li>
<li>Data regeneration: Allows users to adjust the number of data points and regenerate data. </li>
</ol>
<h2>Installation and Setup Guide</h2>
<h3>Environmental requirements</h3>
<ul>
<li>Modern web browser (latest version of Chrome, Firefox, Safari or Edge recommended)</li>
<li>Network connection (for loading external libraries)</li>
</ul>
<h3>How to use</h3>
<ol>
<li>Download the entire HTML file locally. </li>
<li>Open the HTML file using a modern web browser. </li>
<li>No additional installation steps are required, the page automatically loads all necessary scripts and styles. </li>
</ol>
<h2>Instructions for use</h2>
<h3>Operation steps</h3>
<ol>
<li>Adjust confusion matrix parameters: Use the sliders to adjust the values ​​of TP, TN, FP, and FN. </li>
<li>Select performance metrics: Select the performance metrics to display from the drop-down menu. </li>
<li>Select a classification algorithm: Select a different classification algorithm from the algorithm drop-down menu. </li>
<li>Adjust decision boundaries: Use switches to show/hide decision boundaries and adjust boundary point sizes. </li>
<li>Custom Color: Use the color picker to change the color of the positive and negative classes. </li>
<li>Start animation: Click the "Animate Rotation" button to start the rotation animation of 3D graphics. </li>
<li>Regenerate data: Adjust the number of data points and click the "Regenerate Data" button. </li>
</ol>
<h3>Example</h3>
<p>Try the following to explore the tool's capabilities:</p>
<ol>
<li>Add the TP slider to 750 and watch the accuracy change. </li>
<li>Switch the algorithm to "Logistic Regression" and observe the changes in the decision boundary. </li>
<li>Enable "Highlight Decision Boundary Points" and adjust the point size. </li>
<li>Change the positive color to green and the negative color to red. </li>
<li>Start the rotation animation and observe the data distribution from different angles. </li>
</ol>
<h2>Project structure</h2>
<ul>
<li>index.html: Contains all the necessary HTML, CSS, and JavaScript code for an interactive interface to build and display the confusion matrix. </li>
</ul>
<p>Main components:
- ConfusionMatrixModel: Responsible for data processing and calculation.
- ConfusionMatrixView: handles UI elements and user interaction.
- ConfusionMatrixController: coordinates Model and View and handles business logic. </p>
<h2>Contribution Guidelines</h2>
<p>If you would like to contribute to this project, please follow these steps:
1. Fork this repository and clone it to the local environment.
2. Create a new branch for development (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push the changes to your branch (git push origin feature-branch).
5. Submit a Pull Request. </p>
<h2>Authorization information</h2>
<p>This project is licensed under the terms of the <a href="https://opensource.org/licenses/MIT">MIT</a> license. </p>
<h2>Contact information</h2>
<p>If you have any questions or suggestions, please contact the project maintainer: quantumwingslab@gmail.com</p>
<h2>Additional information</h2>
<p>This tool is suitable for education, research and practical application scenarios. It can help users better understand the working principle of classification algorithms and provide an intuitive reference for model selection and optimization. We welcome feedback and contributions from the community to make this tool even more complete and useful. </p>
