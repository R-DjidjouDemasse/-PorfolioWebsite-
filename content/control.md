+++
comments = false
date = 2020-05-11T22:55:19+02:00
draft = false
noauthor = true
share = false
title = "Optimal control of infectious diseases"
type = "page"

+++



<html>
<head>
<style>
img {
  max-width: 100%;
  height: auto;
}
</style>
</head>
<body>
<h2>HBV (Hepatitis B Virus)</h2>
<img src="/uploads/controlHBV.jpg" alt="controlHBV" width="1000" height="300">
<p> One of the characteristics of HBV transmission is the age structure of the host population and the vertical transmission of the disease. The infection is transmitted directly from infected mother to an embryo, fetus, or baby during pregnancy or childbirth (the perinatal infection). Further, symptomatic and asymptomatic HBV infections are age-dependent and the risk of asymptomatic HBV infection is inversely related to age at infection. By formulating an age-structured model for the transmission dynamics of HBV with differential infectivity: symptomatic and asymptomatic infections and using optimal control theory, we find that an optimal control strategy is a combination of immunization of young adults (at least susceptible with the age less than 5 years old) and treatment of HBV symptomatic infections. We also observe that mass vaccination in infants increases the average age of infection in unimmunized individuals and shifts the average age at infection to older age groups ([Djidjou-Demasse et al.](https://link.springer.com/content/pdf/10.1007/s00285-015-0952-6.pdf)).</p>
</body>
</html>

<html>
<head>
<style>
img {
  max-width: 100%;
  height: auto;
}
</style>
</head>
<body>
<h2>HIV and impact of ART (antiretroviral therapy) drop out</h2>
<img src="/uploads/HIV-ART.jpg" alt="controlHBV" width="1000" height="300">
<p> By considering the specific mechanism of HIV, we derive a model structured in three successive stages: primary infection, long phase of latency without symptoms and AIDS. Each HIV stage is stratified by the duration for which individuals have been in the stage, leading to a continuous age-structure model. This model is suitable for the specific mechanisms of ART, which is the use of HIV medicines to slow down the progress of the
infection. In fact, ART help people with HIV live longer by extending the time spent in a given HIV stage. Interventions strategies, as function of time, are include into the model: the proportion of individuals, h1, under ART at HIV stage 1 and the proportion, h2, under ART at HIV stage 2 (which were not under ART at HIV stage 1). The performance of control startegies is estimated by assessing the total number of AIDS cases during the control period relatively to AIDS cases without any strategy (values above 1 indicate that intervention strategy has negative impact on the epidemics outbreak). We find that  before introducing ART, investigations should be addressed to know whether the host population is well sensibilized on ART treatment or not. These investigations will probably help in reducing the probability of treatment drop out ([Ba et al.](https://hal.archives-ouvertes.fr/hal-02357239/document)).</p>
</body>
</html>


<html>
<head>
<style>
img {
  float: left;
}
</style>
</head>
<body>
<h2>COVID-19</h2>
<p><img src="/uploads/controlCOVID.jpg" alt="ControlCovid" style="width:400px;height:400px;margin-right:15px;">
Here we explore the best strategy to implement while waiting for pharmaceutical interventions (either vaccine or treatment). We seek a solution minimizing deaths (D_COVID, directly due the infection  or D_SAT, due to the saturation of the healthcare capacity by severe cases Is) and  costs due to the implementation of the control strategy itself. We find that such a solution leads to an increasing level of control with a maximum reached near the 16th month of the epidemics and a steady decrease until vaccine deployment. The average containment level is approximately 50\% during the 25-months period for vaccine deployment. This strategy strongly outperforms others with constant or cycling allocations of the same amount of resources to control the outbreak. This work opens new perspectives to mitigate the effects of the COVID-19 pandemics, and be used as a proof-of-concept in using mathematical modelling techniques to enlighten decision making and public health management in the early times of an outbreak ([Djidjou-Demasse et al.](https://www.medrxiv.org/content/10.1101/2020.04.02.20049189v1.full.pdf)). </p>

<img src="/uploads/LifeCycleAgeCovid.jpg" alt="LifeCycleAgeCovid" width="700" height="200">
<p>This first model assumes a heterogeneous population in relation of the COVID-19 epidemic, whereas the severity of SARS-COV-2 is known to be at least age specific. The infectivity of an individual with SARS-COV-2 affects the spread of the epidemic and varies according to the age of the infection, i.e., the time that has elapsed since that individual has been infected. We propose a model with a double continuous structure by host age and time since infection.  By applying optimal control theory to our age-structured model, we identify a solution minimizing deaths and costs associated with the implementation of the control strategy itself. This strategy consists in rapidly intervening in older populations to decrease virus speed, before progressively alleviating this control. Interventions in the younger population can occur later if the cost associated with the  intervention is low. This wider intervention aims at suppressing the epidemic instead of only protecting the most vulnerable individuals ([Richard et al.](https://www.medrxiv.org/content/10.1101/2020.06.23.20138099v2.full.pdf)). </p>
</body>
</html>





