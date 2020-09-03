History of coronary heart disease increased the mortality rate of COVID-19 patients: a nested case-control study
================================================================================================================

[Read the medRxiv preprint](https://doi.org/10.1101/2020.03.23.20041848)

China has experienced an outbreak of a novel human coronavirus
(SARS-CoV-2) since December 2019, which quickly became a worldwide
pandemic in early 2020. There is limited evidence on the mortality risk
effect of pre-existing comorbidities for coronavirus disease 2019
(COVID-19), which has important implications for early treatment. This
study aims to evaluate the risk of pre-existing comorbidities on
COVID-19 mortality, and provide clinical suggestions accordingly. Under
the nested case-control design, a total of 94 publicly reported deaths
in locations outside of Hubei Province, China, between December 18th,
2019 and March 8th, 2020 were included as cases. Each case was matched
with up to three controls, based on gender and age ± 1 year old (94
cases and 181 controls).

Quick links:

-   [Study Design and Rationale](#study-rationale)
-   [Data Collection Procedure](#data-collection)
-   [Data Summary](#table1)
-   [Weighted Cox Proportional Hazard Model-Univariate](#univariate-Cox)
-   [Weighted Cox Proportional Hazard
    Model-Multivariate](#multivariate-Cox)
-   [KM plot](#KM-plot)
-   [Sensitivity Analyses](#Sensitivity-analysis)

Study Design and Rationale
--------------------------

This study performed survival analysis under a nested case-control (NCC)
design to assess the roles of common comorbidities
(cardiocerebrovascular, endocrine and respiratory disease, etc.) in
predicting mortality for COVID-19, among patients in mainland China
outside of Hubei Province. The study period was from December 18th,
2019, when the first laboratory-confirmed case was announced in China,
till March 8th, 2020.

The study cohort was defined as all the publicly reported confirmed
COVID-19 patients outside of Hubei Province in mainland China between
the study period. During this period, 112 deaths outside of Hubei
Province were reported by the National Health Committee of China, and 18
were excluded from the present study due to missingness of important
clinical information. A total of 448 publicly reported
laboratory-confirmed COVID-19 cases (94 deaths and 354 survivors) were
initially collected. The data collection procedure was blinded to
patient comorbidity information. All deaths were included as cases, and
each case was matched with up to three controls on gender and age ± 1
year old (94 cases and 181 controls). 

Data Collection Procedure
-------------------------

We routinely searched for daily news and public health reports on
confirmed COVID-19 cases in all areas in mainland China outside of Hubei
Province. Patients’ clinical and comorbidity characteristics were
recorded and doubly confirmed by national/provincial/municipal health
commission websites, the official COVID-19 data reporting websites in
China. Follow-up time was defined as the duration from the date of
disease onset till the end of observation on March 8th or when the
participant died, whichever came first. For each eligible patient, we
followed local reports to update their survival status until the end of
follow-up time.

As illustrated in Figure 1, the inclusion criterion was publicly
reported COVID-19 patients who had complete information on basic
demographics (age, gender and region), disease onset date--the first
time a patient became symptomatic, and history of comorbidities (include
but not limited to hypertension, cardiovascular disease, diabetes and
respiratory diseases) were included in the analysis. Asymptomatic
patients were not included in this study. In addition, we defined
“comorbidity-free patients” as those who were specifically described as
“no pre-existing medical condition/comorbidity” on the
national/provincial/municipal health commission websites. 

![Figure 1:
Patient flow diagram detailing included subjects and exclusion
criteria.](/README_files/figure-markdown_strict/Flowchart.png)

In the following three steps, we used the No. 214 patient as an example
to introduce the dynamic tracking method we used to identify any missing
dates:

Step 1. Conducting an internet search on confirmed cases on baidu.com,
the largest search engine in China, using keywords “confirmed COVID-19
cases report” and “pre-existing comorbidities.” A search result
pertained to one confirmed case reported on the website of Municipal
Health Commission of Binzhou (Shandong Province) on February 17th,
described as “the 15th confirmed case: 30-year-old male without
pre-existing morbidities, who lives in the neighborhood of Xincun
Village. This patient was diagnosed positive on February 16th and is
being treated with precaution in Bincheng hospital.” We recorded age,
gender, region and comorbidity-free for this patient.

Step 2. We then determined the onset date of this patient based on
another announcement on the same website. In this announcement titled
“Possible exposure locations and times of the 15th confirmed case,” it
says, “the patient was symptomatic on February 14th.”

Step 3. Finally, we confirmed the event status of this patient as
discharged on March 3rd, by following the updates on this website.

Summary Data
------------


<table class="Rtable1">
<thead>
<tr>
<th class='rowlabel firstrow lastrow'></th>
<th class='firstrow lastrow'><span class='stratlabel'>Survivor<br><span class='stratn'>(n=181)</span></span></th>
<th class='firstrow lastrow'><span class='stratlabel'>Death<br><span class='stratn'>(n=94)</span></span></th>
<th class='firstrow lastrow'>P-value</th>
<th class='firstrow lastrow'><span class='stratlabel'>Overall<br><span class='stratn'>(n=275)</span></span></th>
</tr>
     </thead>
     <tbody>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Age<span class='varunits'> (years)</span></span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>Mean (SD)</td>
     <td>64.2 (14.7)</td>
     <td>70.7 (13.3)</td>
     <td>&lt;0.001</td>
     <td>66.4 (14.5)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Median [Min, Max]</td>
     <td class='lastrow'>67.0 [24.0, 90.0]</td>
     <td class='lastrow'>72.5 [25.0, 94.0]</td>
     <td class='lastrow'></td>
     <td class='lastrow'>68.0 [24.0, 94.0]</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Sex</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>Female</td>
     <td>64 (35.4%)</td>
     <td>38 (40.4%)</td>
     <td>0.488</td>
     <td>102 (37.1%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Male</td>
     <td class='lastrow'>117 (64.6%)</td>
     <td class='lastrow'>56 (59.6%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>173 (62.9%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Early non-intervention period</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>After 01/11/2020</td>
     <td>138 (76.2%)</td>
     <td>67 (71.3%)</td>
     <td>0.453</td>
     <td>205 (74.5%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Before 01/10/2020</td>
     <td class='lastrow'>43 (23.8%)</td>
     <td class='lastrow'>27 (28.7%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>70 (25.5%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>History of surgery</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>175 (96.7%)</td>
     <td>90 (95.7%)</td>
     <td>0.956</td>
     <td>265 (96.4%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>6 (3.3%)</td>
     <td class='lastrow'>4 (4.3%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>10 (3.6%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Hypertension</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>114 (63.0%)</td>
     <td>52 (55.3%)</td>
     <td>0.27</td>
     <td>166 (60.4%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>67 (37.0%)</td>
     <td class='lastrow'>42 (44.7%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>109 (39.6%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Coronary heart disease</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>166 (91.7%)</td>
     <td>69 (73.4%)</td>
     <td>&lt;0.001</td>
     <td>235 (85.5%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>15 (8.3%)</td>
     <td class='lastrow'>25 (26.6%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>40 (14.5%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Chronic_Bronchitis</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>169 (93.4%)</td>
     <td>87 (92.6%)</td>
     <td>0.998</td>
     <td>256 (93.1%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>12 (6.6%)</td>
     <td class='lastrow'>7 (7.4%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>19 (6.9%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>COPD</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>176 (97.2%)</td>
     <td>87 (92.6%)</td>
     <td>0.136</td>
     <td>263 (95.6%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>5 (2.8%)</td>
     <td class='lastrow'>7 (7.4%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>12 (4.4%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Diabetes</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>135 (74.6%)</td>
     <td>68 (72.3%)</td>
     <td>0.797</td>
     <td>203 (73.8%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>46 (25.4%)</td>
     <td class='lastrow'>26 (27.7%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>72 (26.2%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Cerebral_Infarction</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>173 (95.6%)</td>
     <td>83 (88.3%)</td>
     <td>0.0446</td>
     <td>256 (93.1%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>8 (4.4%)</td>
     <td class='lastrow'>11 (11.7%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>19 (6.9%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Cardiac_Failure</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>169 (93.4%)</td>
     <td>84 (89.4%)</td>
     <td>0.353</td>
     <td>253 (92.0%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>12 (6.6%)</td>
     <td class='lastrow'>10 (10.6%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>22 (8.0%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Renal_Failure</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>175 (96.7%)</td>
     <td>88 (93.6%)</td>
     <td>0.384</td>
     <td>263 (95.6%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>6 (3.3%)</td>
     <td class='lastrow'>6 (6.4%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>12 (4.4%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Hepatic_Failure</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>No</td>
     <td>181 (100%)</td>
     <td>91 (96.8%)</td>
     <td>0.0711</td>
     <td>272 (98.9%)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Yes</td>
     <td class='lastrow'>0 (0%)</td>
     <td class='lastrow'>3 (3.2%)</td>
     <td class='lastrow'></td>
     <td class='lastrow'>3 (1.1%)</td>
     </tr>
     <tr>
     <td class='rowlabel firstrow'><span class='varlabel'>Comorbidity Score</span></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     <td class='firstrow'></td>
     </tr>
     <tr>
     <td class='rowlabel'>Mean (SD)</td>
     <td>1.02 (1.11)</td>
     <td>1.60 (2.17)</td>
     <td>&lt;0.001</td>
     <td>1.22 (1.21)</td>
     </tr>
     <tr>
     <td class='rowlabel lastrow'>Median [Min, Max]</td>
     <td class='lastrow'>1.00 [0.00, 5.0]</td>
     <td class='lastrow'>1.50 [0.00, 5.0]</td>
     <td class='lastrow'></td>
     <td class='lastrow'>1.00 [0.00, 5.0]</td>
     </tr>
     </tbody>
     </table>


Additional Fisher’s exact test & Mann–Whitney U test

    ## 
    ##  Fisher's Exact Test for Count Data
    ## 
    ## data:  covid_sub$History_of_Surgery and covid_sub$Death
    ## p-value = 0.7394
    ## alternative hypothesis: true odds ratio is not equal to 1
    ## 95 percent confidence interval:
    ##  0.2618976 5.6202653
    ## sample estimates:
    ## odds ratio 
    ##   1.294993

    ## 
    ##  Wilcoxon rank sum test with continuity correction
    ## 
    ## data:  Age by Death
    ## W = 6255.5, p-value = 0.0003183
    ## alternative hypothesis: true location shift is not equal to 0

    ## 
    ##  Wilcoxon rank sum test with continuity correction
    ## 
    ## data:  ComorbidityScore by Death
    ## W = 5940.5, p-value = 2.296e-05
    ## alternative hypothesis: true location shift is not equal to 0

Median followup time:

    ## Call: survfit(formula = Surv(time = Followup_Days, event = event_follow) ~ 
    ##     1, data = covid_sub)
    ## 
    ##       n  events  median 0.95LCL 0.95UCL 
    ##     275     181      40      38      42

Univariate Cox PH Model
-----------------------

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Age</td>
<td style="text-align: right;">0.0486394</td>
<td style="text-align: right;">1.049842</td>
<td style="text-align: right;">0.0086594</td>
<td style="text-align: right;">0.0100961</td>
<td style="text-align: right;">4.817644</td>
<td style="text-align: right;">1.5e-06</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Male</td>
<td style="text-align: right;">-0.2732098</td>
<td style="text-align: right;">0.7609332</td>
<td style="text-align: right;">0.2103793</td>
<td style="text-align: right;">0.2329391</td>
<td style="text-align: right;">-1.172881</td>
<td style="text-align: right;">0.2408437</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Early_Infection</td>
<td style="text-align: right;">0.1115256</td>
<td style="text-align: right;">1.117982</td>
<td style="text-align: right;">0.2307952</td>
<td style="text-align: right;">0.2498649</td>
<td style="text-align: right;">0.4463437</td>
<td style="text-align: right;">0.655349</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>History_of_Surgery</td>
<td style="text-align: right;">0.5353023</td>
<td style="text-align: right;">1.707964</td>
<td style="text-align: right;">0.5111814</td>
<td style="text-align: right;">0.5562612</td>
<td style="text-align: right;">0.9623218</td>
<td style="text-align: right;">0.335888</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Hypertension</td>
<td style="text-align: right;">0.3119277</td>
<td style="text-align: right;">1.366056</td>
<td style="text-align: right;">0.2075527</td>
<td style="text-align: right;">0.2339723</td>
<td style="text-align: right;">1.333182</td>
<td style="text-align: right;">0.1824719</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>CHD</td>
<td style="text-align: right;">1.433072</td>
<td style="text-align: right;">4.191554</td>
<td style="text-align: right;">0.2346989</td>
<td style="text-align: right;">0.2710545</td>
<td style="text-align: right;">5.287023</td>
<td style="text-align: right;">1e-07</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Chronic_Bronchitis</td>
<td style="text-align: right;">0.0508731</td>
<td style="text-align: right;">1.052189</td>
<td style="text-align: right;">0.3930306</td>
<td style="text-align: right;">0.4487422</td>
<td style="text-align: right;">0.1133681</td>
<td style="text-align: right;">0.9097387</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>COPD</td>
<td style="text-align: right;">0.9590383</td>
<td style="text-align: right;">2.609186</td>
<td style="text-align: right;">0.393382</td>
<td style="text-align: right;">0.3909177</td>
<td style="text-align: right;">2.4533</td>
<td style="text-align: right;">0.0141552</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Diabetes</td>
<td style="text-align: right;">0.1349872</td>
<td style="text-align: right;">1.144522</td>
<td style="text-align: right;">0.2306795</td>
<td style="text-align: right;">0.2611842</td>
<td style="text-align: right;">0.5168275</td>
<td style="text-align: right;">0.6052766</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>ComorbidityScore</td>
<td style="text-align: right;">0.4018354</td>
<td style="text-align: right;">1.494565</td>
<td style="text-align: right;">0.0772606</td>
<td style="text-align: right;">0.0816546</td>
<td style="text-align: right;">4.921158</td>
<td style="text-align: right;">9e-07</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Cerebral_Infarction</td>
<td style="text-align: right;">1.049599</td>
<td style="text-align: right;">2.856504</td>
<td style="text-align: right;">0.3219388</td>
<td style="text-align: right;">0.3600373</td>
<td style="text-align: right;">2.91525</td>
<td style="text-align: right;">0.003554</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Cardiac_Failure</td>
<td style="text-align: right;">0.6132745</td>
<td style="text-align: right;">1.846468</td>
<td style="text-align: right;">0.3346376</td>
<td style="text-align: right;">0.3758117</td>
<td style="text-align: right;">1.631866</td>
<td style="text-align: right;">0.1027076</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Renal_Failure</td>
<td style="text-align: right;">0.8310933</td>
<td style="text-align: right;">2.295827</td>
<td style="text-align: right;">0.4233677</td>
<td style="text-align: right;">0.4904419</td>
<td style="text-align: right;">1.69458</td>
<td style="text-align: right;">0.0901551</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Hepatic_Failure</td>
<td style="text-align: right;">2.11074</td>
<td style="text-align: right;">8.254343</td>
<td style="text-align: right;">0.5915688</td>
<td style="text-align: right;">0.288125</td>
<td style="text-align: right;">7.325777</td>
<td style="text-align: right;">0</td>
</tr>
</tbody>
</table>

Multivariate Cox PH Model
-------------------------

Model 1:

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Age</td>
<td style="text-align: right;">0.0422091</td>
<td style="text-align: right;">1.043113</td>
<td style="text-align: right;">0.0092716</td>
<td style="text-align: right;">0.0106404</td>
<td style="text-align: right;">3.9668523</td>
<td style="text-align: right;">0.0000728</td>
</tr>
<tr class="even">
<td>Male</td>
<td style="text-align: right;">0.0478739</td>
<td style="text-align: right;">1.049038</td>
<td style="text-align: right;">0.2145176</td>
<td style="text-align: right;">0.2295828</td>
<td style="text-align: right;">0.2085257</td>
<td style="text-align: right;">0.8348185</td>
</tr>
<tr class="odd">
<td>Early_Infection</td>
<td style="text-align: right;">0.2460885</td>
<td style="text-align: right;">1.279013</td>
<td style="text-align: right;">0.2320980</td>
<td style="text-align: right;">0.2455243</td>
<td style="text-align: right;">1.0022980</td>
<td style="text-align: right;">0.3161997</td>
</tr>
<tr class="even">
<td>ComorbidityScore</td>
<td style="text-align: right;">0.2673628</td>
<td style="text-align: right;">1.306514</td>
<td style="text-align: right;">0.0816799</td>
<td style="text-align: right;">0.0822388</td>
<td style="text-align: right;">3.2510526</td>
<td style="text-align: right;">0.0011498</td>
</tr>
</tbody>
</table>

Model 2:

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Age</td>
<td style="text-align: right;">0.0425327</td>
<td style="text-align: right;">1.043450</td>
<td style="text-align: right;">0.0090123</td>
<td style="text-align: right;">0.0104228</td>
<td style="text-align: right;">4.0807517</td>
<td style="text-align: right;">0.0000449</td>
</tr>
<tr class="even">
<td>Male</td>
<td style="text-align: right;">0.0852805</td>
<td style="text-align: right;">1.089023</td>
<td style="text-align: right;">0.2134930</td>
<td style="text-align: right;">0.2275641</td>
<td style="text-align: right;">0.3747538</td>
<td style="text-align: right;">0.7078435</td>
</tr>
<tr class="odd">
<td>Early_Infection</td>
<td style="text-align: right;">0.1779544</td>
<td style="text-align: right;">1.194771</td>
<td style="text-align: right;">0.2318960</td>
<td style="text-align: right;">0.2490904</td>
<td style="text-align: right;">0.7144171</td>
<td style="text-align: right;">0.4749693</td>
</tr>
<tr class="even">
<td>CHD</td>
<td style="text-align: right;">1.0732430</td>
<td style="text-align: right;">2.924849</td>
<td style="text-align: right;">0.2428424</td>
<td style="text-align: right;">0.2652509</td>
<td style="text-align: right;">4.0461433</td>
<td style="text-align: right;">0.0000521</td>
</tr>
</tbody>
</table>

Model 3:

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">coef</th>
<th style="text-align: right;">exp(coef)</th>
<th style="text-align: right;">se(coef)</th>
<th style="text-align: right;">robust se</th>
<th style="text-align: right;">z</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Age</td>
<td style="text-align: right;">0.0372684</td>
<td style="text-align: right;">1.0379716</td>
<td style="text-align: right;">0.0092484</td>
<td style="text-align: right;">0.0107136</td>
<td style="text-align: right;">3.4786102</td>
<td style="text-align: right;">0.0005040</td>
</tr>
<tr class="even">
<td>Male</td>
<td style="text-align: right;">-0.0027273</td>
<td style="text-align: right;">0.9972764</td>
<td style="text-align: right;">0.2186409</td>
<td style="text-align: right;">0.2396018</td>
<td style="text-align: right;">-0.0113828</td>
<td style="text-align: right;">0.9909181</td>
</tr>
<tr class="odd">
<td>Early_Infection</td>
<td style="text-align: right;">0.1904524</td>
<td style="text-align: right;">1.2097968</td>
<td style="text-align: right;">0.2338193</td>
<td style="text-align: right;">0.2500363</td>
<td style="text-align: right;">0.7616992</td>
<td style="text-align: right;">0.4462396</td>
</tr>
<tr class="even">
<td>CHD</td>
<td style="text-align: right;">1.1012042</td>
<td style="text-align: right;">3.0077858</td>
<td style="text-align: right;">0.2423555</td>
<td style="text-align: right;">0.2575034</td>
<td style="text-align: right;">4.2764651</td>
<td style="text-align: right;">0.0000190</td>
</tr>
<tr class="odd">
<td>Cerebral_Infarction</td>
<td style="text-align: right;">0.6419621</td>
<td style="text-align: right;">1.9002055</td>
<td style="text-align: right;">0.3341922</td>
<td style="text-align: right;">0.3592212</td>
<td style="text-align: right;">1.7870938</td>
<td style="text-align: right;">0.0739223</td>
</tr>
<tr class="even">
<td>COPD</td>
<td style="text-align: right;">0.6166034</td>
<td style="text-align: right;">1.8526247</td>
<td style="text-align: right;">0.4154428</td>
<td style="text-align: right;">0.3734279</td>
<td style="text-align: right;">1.6511980</td>
<td style="text-align: right;">0.0986982</td>
</tr>
<tr class="odd">
<td>Renal_Failure</td>
<td style="text-align: right;">0.7046864</td>
<td style="text-align: right;">2.0232120</td>
<td style="text-align: right;">0.4360997</td>
<td style="text-align: right;">0.4684805</td>
<td style="text-align: right;">1.5041956</td>
<td style="text-align: right;">0.1325310</td>
</tr>
</tbody>
</table>

KM Plot
-------
![Figure 1:
Patient flow diagram detailing included subjects and exclusion
criteria.](/README_files/figure-markdown_strict/KM-plot-1.png)

Sensitivity Analyses
--------------------

Sensitivity analysis was performed using multivariate logistic
regression to provide estimated odds ratio (ORs), which includes the
same covariates as the multivariate weighted Cox model. The results were
similar.

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">Estimate</th>
<th style="text-align: right;">Std. Error</th>
<th style="text-align: right;">z value</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>(Intercept)</td>
<td style="text-align: right;">-2.9553523</td>
<td style="text-align: right;">0.8053584</td>
<td style="text-align: right;">-3.6696111</td>
<td style="text-align: right;">0.0002429</td>
</tr>
<tr class="even">
<td>Age</td>
<td style="text-align: right;">0.0289566</td>
<td style="text-align: right;">0.0106839</td>
<td style="text-align: right;">2.7103099</td>
<td style="text-align: right;">0.0067220</td>
</tr>
<tr class="odd">
<td>Male</td>
<td style="text-align: right;">0.0466922</td>
<td style="text-align: right;">0.2820745</td>
<td style="text-align: right;">0.1655316</td>
<td style="text-align: right;">0.8685256</td>
</tr>
<tr class="even">
<td>Early_Infection</td>
<td style="text-align: right;">0.4753632</td>
<td style="text-align: right;">0.3048857</td>
<td style="text-align: right;">1.5591523</td>
<td style="text-align: right;">0.1189603</td>
</tr>
<tr class="odd">
<td>CHD</td>
<td style="text-align: right;">1.1833551</td>
<td style="text-align: right;">0.3711950</td>
<td style="text-align: right;">3.1879609</td>
<td style="text-align: right;">0.0014328</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">Estimate</th>
<th style="text-align: right;">Std. Error</th>
<th style="text-align: right;">z value</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>(Intercept)</td>
<td style="text-align: right;">-2.5960546</td>
<td style="text-align: right;">0.8248978</td>
<td style="text-align: right;">-3.1471228</td>
<td style="text-align: right;">0.0016489</td>
</tr>
<tr class="even">
<td>Age</td>
<td style="text-align: right;">0.0220286</td>
<td style="text-align: right;">0.0111294</td>
<td style="text-align: right;">1.9793162</td>
<td style="text-align: right;">0.0477804</td>
</tr>
<tr class="odd">
<td>Male</td>
<td style="text-align: right;">-0.0416592</td>
<td style="text-align: right;">0.2890719</td>
<td style="text-align: right;">-0.1441136</td>
<td style="text-align: right;">0.8854107</td>
</tr>
<tr class="even">
<td>Early_Infection</td>
<td style="text-align: right;">0.5207312</td>
<td style="text-align: right;">0.3105032</td>
<td style="text-align: right;">1.6770559</td>
<td style="text-align: right;">0.0935316</td>
</tr>
<tr class="odd">
<td>CHD</td>
<td style="text-align: right;">1.2364024</td>
<td style="text-align: right;">0.3786224</td>
<td style="text-align: right;">3.2655289</td>
<td style="text-align: right;">0.0010926</td>
</tr>
<tr class="even">
<td>Cerebral_Infarction</td>
<td style="text-align: right;">0.9023069</td>
<td style="text-align: right;">0.5167924</td>
<td style="text-align: right;">1.7459757</td>
<td style="text-align: right;">0.0808152</td>
</tr>
<tr class="odd">
<td>COPD</td>
<td style="text-align: right;">0.9351284</td>
<td style="text-align: right;">0.6386495</td>
<td style="text-align: right;">1.4642279</td>
<td style="text-align: right;">0.1431317</td>
</tr>
<tr class="even">
<td>Renal_Failure</td>
<td style="text-align: right;">0.6642553</td>
<td style="text-align: right;">0.6410489</td>
<td style="text-align: right;">1.0362007</td>
<td style="text-align: right;">0.3001085</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th></th>
<th style="text-align: right;">Estimate</th>
<th style="text-align: right;">Std. Error</th>
<th style="text-align: right;">z value</th>
<th style="text-align: right;">Pr(&gt;|z|)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>(Intercept)</td>
<td style="text-align: right;">-2.9195778</td>
<td style="text-align: right;">0.8068492</td>
<td style="text-align: right;">-3.6184925</td>
<td style="text-align: right;">0.0002963</td>
</tr>
<tr class="even">
<td>Age</td>
<td style="text-align: right;">0.0247662</td>
<td style="text-align: right;">0.0109997</td>
<td style="text-align: right;">2.2515310</td>
<td style="text-align: right;">0.0243519</td>
</tr>
<tr class="odd">
<td>Male</td>
<td style="text-align: right;">-0.0190545</td>
<td style="text-align: right;">0.2822476</td>
<td style="text-align: right;">-0.0675099</td>
<td style="text-align: right;">0.9461758</td>
</tr>
<tr class="even">
<td>Early_Infection</td>
<td style="text-align: right;">0.5133597</td>
<td style="text-align: right;">0.3056213</td>
<td style="text-align: right;">1.6797248</td>
<td style="text-align: right;">0.0930109</td>
</tr>
<tr class="odd">
<td>ComorbidityScore</td>
<td style="text-align: right;">0.2938610</td>
<td style="text-align: right;">0.0944214</td>
<td style="text-align: right;">3.1122296</td>
<td style="text-align: right;">0.0018568</td>
</tr>
</tbody>
</table>
