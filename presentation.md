

<style>
.footer {
    color: black;
    background: white;
    position: fixed;
    top: 90%;
    text-align:center;
    width:100%;
}
.midcenter {
    position: fixed;
    top: 75%;
    left: 50%;
}
.small-code pre code {
  font-size: 1em;
}

.reveal h3 {
  word-wrap: normal;
  -moz-hyphens: none;
}
.reveal h1 {
  word-wrap: normal;
  -moz-hyphens: none;
}
.exclaim .reveal .state-background {
  background: white;
} 

.exclaim .reveal h1,
.exclaim .reveal h2,
.exclaim .reveal p {
  color: black;
}
.section .reveal .state-background {
    background: white;}
.section .reveal h1,
.section .reveal p {
    color: black;
    position: relative;
    top: 4%;}
</style>


Applied Economics in Finance and Banking 
========================================================
autosize: true
transition: rotate
type:section
<br>
<br>
<a href="https://www.linkedin.com/in/nick-lewellen-8b305472/">Nick Lewellen</a> <br>
Senior Credit Data Analytics Officer <br>
April 13th, 2018 <br>


<div class="midcenter"><div style="margin-left:-0px;margin-top:-75px;"><img style="margin:0px; background-color:transparent; border:0px; box-shadow:none;" src="tulogo.jpg"></img></div></div>

Background
========================================================
type:exclaim

## Education

- B.A. Economics, University of Tulsa, 2013
- M.A. Economics, Duke University, 2015
- M.S. Analytics, Georgia Institute of Technology, Present

## Work

- Financial Analyst, CFO Network, 2016-17
- Quantitative Risk Modeler, Bank of the Ozarks, 2017-18
- Senior Credit Data Analytics Officer, Bank of the Ozarks, 2018-present

Graduate Education
========================================================

## Why?

- If you ask "Why should I go to graduate school" and the answer
mentions the job market, start over. 

## Where?

- Better schools are preferred. 
    - If Master's, then name brand.
    - If PhD, experience and environment.
- Go somewhere you'll be happy. 
- Consider online or distance programs. 
    - Often cheaper
    - Allow you to work 
    - Excellent Universities (Hopkins, GA Tech, Penn State)

 

Graduate Education pt. 2
========================================================

## When?

- There is no good answer for this. 
- Right after college or a few years after can both work.

<b>Don't take advice on graduate school (or anything else) too seriously!</b>
<br>
- Advice is always based on personal experience. My experience is not your experience.

- You have your own tastes and preferences, and you know them better than I do. 

- It's really hard to make a life ruining decision right after college. 

My Experience at Duke
========================================================
<br>
- Math
- Most econ programs are very structured.
- Augment your education to your interests and needs. 
- It's going to be hard. 


Job Opportunities in Banking
========================================================

## Data and Statisitics 

- Commercial banking as perfect competition
- The analytics revolution in commercial banking
- Economists are suited to the task


## Dodd-Frank Act

- The Dodd Frank Act Stress Testing (i.e., DFAST) created an even greater need for 
economists, data scientists and analytics experts in banking.
- Despite what you hear, the industry has seemed to welcome the influx of talent.
- Even if DFAST is repealed, Stress Testing and economic analysis still has a place in
banking.

Stress Test Case Study
========================================================

- If the economy enters a recession, what happens to the 
bank's assets, deposits, etc.?
- The goal is to produce financial statements and projects
based on three scenarios: baseline, adverse, severely adverse.
- Example: Single Family Residential balances



<img src="presentation-figure/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" angle=90 style="display: block; margin: auto;" />

Stress Test Case Study pt. 2
========================================================

- Initial questions:
    - What happened during other recessions?
    - What factors contributed to the bank's growth and 
    contraction? 



<img src="presentation-figure/unnamed-chunk-4-1.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" angle=90 style="display: block; margin: auto;" />

Stress Test Case Study pt. 3
========================================================

- The DFAST problem is in changes. 
- BOTO grew from acquisitions. 



<img src="presentation-figure/unnamed-chunk-6-1.png" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" angle=90 style="display: block; margin: auto;" />

- We have to control for acquisitions. 
- Macroeconomic variables to contorl for the relationship
between the bank and the macroeconomic environment. 

Stress Test Case Study pt. 4
========================================================

Regression equation: 

$$% \delta Balance__t= \beta_0+ \beta_1 RVBacq+ \beta_2 UNBacq+ \beta_3 2010Q3acq+ \beta_4 CSBacq +\beta_5 2011Q2acq +\beta_6 GBIacq + \beta_7 FNBacq + \beta_8 SBIacq+ \beta_9 IBCacq + \beta_10 BCCacq+ \beta_11 2016Q3acq+ \beta_12 ∆Households+ \epsilon$$





|                      |   Estimate| Std. Error|    t value| Pr(>&#124;t&#124;)|
|:---------------------|----------:|----------:|----------:|------------------:|
|(Intercept)           | -0.0100682|  0.0126180| -0.7979218|          0.4283477|
|RVBacq                |  0.1509399|  0.0279752|  5.3954812|          0.0000015|
|UNBacq                |  0.1342309|  0.0299697|  4.4788902|          0.0000383|
|Q3_2010acq            |  0.2361953|  0.0284871|  8.2912927|          0.0000000|
|CSBacq                |  0.0399778|  0.0288719|  1.3846621|          0.1717477|
|Q2_2011acq            |  0.1682160|  0.0285789|  5.8860210|          0.0000002|
|FNBSacq               |  0.2304535|  0.0278235|  8.2827037|          0.0000000|
|SBIacq                |  0.3260567|  0.0279701| 11.6573499|          0.0000000|
|IBCacq                |  0.0513208|  0.0279482|  1.8362833|          0.0717228|
|BCCacq                |  0.1487508|  0.0278336|  5.3442824|          0.0000018|
|Q3_2016acq            |  0.7464250|  0.0280688| 26.5926786|          0.0000000|
|Houshold_baseline_dif |  0.0000457|  0.0000411|  1.1096126|          0.2719941|

- Include binary variables for acquisitions



Job Market Suggestions
========================================================

- Since Nov. 2017, I have interviewed dozens of people for entry
level and senior level positions at BOTO. 
- Mistake free resume and cover letters. 
- Do your research!
- Skills:
    - SQL (must!)
    - R or Python
    - SAS, Stata, Eviews, etc.
- Be proactive
- Show don't tell 


Questions and Follow Up
========================================================
<br>
## Questions?
<br>

## Contact

Linkedin: <a href="https://www.linkedin.com/in/nick-lewellen-8b305472/">Nick Lewellen</a> <br> 
Email: <a href="nlewellen@bankozarks.com">nlewellen@bankozarks.com</a> <br>
Phone: 501-352-8985 <br>
 
