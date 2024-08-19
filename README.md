<h1>Fuel Efficiency Analysis Using One-Way and Two-Way ANOVA</h1>

<h2>Overview</h2>
<p>This project investigates the factors influencing fuel efficiency in cars, focusing on the number of engine cylinders and the interaction between transmission type and engine configuration. Using real-world data from the <code>mtcars</code> dataset in R, we apply statistical methods, including one-way and two-way ANOVA, to determine the impact of these variables on miles per gallon (mpg).</p>

<h2>Problem Statement</h2>
<p>The study aims to explore whether the number of engine cylinders and the combination of transmission type with engine configuration significantly affect fuel efficiency in cars.</p>

<h2>Dataset</h2>
<p>We use the <code>mtcars</code> dataset, which contains data on various car models, including:</p>
<ul>
    <li><strong>cyl</strong>: Number of cylinders (4, 6, or 8)</li>
    <li><strong>mpg</strong>: Miles per gallon (fuel efficiency)</li>
    <li><strong>am</strong>: Transmission type (0 = automatic, 1 = manual)</li>
    <li><strong>vs</strong>: Engine configuration (0 = V-shaped, 1 = straight)</li>
</ul>

<h2>Analysis</h2>
<h3>One-Way ANOVA</h3>
<p>We analyze the effect of the number of cylinders on fuel efficiency using one-way ANOVA.</p>

<h3>Two-Way ANOVA</h3>
<p>We extend the analysis to evaluate the combined effect of transmission type and engine configuration on fuel efficiency using two-way ANOVA.</p>

<h3>Key Findings</h3>
<ul>
    <li>Cars with fewer cylinders (4 cylinders) generally have better fuel efficiency.</li>
    <li>Both transmission type and engine configuration significantly impact fuel efficiency, with manual transmission and straight engine configuration yielding the best results.</li>
    <li>No significant interaction effect between transmission type and engine configuration on fuel efficiency.</li>
</ul>

<h2>Visualizations</h2>
<p>The analysis includes visual representations such as boxplots and scatter plots to illustrate the differences in fuel efficiency across different groups.</p>

<h2>Conclusion</h2>
<p>The findings provide valuable insights for car manufacturers and consumers, highlighting the importance of engine design and transmission type in achieving optimal fuel efficiency.</p>
