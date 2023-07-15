---
title:
permalink: /writing/
layout: "single"
classes: wide
author_profile: true
---

I’m a PhD student at Harvard University studying Business Economics, a joint degree that combines the Economics Department’s PhD program with support from the Business School. I have also worked as a financial analyst at the Consumer Financial Protection Bureau, a research assistant at NYU Stern, and a contractor with the Core Data Science team at Facebook.

If you'd like to learn more about me, you can find my CV [here][dr-cv].

[dr-cv]:{{ site.baseurl }}{% link assets/files/Dominic_Russel_CV.pdf %}


# <center> Working Papers </center>
- - -

**Counterfactual Risk Assessments under Unmeasured Confounding** (with [Amanda Coston][acoston] and [Edward Kennedy][ekennedy]). Updated Feb 2023. <br/>
<small>[ <a href="#/" onclick="visib('risk-assessments-confounding')">Abstract</a> | [Draft][risk-ass-confounding] ] </small>

<div id="risk-assessments-confounding" style="display: none; text-align: justify; line-height: 1.2" ><small>
Statistical risk assessments inform consequential decisions such as pretrial release in criminal justice, and loan approvals in consumer finance.
Such risk assessments make counterfactual predictions, predicting the likelihood of an outcome under a proposed decision (e.g., what would happen if we approved this loan?).
A central challenge, however, is that there may have been unmeasured confounders that jointly affected past decisions and outcomes in the historical data. 
This paper proposes a tractable mean outcome sensitivity model that bounds the extent to which unmeasured confounders could affect outcomes on average. 
The mean outcome sensitivity model partially identifies the conditional likelihood of the outcome under the proposed decision, popular predictive performance metrics (e.g., accuracy, calibration, TPR, FPR), and commonly-used predictive disparities. We derive their sharp identified sets, and we then solve three tasks that are essential to deploying statistical risk assessments in high-stakes settings.
First, we propose a doubly-robust learning procedure for the bounds on the conditional likelihood of the outcome under the proposed decision.
Second, we translate our estimated bounds on the conditional likelihood of the outcome under the proposed decision into a robust, plug-in decision-making policy.
Third, we develop doubly-robust estimators of the bounds on the predictive performance of an existing risk assessment.
We apply our methods to analyze a real-world credit-scoring task, illustrating how varying assumptions on unmeasured confounding leads to substantive changes in the credit score's predictions and evaluations of its predictive disparities.
</small><br><br/></div>

[risk-ass-confounding]: https://arxiv.org/pdf/2212.09844.pdf
[ekennedy]: https://www.ehkennedy.com/




[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>