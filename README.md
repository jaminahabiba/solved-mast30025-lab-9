Download Link: https://assignmentchef.com/product/solved-mast30025-lab-9
<br>
<ol>

 <li>Recall Question 5 from the Week 8 lab. In a manufacturing plant, filters are used to remove pollutants. We are interested in comparing the lifespan of 5 different types of filters. Six filters of each type are tested, and the time to failure in hours is given in the dataset filters (on the website, in csv format).

  <ul>

   <li>Is <em>µ </em>− <em>τ</em><sub>1 </sub>+ <em>τ</em><sub>5 </sub>estimable?</li>

   <li>Is estimable?</li>

   <li>In the week 8 lab you were asked to find two solutions to the normal equations. Verify thatthey produce the same estimate of <em>τ</em><sub>4</sub>− <em>τ</em><sub>5</sub>.</li>

   <li>Do your two solutions produce the same estimate of 2<em>µ </em>+ <em>τ</em><sub>1</sub>?</li>

   <li>Write down the quantities corresponding to: (i) the lifespan of type 1 filters; (ii) the differencebetween the lifespans of type 2 and type 3 filters; (iii) the amount by which type 4 filters outlive the average filter; (iv) the expected total time to failure of a set of filters containing one of each type.</li>

  </ul></li>

</ol>

Verify directly that all of these quantities are estimable, and estimate them.

<ul>

 <li>Fit a lm model using treatment contrasts (the default). This gives estimates of <em>µ</em><sub>1</sub><em>,µ</em><sub>2</sub>− <em>µ</em><sub>1</sub><em>,…,µ</em><sub>5</sub>− <em>µ</em><sub>1</sub>. Use these to estimate ¯<em>µ,µ</em><sub>1</sub>− <em>µ,…,µ</em>¯ <sub>5</sub>− <em>µ</em>¯. Check your answers by fitting a contr.sum model.</li>

</ul>

<ol start="2">

 <li>According to the Gauss-Markov theorem, the estimator for <strong>t</strong><em><sup>T</sup></em><em>β </em>with the lowest variance is <strong>t</strong><em><sup>T</sup></em><strong>b</strong>. Assuming that <strong>t</strong><em><sup>T</sup></em><em>β </em>is estimable, show that this variance is <em>σ</em><sup>2</sup><strong>t</strong><em><sup>T</sup></em>(<em>X<sup>T</sup>X</em>)<em><sup>c</sup></em><strong>t</strong>. 3. For the one-way classification model, with <em>n<sub>i </sub></em>observations in group <em>i</em>, show that</li>

</ol>

<em>k</em>

<em>SS<sub>Reg </sub></em>:= <strong>y</strong>ˆ<em><sup>T</sup></em><strong>y</strong>ˆ = <strong>y</strong><em><sup>T</sup>X</em>(<em>X<sup>T</sup>X</em>)<em><sup>c</sup>X<sup>T</sup></em><strong>y </strong>= <sup>X</sup>(¯<em>y<sub>i</sub></em>)<sup>2</sup><em>n<sub>i</sub>.</em>

<em>i</em>=1

<ol start="4">

 <li>Consider the one-way classification model with 3 levels (<em>k </em>= 3). Find all estimable quantities of the form.</li>

 <li>Consider the two-way classification model</li>

</ol>

<em>y</em><em>ij </em>= <em>µ </em>+ <em>τ</em><em>i </em>+ <em>β</em><em>j </em>+ <em>ε</em><em>ij.</em>

Suppose that you have at least one sample from each combination of factor levels.

Treatment contrasts for the first factor are defined here as <sup>P</sup><em><sub>i </sub>a<sub>i</sub>τ<sub>i</sub></em>, where <sup>P</sup><em><sub>i </sub>a<sub>i </sub></em>= 0. Show that these treatment contrasts are estimable.

1