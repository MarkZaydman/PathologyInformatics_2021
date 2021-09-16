---
title: "AccuracyLecture_Activity.md"
author: "Mark Zaydman"
output: pdf_document
---

# Exploring accuracy concepts </div> {ignore=True}

#### Mark A. Zaydman<sup>1</sup> {ignore=True}

<sup>1</sup>Department of Pathology and Immunology, Division of Laboratory and Genomic medicine, Washington University in St. Louis, School of Medicine, St. Louis, MO 

## Table of contents {ignore=True}

[TOC]

## Introduction

The purpose of this class activity is to: 1) apply the metrics of analytical accuracy presented in class, and 2) to start to consider the overlap and distinctions between accuracy and value. 
You will be divided into small groups.
Please discuss the questions and the case listed below with your group.
Try to arrive at a consensus position and be prepared to explain your collective reasoning to the class. 

## Background

Cardiac troponins are proteins that are specifically expressed in cardiac myocytes.
As such, the quantitation of circulating cardiac troponins serves as a specific biomarker of myocardial injury and serves as an important diagnostic test in the diagnosis of an acute myocardial infarction.
Recent improvements in analytical methods have led to the development of high sensitivity cardiac troponin assays (hs-cTN) that are capable of detecting circulating cardiac troponins in greater than 50% of healthy individuals.
This represents an approximately 10 fold improvement in the lower limit of quantification.

<p style="page-break-after: always;">&nbsp;</p>

## Questions

**Question 1:** If the diagnostic threshold is considered to be any concentration above the lower limit of quantification, what do you expect to be the impact (increase/decrease/no change) of migrating from a standard cardiac troponin assay to the hs-cTN assay on the follow accuracy metrics?
<table>
    <tr>
        <th>Metric</th>
        <th>Impact</th>
        <th>Metric</th>        
        <th>Impact</th>        
    </tr>
    <tr>
        <td align="right">Sensitivity:</td>
        <td></td>
        <td align="right">LR<sup>+</sup>:</td>
        <td></td>   
    </tr>
    <tr>
        <td align="right">Specificity:</td>
        <td></td>
        <td align="right">LR<sup>-</sup>:</td>
        <td></td>   
    </tr>         
    <tr>
        <td align="right">PPV:</td>
        <td></td>
        <td align="right">DOR:</td>
        <td></td>   
    </tr>
    <tr>
        <td align="right">NPV:</td>
        <td></td>
    </tr>             
</table>


**Question 2:** What do you think the clinical utility of a high sensitivity cardiac troponin assay is? (choose all that apply)

1. Helps to confidently rule-in an acute MI.
2. Helps to confidently rule-out an acute MI.
3. Shortens time to diagnosis.
4. Better for evaluating asymptomatic individuals.
5. Better for evaluating symptomatic individuals.

**Question 3:** The diagnostic threshold for a baseline hs-cTN is typically taken to be greater than the 99<sup>th</sup> percentile of values observed in a healthy cohort. Why is it important to use the 99<sup>th</sup> percentile instead of the 95<sup>th</sup> or the lower limit of quantification? (choose all that apply)

1. Helps to confidently rule-in an acute MI.
2. Helps to confidently rule-out an acute MI.
3. Shortens time to diagnosis.
4. Better for evaluating asymptomatic individuals.
5. Better for evaluating symptomatic individuals.

<p style="page-break-after: always;">&nbsp;</p>

**Question 4:** Sketch how the ROC curves will differ for the conventional and high sensitivity troponin assays.

<br /><br /><br /><br /><br /><br /><br /><br /><br /><br />




**Question 5:**
The area under the ROC curve for two different assays is 0.6 and 0.3.
Which assay is more accurate?

**Question 6:** 
The results of a study (*Giannitsis E et al. 2010 Clin Chem*) evaluating the performance characteristics of a high sensitivity cardiac troponin assay for the diagnosis of NSTEMI are presented in the two-by-two contingency table below:

<block style="margin-left:auto;margin-right:auto;margin-top:40px;margin-bottom:40px">

<table>
  <tr align='center'>
    <th><ins>NSTEMI</ins></th>
    <td>hs-cTN > 14 ng/L (99<sup>th</sup>%</th>)
    <td>hs-cTN <= 14 ng/L (99<sup>th</sup>%</th>)
  </tr>
  <tr>
    <td align="right">Diseased</td>
    <td align='center'>125</td>
    <td align='center'>11</td>
  </tr>
  <tr>
    <td align="right">Healthy</td>
    <td align='center'>117</td>
    <td align='center'>250</td>
  </tr>
</table>
</block>

Based upon these data estimate the following:

<table>
    <tr >
        <th align="right">Metric</th>
        <th align="center">Estimate</th>
        <th align="center">Metric</th>        
        <th align="center">Estimate</th>        
    </tr>
    <tr>
        <td align="right">Prevalence:</td>
        <td></td>
        <td align="right">NPV:</sup></td>
        <td></td>   
    </tr>
    <tr>
        <td align="right">Sensitivity:</td>
        <td></td>
        <td align="right">LR<sup>+</sup>:</td>
        <td></td>   
    </tr>         
    <tr>
        <td align="right">Specificity:</td>
        <td></td>
        <td align="right">LR<sup>-</sup>:</td>
        <td></td>   
    </tr>
    <tr>
        <td align="right">PPV:</td>
        <td></td>
        <td align="right">DOR:</td>
        <td></td>        
    </tr>             
</table>

<p style="page-break-after: always;">&nbsp;</p>

## Clinical case

A 50 year old man with a history of HTN, HLD, T2DM, and obesity presents to the ED with squeezing chest pain, shortness of breath, and dizziness. 
On physical exam he is pale, diaphoretic, and in apparent discomfort.

A STAT ECG was obtained and is shown below:

![](../Activity/STEMI.jpeg)

What is the most appropriate next step in management?

<style type="text/css">
    ol { list-style-type: upper-alpha; }
</style>

1. Order CK-MB
2. Order LDH
3. Order conventional cardiac troponins
4. Order high sensitivity cardiac troponins
5. Cardiac catheterization