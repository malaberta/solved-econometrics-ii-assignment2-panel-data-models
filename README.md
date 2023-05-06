Download Link: https://assignmentchef.com/product/solved-econometrics-ii-assignment2-panel-data-models
<br>
<strong>Econometrics II: Assignment 2, Panel data models</strong>

The dataset NLSY2000RC V2.dta(.csv) is a paneldataset on male workers, working at least 30 hours a week. It has data for the years 1980-1994, 1996, 1998 and 2000. It contains the following variables:

<table width="353">

 <tbody>

  <tr>

   <td width="105">ID</td>

   <td width="20">:</td>

   <td width="228">personal identifier</td>

  </tr>

  <tr>

   <td width="105">TIME</td>

   <td width="20">:</td>

   <td width="228">year − 1980</td>

  </tr>

  <tr>

   <td width="105">EARNINGS</td>

   <td width="20">:</td>

   <td width="228">hourly wage</td>

  </tr>

  <tr>

   <td width="105">AGE</td>

   <td width="20">:</td>

   <td width="228">age</td>

  </tr>

  <tr>

   <td width="105">AGESQ</td>

   <td width="20">:</td>

   <td width="228">age squared</td>

  </tr>

  <tr>

   <td width="105">S</td>

   <td width="20">:</td>

   <td width="228">years of schooling</td>

  </tr>

  <tr>

   <td width="105">ETHBLACK</td>

   <td width="20">:</td>

   <td width="228">black ethnicity (dummy variable)</td>

  </tr>

  <tr>

   <td width="105">URBAN</td>

   <td width="20">:</td>

   <td width="228">living in urban area</td>

  </tr>

  <tr>

   <td width="105">REGNE</td>

   <td width="20">:</td>

   <td width="228">region north-east</td>

  </tr>

  <tr>

   <td width="105">REGNC</td>

   <td width="20">:</td>

   <td width="228">region north-central</td>

  </tr>

  <tr>

   <td width="105">REGW</td>

   <td width="20">:</td>

   <td width="228">region west</td>

  </tr>

  <tr>

   <td width="105">REGS</td>

   <td width="20">:</td>

   <td width="228">region south</td>

  </tr>

  <tr>

   <td width="105">ASVABC</td>

   <td width="20">:</td>

   <td width="228">index test score</td>

  </tr>

 </tbody>

</table>

The variable ASVABC is a composite test score for skills like arithmetic reasoning, word knowledge, paragraph comprehension. A higher value of ASVABC goes together with a higher test score. It is generally considered to be a good indicator for ability. It is measured only once, upon entering the panel, and therefore it is constant over time.

A researcher is interested in estimating the effect of schooling on the hourly wage. A basic equation is ln<em>EARNINGS</em><em>it </em>= <em>α</em>0 + <em>α</em>1<em>S</em><em>it </em>+ <em>α</em>2<em>AGE</em><em>it </em>+ <em>α</em>3<em>AGESQ</em><em>it </em>+ <em>X</em><em>it</em>0 <em>γ </em>+ <em>U</em><em>it</em>

where <em>X </em>includes remaining variables.

<ol>

 <li>First use pooled OLS to check the impact of including and excluding ASVABC on the estimate of <em>α</em><sub>1</sub>. Present and explain the result.</li>

</ol>

The researcher is asked to analyze whether returns to schooling, as measured by the parameter <em>α</em><sub>1</sub>, is different for workers with a black ethnicity. A difference in returns to schooling by ethnicity is sometimes interpreted as an indication of discrimination on the labour market. Two basic ways to model heterogeneity in the schooling parameter by ethnicity are (1) including a cross effect of schooling and ethnicity and (2) estimating separate equations by ethnicity.

<ol start="2">

 <li>Perform a pooled OLS analysis to obtain insight in the heterogeneity of returns to schooling by ethnicity. Present the results and comment on the outcomes: what are the conclusions based on this?</li>

</ol>

So far, the panel nature of the data has hardly been exploited. Random effects estimation can improve efficiency of the estimates compared to pooled OLS.

<ol start="3">

 <li>Perform the analysis for heterogenous schooling effects using the random effects model. Present the results and compare the outcomes with the pooled OLS results obtained before. Interpret the outcomes.</li>

</ol>

Alternatively, panel data can be exploited to perform fixed effects (or: within group) estimation.

<ol start="4">

 <li>A priori, would you plead for using fixed effects estimation or random effects estimation? Explain your answer.</li>

 <li>Apply the fixed effects estimator to analyze the heterogenous schooling effect. Interpret the outcomes.</li>

 <li>Fixed effects estimation may not be as efficient as random effects estimation, but is robust to correlation between regressors and the random effect. Can we perform a Hausman test in this context? Perform the test you propose.</li>

 <li>Perform Mundlak estimation of the model. Present the results of estimation and test for the joint sigificance of the within-group means.</li>

 <li>What are your overall conclusions from the analysis of heterogeneity in returns to schooling by ethnicity?</li>

 <li>To gain insight in the impact of nonresponse and attrition, the researcher applies a variant of the Verbeek and Nijman-test (see lecture slides). He defines the dummy variable <em>d<sub>i </sub></em>which is 1 if the individual is in the panel for more than 5 waves, and is zero otherwise. Apply the Verbeek and Nijman test with this definition of <em>d<sub>i </sub></em>(otherwise equal to the definition at the lecture slides). Draw conclusions and address practical problems you possibly met in implementing the test.</li>

</ol>