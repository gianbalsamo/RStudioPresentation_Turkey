COST OF EURO AREA MEMBERSHIP  
========================================================
author: Gian Balsamo, Ph.D.  


========================================================
<style>
strong {
  font-weight: bold;
}
</style>

<style>
em {
  font-style: italic
}
</style>




# Turkey after the Global Financial Crisis  
In spite of being “one of the hardest hit emerging economies by the global financial crisis,” Turkey was able to soften considerably the effects of the recession by means of an expansionary monetary policy [see IMFworkingPaper2011, pp. 4-5]. This policy was aggressively deployed, starting November 2008, by the Central Bank of the Republic of Turkey (CBRT).  
Given Turkey’s persistent aim at being granted Euro Area membership, becoming thereby one of the the nineteen countries that use the euro as their currency, this study probes the disadvantageous impact that Euro Area membership would have had on Turkey’s recent monetary policy. The web application linked to this presentation quantifies such impact. 
A countercyclical and discretionary monetary policy is usually captured by changes in the short-term interest rate and the exchange rate. This is especially true in the case of a country such as Turkey that, starting from the 2001 crisis (noticeably, seven years before the beginning of the 2008 recession), purposefully adopted floating exchange rates and a robust inflation-targeting regime [IMFworkingPaper2011, p. 8].

========================================================

As argued by Harun Alp and Selim Elekdag, lower interest rates increase domestic demand and output, “putting [thereby upward] pressure on inflation”; they increase net exports, “further decreasing aggregate demand”; and, through a “financial accelerator mechanism,” they strengthen balance sheet fundamentals, thereby decreasing the opportunity cost of investments [IMFworkingPaper2011, p. 14].  
According to Alp and Elekdag, these three factors explain why the CBRT’s monetary policy softened to a significant degree the medium-term impact of the global financial crisis.  This study adopts increments in money supply as a proxy to the CBRT’s pro-active interventions on interest rates and purposeful non-intervention on exchange rates. More specifically, increments/decrements of money supply are here treated as reasonably faithful indicators of a countercyclical leverage which is unavailable, by definition, to the central banks of Euro Area members.  
In the aftermath of the 2008 crisis, Euro Area membership would have deprived the CBRT of the option of an expansionary monetary policy.  Can we quantify this loss of leverage?  

========================================================

In the following slides, **a cost function** is defined and measured in terms of **the ratio of the CBRT’s yearly increase in money supply over the analogous aggregate increase of its European counterparts**. The data consist of OECD monthly monetary aggregates from 1992 to 2014, and include currency narrowly defined, i.e. banknotes and coins, plus overnight deposits; they are measured as a seasonally adjusted index based on 2010=100 [see OECD2015].  
The rest of this slide presentation describes the rationale and the algorithm of the cost function, and provide a concise user guide to the cost-function application. Once activated, this application will enable the user to compute month-by-month the cost, i.e. the leverage loss, to Turkey's monetary policy, of an hypotethical Euro Area membership. The cost function is deployed at this site:
(https://gianbalsamo.shinyapps.io/moreComplexShinyApplication)

========================================================

## Interactive Chart 1.  
## Turkey's Money Supply (1992-2014, monthly data, 2010=100) 
The charts in the next two slides, obtained from these data, plot the increase in money supply for Turkey and the Euro Area from 1992 to 2014, with the 2010 value serving as 100 index. By hovering the cursor over the chart, you can see and compare distinctive monthly values.

<link rel='stylesheet' href=//cdnjs.cloudflare.com/ajax/libs/nvd3/1.1.15-beta/nv.d3.min.css>
<script type='text/javascript' src=//ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js></script>
<script type='text/javascript' src=//d3js.org/d3.v3.min.js></script>
<script type='text/javascript' src=//cdnjs.cloudflare.com/ajax/libs/nvd3/1.1.15-beta/nv.d3.min.js></script>
<script type='text/javascript' src=//nvd3.org/assets/lib/fisheye.js></script> 
 <style>
  .rChart {
    display: block;
    margin-left: auto; 
    margin-right: auto;
    width: 800px;
    height: 400px;
  }  
  </style>
<div id = 'chartJ' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchartJ()
    });
    function drawchartJ(){  
      var opts = {
 "dom": "chartJ",
"width":    800,
"height":    400,
"x": "TIME",
"y": "Value",
"type": "multiBarChart",
"id": "chartJ" 
},
        data = [
 {
 "TIME": "1992-06-01",
"LOCATION": "TUR",
"Value":     0.06428535 
},
{
 "TIME": "1992-07-01",
"LOCATION": "TUR",
"Value":     0.06680655 
},
{
 "TIME": "1992-08-01",
"LOCATION": "TUR",
"Value":     0.06914815 
},
{
 "TIME": "1992-09-01",
"LOCATION": "TUR",
"Value":      0.0729182 
},
{
 "TIME": "1992-10-01",
"LOCATION": "TUR",
"Value":     0.07689486 
},
{
 "TIME": "1992-11-01",
"LOCATION": "TUR",
"Value":     0.08233015 
},
{
 "TIME": "1992-12-01",
"LOCATION": "TUR",
"Value":     0.08794507 
},
{
 "TIME": "1993-01-01",
"LOCATION": "TUR",
"Value":     0.09335715 
},
{
 "TIME": "1993-02-01",
"LOCATION": "TUR",
"Value":     0.09845393 
},
{
 "TIME": "1993-03-01",
"LOCATION": "TUR",
"Value":      0.1050505 
},
{
 "TIME": "1993-04-01",
"LOCATION": "TUR",
"Value":      0.1081227 
},
{
 "TIME": "1993-05-01",
"LOCATION": "TUR",
"Value":      0.1175953 
},
{
 "TIME": "1993-06-01",
"LOCATION": "TUR",
"Value":      0.1243591 
},
{
 "TIME": "1993-07-01",
"LOCATION": "TUR",
"Value":      0.1215915 
},
{
 "TIME": "1993-08-01",
"LOCATION": "TUR",
"Value":      0.1257577 
},
{
 "TIME": "1993-09-01",
"LOCATION": "TUR",
"Value":      0.1300028 
},
{
 "TIME": "1993-10-01",
"LOCATION": "TUR",
"Value":      0.1356167 
},
{
 "TIME": "1993-11-01",
"LOCATION": "TUR",
"Value":        0.14153 
},
{
 "TIME": "1993-12-01",
"LOCATION": "TUR",
"Value":      0.1466766 
},
{
 "TIME": "1994-01-01",
"LOCATION": "TUR",
"Value":      0.1506095 
},
{
 "TIME": "1994-02-01",
"LOCATION": "TUR",
"Value":      0.1511412 
},
{
 "TIME": "1994-03-01",
"LOCATION": "TUR",
"Value":      0.1467513 
},
{
 "TIME": "1994-04-01",
"LOCATION": "TUR",
"Value":      0.1548207 
},
{
 "TIME": "1994-05-01",
"LOCATION": "TUR",
"Value":      0.1826873 
},
{
 "TIME": "1994-06-01",
"LOCATION": "TUR",
"Value":      0.1983272 
},
{
 "TIME": "1994-07-01",
"LOCATION": "TUR",
"Value":      0.2099259 
},
{
 "TIME": "1994-08-01",
"LOCATION": "TUR",
"Value":      0.2315941 
},
{
 "TIME": "1994-09-01",
"LOCATION": "TUR",
"Value":      0.2451498 
},
{
 "TIME": "1994-10-01",
"LOCATION": "TUR",
"Value":      0.2556015 
},
{
 "TIME": "1994-11-01",
"LOCATION": "TUR",
"Value":      0.2647822 
},
{
 "TIME": "1994-12-01",
"LOCATION": "TUR",
"Value":      0.2681586 
},
{
 "TIME": "1995-01-01",
"LOCATION": "TUR",
"Value":      0.2768017 
},
{
 "TIME": "1995-02-01",
"LOCATION": "TUR",
"Value":      0.3046034 
},
{
 "TIME": "1995-03-01",
"LOCATION": "TUR",
"Value":      0.3208315 
},
{
 "TIME": "1995-04-01",
"LOCATION": "TUR",
"Value":      0.3384664 
},
{
 "TIME": "1995-05-01",
"LOCATION": "TUR",
"Value":      0.3717545 
},
{
 "TIME": "1995-06-01",
"LOCATION": "TUR",
"Value":      0.3939934 
},
{
 "TIME": "1995-07-01",
"LOCATION": "TUR",
"Value":      0.4180438 
},
{
 "TIME": "1995-08-01",
"LOCATION": "TUR",
"Value":      0.4333236 
},
{
 "TIME": "1995-09-01",
"LOCATION": "TUR",
"Value":      0.4459316 
},
{
 "TIME": "1995-10-01",
"LOCATION": "TUR",
"Value":       0.466597 
},
{
 "TIME": "1995-11-01",
"LOCATION": "TUR",
"Value":       0.478828 
},
{
 "TIME": "1995-12-01",
"LOCATION": "TUR",
"Value":      0.4681993 
},
{
 "TIME": "1996-01-01",
"LOCATION": "TUR",
"Value":      0.4800714 
},
{
 "TIME": "1996-02-01",
"LOCATION": "TUR",
"Value":      0.5323017 
},
{
 "TIME": "1996-03-01",
"LOCATION": "TUR",
"Value":      0.5617366 
},
{
 "TIME": "1996-04-01",
"LOCATION": "TUR",
"Value":      0.6156716 
},
{
 "TIME": "1996-05-01",
"LOCATION": "TUR",
"Value":      0.6481591 
},
{
 "TIME": "1996-06-01",
"LOCATION": "TUR",
"Value":      0.6415555 
},
{
 "TIME": "1996-07-01",
"LOCATION": "TUR",
"Value":       0.667399 
},
{
 "TIME": "1996-08-01",
"LOCATION": "TUR",
"Value":      0.7077261 
},
{
 "TIME": "1996-09-01",
"LOCATION": "TUR",
"Value":      0.7631689 
},
{
 "TIME": "1996-10-01",
"LOCATION": "TUR",
"Value":      0.8083317 
},
{
 "TIME": "1996-11-01",
"LOCATION": "TUR",
"Value":      0.8844156 
},
{
 "TIME": "1996-12-01",
"LOCATION": "TUR",
"Value":      0.9976155 
},
{
 "TIME": "1997-01-01",
"LOCATION": "TUR",
"Value":       1.096997 
},
{
 "TIME": "1997-02-01",
"LOCATION": "TUR",
"Value":       1.182048 
},
{
 "TIME": "1997-03-01",
"LOCATION": "TUR",
"Value":       1.280201 
},
{
 "TIME": "1997-04-01",
"LOCATION": "TUR",
"Value":       1.358625 
},
{
 "TIME": "1997-05-01",
"LOCATION": "TUR",
"Value":       1.384974 
},
{
 "TIME": "1997-06-01",
"LOCATION": "TUR",
"Value":        1.40993 
},
{
 "TIME": "1997-07-01",
"LOCATION": "TUR",
"Value":       1.418335 
},
{
 "TIME": "1997-08-01",
"LOCATION": "TUR",
"Value":       1.390034 
},
{
 "TIME": "1997-09-01",
"LOCATION": "TUR",
"Value":       1.458868 
},
{
 "TIME": "1997-10-01",
"LOCATION": "TUR",
"Value":        1.60631 
},
{
 "TIME": "1997-11-01",
"LOCATION": "TUR",
"Value":       1.638962 
},
{
 "TIME": "1997-12-01",
"LOCATION": "TUR",
"Value":       1.733823 
},
{
 "TIME": "1998-01-01",
"LOCATION": "TUR",
"Value":       1.968391 
},
{
 "TIME": "1998-02-01",
"LOCATION": "TUR",
"Value":       1.991919 
},
{
 "TIME": "1998-03-01",
"LOCATION": "TUR",
"Value":       1.987872 
},
{
 "TIME": "1998-04-01",
"LOCATION": "TUR",
"Value":       2.121341 
},
{
 "TIME": "1998-05-01",
"LOCATION": "TUR",
"Value":       2.186144 
},
{
 "TIME": "1998-06-01",
"LOCATION": "TUR",
"Value":       2.329307 
},
{
 "TIME": "1998-07-01",
"LOCATION": "TUR",
"Value":       2.567532 
},
{
 "TIME": "1998-08-01",
"LOCATION": "TUR",
"Value":       2.721984 
},
{
 "TIME": "1998-09-01",
"LOCATION": "TUR",
"Value":       2.862144 
},
{
 "TIME": "1998-10-01",
"LOCATION": "TUR",
"Value":       2.951957 
},
{
 "TIME": "1998-11-01",
"LOCATION": "TUR",
"Value":       2.974545 
},
{
 "TIME": "1998-12-01",
"LOCATION": "TUR",
"Value":       3.006397 
},
{
 "TIME": "1999-01-01",
"LOCATION": "TUR",
"Value":       3.141168 
},
{
 "TIME": "1999-02-01",
"LOCATION": "TUR",
"Value":       3.214484 
},
{
 "TIME": "1999-03-01",
"LOCATION": "TUR",
"Value":       3.584064 
},
{
 "TIME": "1999-04-01",
"LOCATION": "TUR",
"Value":       3.742786 
},
{
 "TIME": "1999-05-01",
"LOCATION": "TUR",
"Value":       3.524514 
},
{
 "TIME": "1999-06-01",
"LOCATION": "TUR",
"Value":       3.643867 
},
{
 "TIME": "1999-07-01",
"LOCATION": "TUR",
"Value":       3.748049 
},
{
 "TIME": "1999-08-01",
"LOCATION": "TUR",
"Value":       4.004656 
},
{
 "TIME": "1999-09-01",
"LOCATION": "TUR",
"Value":         4.2404 
},
{
 "TIME": "1999-10-01",
"LOCATION": "TUR",
"Value":       4.343685 
},
{
 "TIME": "1999-11-01",
"LOCATION": "TUR",
"Value":       4.467598 
},
{
 "TIME": "1999-12-01",
"LOCATION": "TUR",
"Value":       5.021299 
},
{
 "TIME": "2000-01-01",
"LOCATION": "TUR",
"Value":       5.894132 
},
{
 "TIME": "2000-02-01",
"LOCATION": "TUR",
"Value":       6.257369 
},
{
 "TIME": "2000-03-01",
"LOCATION": "TUR",
"Value":       6.328056 
},
{
 "TIME": "2000-04-01",
"LOCATION": "TUR",
"Value":       6.498438 
},
{
 "TIME": "2000-05-01",
"LOCATION": "TUR",
"Value":       6.950172 
},
{
 "TIME": "2000-06-01",
"LOCATION": "TUR",
"Value":       7.310826 
},
{
 "TIME": "2000-07-01",
"LOCATION": "TUR",
"Value":       7.696634 
},
{
 "TIME": "2000-08-01",
"LOCATION": "TUR",
"Value":        7.96929 
},
{
 "TIME": "2000-09-01",
"LOCATION": "TUR",
"Value":       8.020978 
},
{
 "TIME": "2000-10-01",
"LOCATION": "TUR",
"Value":       8.365701 
},
{
 "TIME": "2000-11-01",
"LOCATION": "TUR",
"Value":       8.631449 
},
{
 "TIME": "2000-12-01",
"LOCATION": "TUR",
"Value":       8.856974 
},
{
 "TIME": "2001-01-01",
"LOCATION": "TUR",
"Value":       9.102716 
},
{
 "TIME": "2001-02-01",
"LOCATION": "TUR",
"Value":       10.00366 
},
{
 "TIME": "2001-03-01",
"LOCATION": "TUR",
"Value":       10.77424 
},
{
 "TIME": "2001-04-01",
"LOCATION": "TUR",
"Value":       11.06387 
},
{
 "TIME": "2001-05-01",
"LOCATION": "TUR",
"Value":       11.62178 
},
{
 "TIME": "2001-06-01",
"LOCATION": "TUR",
"Value":       12.06964 
},
{
 "TIME": "2001-07-01",
"LOCATION": "TUR",
"Value":       12.44194 
},
{
 "TIME": "2001-08-01",
"LOCATION": "TUR",
"Value":       12.94803 
},
{
 "TIME": "2001-09-01",
"LOCATION": "TUR",
"Value":       13.10986 
},
{
 "TIME": "2001-10-01",
"LOCATION": "TUR",
"Value":       13.02833 
},
{
 "TIME": "2001-11-01",
"LOCATION": "TUR",
"Value":       13.19513 
},
{
 "TIME": "2001-12-01",
"LOCATION": "TUR",
"Value":       13.48804 
},
{
 "TIME": "2002-01-01",
"LOCATION": "TUR",
"Value":       13.87218 
},
{
 "TIME": "2002-02-01",
"LOCATION": "TUR",
"Value":       14.90787 
},
{
 "TIME": "2002-03-01",
"LOCATION": "TUR",
"Value":       15.22365 
},
{
 "TIME": "2002-04-01",
"LOCATION": "TUR",
"Value":        14.8805 
},
{
 "TIME": "2002-05-01",
"LOCATION": "TUR",
"Value":       15.47758 
},
{
 "TIME": "2002-06-01",
"LOCATION": "TUR",
"Value":       16.02934 
},
{
 "TIME": "2002-07-01",
"LOCATION": "TUR",
"Value":       16.48552 
},
{
 "TIME": "2002-08-01",
"LOCATION": "TUR",
"Value":       16.75585 
},
{
 "TIME": "2002-09-01",
"LOCATION": "TUR",
"Value":       17.37843 
},
{
 "TIME": "2002-10-01",
"LOCATION": "TUR",
"Value":       18.31587 
},
{
 "TIME": "2002-11-01",
"LOCATION": "TUR",
"Value":       18.91708 
},
{
 "TIME": "2002-12-01",
"LOCATION": "TUR",
"Value":       19.22287 
},
{
 "TIME": "2003-01-01",
"LOCATION": "TUR",
"Value":       19.49206 
},
{
 "TIME": "2003-02-01",
"LOCATION": "TUR",
"Value":       19.81253 
},
{
 "TIME": "2003-03-01",
"LOCATION": "TUR",
"Value":        19.9841 
},
{
 "TIME": "2003-04-01",
"LOCATION": "TUR",
"Value":       19.97449 
},
{
 "TIME": "2003-05-01",
"LOCATION": "TUR",
"Value":       20.09681 
},
{
 "TIME": "2003-06-01",
"LOCATION": "TUR",
"Value":       21.22314 
},
{
 "TIME": "2003-07-01",
"LOCATION": "TUR",
"Value":       22.50395 
},
{
 "TIME": "2003-08-01",
"LOCATION": "TUR",
"Value":       23.06637 
},
{
 "TIME": "2003-09-01",
"LOCATION": "TUR",
"Value":       24.13056 
},
{
 "TIME": "2003-10-01",
"LOCATION": "TUR",
"Value":       25.59487 
},
{
 "TIME": "2003-11-01",
"LOCATION": "TUR",
"Value":       26.95823 
},
{
 "TIME": "2003-12-01",
"LOCATION": "TUR",
"Value":       27.94435 
},
{
 "TIME": "2004-01-01",
"LOCATION": "TUR",
"Value":       30.36655 
},
{
 "TIME": "2004-02-01",
"LOCATION": "TUR",
"Value":       30.94914 
},
{
 "TIME": "2004-03-01",
"LOCATION": "TUR",
"Value":       30.07431 
},
{
 "TIME": "2004-04-01",
"LOCATION": "TUR",
"Value":       31.45382 
},
{
 "TIME": "2004-05-01",
"LOCATION": "TUR",
"Value":       32.33878 
},
{
 "TIME": "2004-06-01",
"LOCATION": "TUR",
"Value":       32.61805 
},
{
 "TIME": "2004-07-01",
"LOCATION": "TUR",
"Value":       32.90953 
},
{
 "TIME": "2004-08-01",
"LOCATION": "TUR",
"Value":       34.08751 
},
{
 "TIME": "2004-09-01",
"LOCATION": "TUR",
"Value":       34.96507 
},
{
 "TIME": "2004-10-01",
"LOCATION": "TUR",
"Value":       35.07753 
},
{
 "TIME": "2004-11-01",
"LOCATION": "TUR",
"Value":       35.40837 
},
{
 "TIME": "2004-12-01",
"LOCATION": "TUR",
"Value":       35.45994 
},
{
 "TIME": "2005-01-01",
"LOCATION": "TUR",
"Value":        35.9229 
},
{
 "TIME": "2005-02-01",
"LOCATION": "TUR",
"Value":       37.16319 
},
{
 "TIME": "2005-03-01",
"LOCATION": "TUR",
"Value":       38.68299 
},
{
 "TIME": "2005-04-01",
"LOCATION": "TUR",
"Value":       40.16473 
},
{
 "TIME": "2005-05-01",
"LOCATION": "TUR",
"Value":       40.97123 
},
{
 "TIME": "2005-06-01",
"LOCATION": "TUR",
"Value":       41.68172 
},
{
 "TIME": "2005-07-01",
"LOCATION": "TUR",
"Value":       42.87539 
},
{
 "TIME": "2005-08-01",
"LOCATION": "TUR",
"Value":       43.95375 
},
{
 "TIME": "2005-09-01",
"LOCATION": "TUR",
"Value":       45.11081 
},
{
 "TIME": "2005-10-01",
"LOCATION": "TUR",
"Value":        47.4871 
},
{
 "TIME": "2005-11-01",
"LOCATION": "TUR",
"Value":        48.3925 
},
{
 "TIME": "2005-12-01",
"LOCATION": "TUR",
"Value":       49.74916 
},
{
 "TIME": "2006-01-01",
"LOCATION": "TUR",
"Value":       52.01389 
},
{
 "TIME": "2006-02-01",
"LOCATION": "TUR",
"Value":       52.14031 
},
{
 "TIME": "2006-03-01",
"LOCATION": "TUR",
"Value":       52.47642 
},
{
 "TIME": "2006-04-01",
"LOCATION": "TUR",
"Value":       53.02528 
},
{
 "TIME": "2006-05-01",
"LOCATION": "TUR",
"Value":       57.98223 
},
{
 "TIME": "2006-06-01",
"LOCATION": "TUR",
"Value":       61.28053 
},
{
 "TIME": "2006-07-01",
"LOCATION": "TUR",
"Value":       58.65648 
},
{
 "TIME": "2006-08-01",
"LOCATION": "TUR",
"Value":       57.99984 
},
{
 "TIME": "2006-09-01",
"LOCATION": "TUR",
"Value":       58.43769 
},
{
 "TIME": "2006-10-01",
"LOCATION": "TUR",
"Value":       58.41433 
},
{
 "TIME": "2006-11-01",
"LOCATION": "TUR",
"Value":       58.24118 
},
{
 "TIME": "2006-12-01",
"LOCATION": "TUR",
"Value":       59.09494 
},
{
 "TIME": "2007-01-01",
"LOCATION": "TUR",
"Value":       59.54337 
},
{
 "TIME": "2007-02-01",
"LOCATION": "TUR",
"Value":       59.06969 
},
{
 "TIME": "2007-03-01",
"LOCATION": "TUR",
"Value":       58.74749 
},
{
 "TIME": "2007-04-01",
"LOCATION": "TUR",
"Value":        58.9942 
},
{
 "TIME": "2007-05-01",
"LOCATION": "TUR",
"Value":        60.0181 
},
{
 "TIME": "2007-06-01",
"LOCATION": "TUR",
"Value":       60.62762 
},
{
 "TIME": "2007-07-01",
"LOCATION": "TUR",
"Value":       61.73418 
},
{
 "TIME": "2007-08-01",
"LOCATION": "TUR",
"Value":        62.9994 
},
{
 "TIME": "2007-09-01",
"LOCATION": "TUR",
"Value":       62.30378 
},
{
 "TIME": "2007-10-01",
"LOCATION": "TUR",
"Value":       61.59008 
},
{
 "TIME": "2007-11-01",
"LOCATION": "TUR",
"Value":       63.01495 
},
{
 "TIME": "2007-12-01",
"LOCATION": "TUR",
"Value":       64.03269 
},
{
 "TIME": "2008-01-01",
"LOCATION": "TUR",
"Value":       64.87749 
},
{
 "TIME": "2008-02-01",
"LOCATION": "TUR",
"Value":       66.24491 
},
{
 "TIME": "2008-03-01",
"LOCATION": "TUR",
"Value":        68.2479 
},
{
 "TIME": "2008-04-01",
"LOCATION": "TUR",
"Value":       69.96207 
},
{
 "TIME": "2008-05-01",
"LOCATION": "TUR",
"Value":       69.79923 
},
{
 "TIME": "2008-06-01",
"LOCATION": "TUR",
"Value":       69.54837 
},
{
 "TIME": "2008-07-01",
"LOCATION": "TUR",
"Value":       70.21999 
},
{
 "TIME": "2008-08-01",
"LOCATION": "TUR",
"Value":       69.95692 
},
{
 "TIME": "2008-09-01",
"LOCATION": "TUR",
"Value":       71.64056 
},
{
 "TIME": "2008-10-01",
"LOCATION": "TUR",
"Value":       74.09857 
},
{
 "TIME": "2008-11-01",
"LOCATION": "TUR",
"Value":        73.8287 
},
{
 "TIME": "2008-12-01",
"LOCATION": "TUR",
"Value":       72.66344 
},
{
 "TIME": "2009-01-01",
"LOCATION": "TUR",
"Value":       72.88264 
},
{
 "TIME": "2009-02-01",
"LOCATION": "TUR",
"Value":       76.31331 
},
{
 "TIME": "2009-03-01",
"LOCATION": "TUR",
"Value":       78.31217 
},
{
 "TIME": "2009-04-01",
"LOCATION": "TUR",
"Value":       77.83634 
},
{
 "TIME": "2009-05-01",
"LOCATION": "TUR",
"Value":       78.65823 
},
{
 "TIME": "2009-06-01",
"LOCATION": "TUR",
"Value":       79.15849 
},
{
 "TIME": "2009-07-01",
"LOCATION": "TUR",
"Value":       79.52721 
},
{
 "TIME": "2009-08-01",
"LOCATION": "TUR",
"Value":       80.56467 
},
{
 "TIME": "2009-09-01",
"LOCATION": "TUR",
"Value":       82.76588 
},
{
 "TIME": "2009-10-01",
"LOCATION": "TUR",
"Value":       85.13492 
},
{
 "TIME": "2009-11-01",
"LOCATION": "TUR",
"Value":       89.48237 
},
{
 "TIME": "2009-12-01",
"LOCATION": "TUR",
"Value":         91.816 
},
{
 "TIME": "2010-01-01",
"LOCATION": "TUR",
"Value":       91.40368 
},
{
 "TIME": "2010-02-01",
"LOCATION": "TUR",
"Value":       94.02367 
},
{
 "TIME": "2010-03-01",
"LOCATION": "TUR",
"Value":       95.20166 
},
{
 "TIME": "2010-04-01",
"LOCATION": "TUR",
"Value":       95.28101 
},
{
 "TIME": "2010-05-01",
"LOCATION": "TUR",
"Value":       96.31741 
},
{
 "TIME": "2010-06-01",
"LOCATION": "TUR",
"Value":       98.62749 
},
{
 "TIME": "2010-07-01",
"LOCATION": "TUR",
"Value":        100.534 
},
{
 "TIME": "2010-08-01",
"LOCATION": "TUR",
"Value":       101.7097 
},
{
 "TIME": "2010-09-01",
"LOCATION": "TUR",
"Value":       103.1364 
},
{
 "TIME": "2010-10-01",
"LOCATION": "TUR",
"Value":       105.1738 
},
{
 "TIME": "2010-11-01",
"LOCATION": "TUR",
"Value":       107.5738 
},
{
 "TIME": "2010-12-01",
"LOCATION": "TUR",
"Value":       111.0174 
},
{
 "TIME": "2011-01-01",
"LOCATION": "TUR",
"Value":       114.6473 
},
{
 "TIME": "2011-02-01",
"LOCATION": "TUR",
"Value":       116.7503 
},
{
 "TIME": "2011-03-01",
"LOCATION": "TUR",
"Value":       118.6394 
},
{
 "TIME": "2011-04-01",
"LOCATION": "TUR",
"Value":       121.0677 
},
{
 "TIME": "2011-05-01",
"LOCATION": "TUR",
"Value":       123.5693 
},
{
 "TIME": "2011-06-01",
"LOCATION": "TUR",
"Value":       125.5929 
},
{
 "TIME": "2011-07-01",
"LOCATION": "TUR",
"Value":       128.3833 
},
{
 "TIME": "2011-08-01",
"LOCATION": "TUR",
"Value":       134.6873 
},
{
 "TIME": "2011-09-01",
"LOCATION": "TUR",
"Value":       135.8661 
},
{
 "TIME": "2011-10-01",
"LOCATION": "TUR",
"Value":       133.8085 
},
{
 "TIME": "2011-11-01",
"LOCATION": "TUR",
"Value":       135.3159 
},
{
 "TIME": "2011-12-01",
"LOCATION": "TUR",
"Value":       135.3699 
},
{
 "TIME": "2012-01-01",
"LOCATION": "TUR",
"Value":       134.6824 
},
{
 "TIME": "2012-02-01",
"LOCATION": "TUR",
"Value":       134.4113 
},
{
 "TIME": "2012-03-01",
"LOCATION": "TUR",
"Value":        134.429 
},
{
 "TIME": "2012-04-01",
"LOCATION": "TUR",
"Value":       135.8972 
},
{
 "TIME": "2012-05-01",
"LOCATION": "TUR",
"Value":       138.2298 
},
{
 "TIME": "2012-06-01",
"LOCATION": "TUR",
"Value":       140.4813 
},
{
 "TIME": "2012-07-01",
"LOCATION": "TUR",
"Value":       141.0636 
},
{
 "TIME": "2012-08-01",
"LOCATION": "TUR",
"Value":       141.2873 
},
{
 "TIME": "2012-09-01",
"LOCATION": "TUR",
"Value":       144.0167 
},
{
 "TIME": "2012-10-01",
"LOCATION": "TUR",
"Value":       146.7221 
},
{
 "TIME": "2012-11-01",
"LOCATION": "TUR",
"Value":       147.8475 
},
{
 "TIME": "2012-12-01",
"LOCATION": "TUR",
"Value":        149.358 
},
{
 "TIME": "2013-01-01",
"LOCATION": "TUR",
"Value":       152.3188 
},
{
 "TIME": "2013-02-01",
"LOCATION": "TUR",
"Value":       155.5647 
},
{
 "TIME": "2013-03-01",
"LOCATION": "TUR",
"Value":       159.6541 
},
{
 "TIME": "2013-04-01",
"LOCATION": "TUR",
"Value":       162.3468 
},
{
 "TIME": "2013-05-01",
"LOCATION": "TUR",
"Value":       166.7027 
},
{
 "TIME": "2013-06-01",
"LOCATION": "TUR",
"Value":       172.5549 
},
{
 "TIME": "2013-07-01",
"LOCATION": "TUR",
"Value":       176.2217 
},
{
 "TIME": "2013-08-01",
"LOCATION": "TUR",
"Value":       180.1482 
},
{
 "TIME": "2013-09-01",
"LOCATION": "TUR",
"Value":       182.0307 
},
{
 "TIME": "2013-10-01",
"LOCATION": "TUR",
"Value":       183.3479 
},
{
 "TIME": "2013-11-01",
"LOCATION": "TUR",
"Value":         186.93 
},
{
 "TIME": "2013-12-01",
"LOCATION": "TUR",
"Value":       190.7672 
},
{
 "TIME": "2014-01-01",
"LOCATION": "TUR",
"Value":       195.4386 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

========================================================
 

##  Interactive Chart 2.  
## Euro Area's's Money Supply (1992-2014, monthly data, 2010=100)
Between 2001 and 2014, the difference in slope with the previous slide is obvious. This difference is a rough but suggestive indicator of the steady extent whereby Turkey’s monetary policy has been more expansionary than the Euro Area’s for the last fifteen years.   

<link rel='stylesheet' href=//cdnjs.cloudflare.com/ajax/libs/nvd3/1.1.15-beta/nv.d3.min.css>
<script type='text/javascript' src=//ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js></script>
<script type='text/javascript' src=//d3js.org/d3.v3.min.js></script>
<script type='text/javascript' src=//cdnjs.cloudflare.com/ajax/libs/nvd3/1.1.15-beta/nv.d3.min.js></script>
<script type='text/javascript' src=//nvd3.org/assets/lib/fisheye.js></script> 
 <style>
  .rChart {
    display: block;
    margin-left: auto; 
    margin-right: auto;
    width: 800px;
    height: 400px;
  }  
  </style>
<div id = 'chartC' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchartC()
    });
    function drawchartC(){  
      var opts = {
 "dom": "chartC",
"width":    800,
"height":    400,
"x": "TIME",
"y": "Value",
"type": "multiBarChart",
"id": "chartC" 
},
        data = [
 {
 "TIME": "1992-06-01",
"LOCATION": "EA19",
"Value":       23.98398 
},
{
 "TIME": "1992-07-01",
"LOCATION": "EA19",
"Value":       23.95594 
},
{
 "TIME": "1992-08-01",
"LOCATION": "EA19",
"Value":       24.03075 
},
{
 "TIME": "1992-09-01",
"LOCATION": "EA19",
"Value":       24.20537 
},
{
 "TIME": "1992-10-01",
"LOCATION": "EA19",
"Value":       24.36568 
},
{
 "TIME": "1992-11-01",
"LOCATION": "EA19",
"Value":       24.54922 
},
{
 "TIME": "1992-12-01",
"LOCATION": "EA19",
"Value":       24.69844 
},
{
 "TIME": "1993-01-01",
"LOCATION": "EA19",
"Value":        24.6468 
},
{
 "TIME": "1993-02-01",
"LOCATION": "EA19",
"Value":       24.61376 
},
{
 "TIME": "1993-03-01",
"LOCATION": "EA19",
"Value":       24.74919 
},
{
 "TIME": "1993-04-01",
"LOCATION": "EA19",
"Value":       24.86336 
},
{
 "TIME": "1993-05-01",
"LOCATION": "EA19",
"Value":       24.93034 
},
{
 "TIME": "1993-06-01",
"LOCATION": "EA19",
"Value":       25.08189 
},
{
 "TIME": "1993-07-01",
"LOCATION": "EA19",
"Value":       25.19445 
},
{
 "TIME": "1993-08-01",
"LOCATION": "EA19",
"Value":       25.28793 
},
{
 "TIME": "1993-09-01",
"LOCATION": "EA19",
"Value":       25.42252 
},
{
 "TIME": "1993-10-01",
"LOCATION": "EA19",
"Value":       25.64734 
},
{
 "TIME": "1993-11-01",
"LOCATION": "EA19",
"Value":       25.97734 
},
{
 "TIME": "1993-12-01",
"LOCATION": "EA19",
"Value":       26.21684 
},
{
 "TIME": "1994-01-01",
"LOCATION": "EA19",
"Value":       26.44835 
},
{
 "TIME": "1994-02-01",
"LOCATION": "EA19",
"Value":       26.70785 
},
{
 "TIME": "1994-03-01",
"LOCATION": "EA19",
"Value":       26.98524 
},
{
 "TIME": "1994-04-01",
"LOCATION": "EA19",
"Value":       27.12331 
},
{
 "TIME": "1994-05-01",
"LOCATION": "EA19",
"Value":        27.0256 
},
{
 "TIME": "1994-06-01",
"LOCATION": "EA19",
"Value":       27.07801 
},
{
 "TIME": "1994-07-01",
"LOCATION": "EA19",
"Value":       27.19782 
},
{
 "TIME": "1994-08-01",
"LOCATION": "EA19",
"Value":       27.28868 
},
{
 "TIME": "1994-09-01",
"LOCATION": "EA19",
"Value":       27.37548 
},
{
 "TIME": "1994-10-01",
"LOCATION": "EA19",
"Value":       27.45723 
},
{
 "TIME": "1994-11-01",
"LOCATION": "EA19",
"Value":       27.48841 
},
{
 "TIME": "1994-12-01",
"LOCATION": "EA19",
"Value":        27.4548 
},
{
 "TIME": "1995-01-01",
"LOCATION": "EA19",
"Value":       27.41512 
},
{
 "TIME": "1995-02-01",
"LOCATION": "EA19",
"Value":       27.48176 
},
{
 "TIME": "1995-03-01",
"LOCATION": "EA19",
"Value":       27.59102 
},
{
 "TIME": "1995-04-01",
"LOCATION": "EA19",
"Value":       27.58623 
},
{
 "TIME": "1995-05-01",
"LOCATION": "EA19",
"Value":       27.67757 
},
{
 "TIME": "1995-06-01",
"LOCATION": "EA19",
"Value":        27.8053 
},
{
 "TIME": "1995-07-01",
"LOCATION": "EA19",
"Value":       27.88472 
},
{
 "TIME": "1995-08-01",
"LOCATION": "EA19",
"Value":       27.98143 
},
{
 "TIME": "1995-09-01",
"LOCATION": "EA19",
"Value":       28.17615 
},
{
 "TIME": "1995-10-01",
"LOCATION": "EA19",
"Value":       28.29309 
},
{
 "TIME": "1995-11-01",
"LOCATION": "EA19",
"Value":        28.3582 
},
{
 "TIME": "1995-12-01",
"LOCATION": "EA19",
"Value":       28.77685 
},
{
 "TIME": "1996-01-01",
"LOCATION": "EA19",
"Value":       29.01545 
},
{
 "TIME": "1996-02-01",
"LOCATION": "EA19",
"Value":       28.93705 
},
{
 "TIME": "1996-03-01",
"LOCATION": "EA19",
"Value":        29.0125 
},
{
 "TIME": "1996-04-01",
"LOCATION": "EA19",
"Value":        29.1907 
},
{
 "TIME": "1996-05-01",
"LOCATION": "EA19",
"Value":       29.37968 
},
{
 "TIME": "1996-06-01",
"LOCATION": "EA19",
"Value":       29.51245 
},
{
 "TIME": "1996-07-01",
"LOCATION": "EA19",
"Value":        29.6464 
},
{
 "TIME": "1996-08-01",
"LOCATION": "EA19",
"Value":       29.86647 
},
{
 "TIME": "1996-09-01",
"LOCATION": "EA19",
"Value":       30.13628 
},
{
 "TIME": "1996-10-01",
"LOCATION": "EA19",
"Value":       30.41588 
},
{
 "TIME": "1996-11-01",
"LOCATION": "EA19",
"Value":        30.7076 
},
{
 "TIME": "1996-12-01",
"LOCATION": "EA19",
"Value":       31.14834 
},
{
 "TIME": "1997-01-01",
"LOCATION": "EA19",
"Value":       31.39457 
},
{
 "TIME": "1997-02-01",
"LOCATION": "EA19",
"Value":       31.42654 
},
{
 "TIME": "1997-03-01",
"LOCATION": "EA19",
"Value":        31.5139 
},
{
 "TIME": "1997-04-01",
"LOCATION": "EA19",
"Value":        31.5112 
},
{
 "TIME": "1997-05-01",
"LOCATION": "EA19",
"Value":       31.72257 
},
{
 "TIME": "1997-06-01",
"LOCATION": "EA19",
"Value":       32.12764 
},
{
 "TIME": "1997-07-01",
"LOCATION": "EA19",
"Value":        32.4462 
},
{
 "TIME": "1997-08-01",
"LOCATION": "EA19",
"Value":       32.67791 
},
{
 "TIME": "1997-09-01",
"LOCATION": "EA19",
"Value":       32.87106 
},
{
 "TIME": "1997-10-01",
"LOCATION": "EA19",
"Value":       33.19031 
},
{
 "TIME": "1997-11-01",
"LOCATION": "EA19",
"Value":       33.43673 
},
{
 "TIME": "1997-12-01",
"LOCATION": "EA19",
"Value":       33.60683 
},
{
 "TIME": "1998-01-01",
"LOCATION": "EA19",
"Value":       33.84357 
},
{
 "TIME": "1998-02-01",
"LOCATION": "EA19",
"Value":       34.07332 
},
{
 "TIME": "1998-03-01",
"LOCATION": "EA19",
"Value":       34.42369 
},
{
 "TIME": "1998-04-01",
"LOCATION": "EA19",
"Value":       34.83324 
},
{
 "TIME": "1998-05-01",
"LOCATION": "EA19",
"Value":       35.12949 
},
{
 "TIME": "1998-06-01",
"LOCATION": "EA19",
"Value":       35.47555 
},
{
 "TIME": "1998-07-01",
"LOCATION": "EA19",
"Value":       35.65867 
},
{
 "TIME": "1998-08-01",
"LOCATION": "EA19",
"Value":       35.69506 
},
{
 "TIME": "1998-09-01",
"LOCATION": "EA19",
"Value":       35.87795 
},
{
 "TIME": "1998-10-01",
"LOCATION": "EA19",
"Value":       36.10749 
},
{
 "TIME": "1998-11-01",
"LOCATION": "EA19",
"Value":       36.48504 
},
{
 "TIME": "1998-12-01",
"LOCATION": "EA19",
"Value":       37.03155 
},
{
 "TIME": "1999-01-01",
"LOCATION": "EA19",
"Value":       38.16187 
},
{
 "TIME": "1999-02-01",
"LOCATION": "EA19",
"Value":       38.75322 
},
{
 "TIME": "1999-03-01",
"LOCATION": "EA19",
"Value":        38.7435 
},
{
 "TIME": "1999-04-01",
"LOCATION": "EA19",
"Value":       39.09586 
},
{
 "TIME": "1999-05-01",
"LOCATION": "EA19",
"Value":        39.4227 
},
{
 "TIME": "1999-06-01",
"LOCATION": "EA19",
"Value":       39.83759 
},
{
 "TIME": "1999-07-01",
"LOCATION": "EA19",
"Value":       40.32667 
},
{
 "TIME": "1999-08-01",
"LOCATION": "EA19",
"Value":       40.54995 
},
{
 "TIME": "1999-09-01",
"LOCATION": "EA19",
"Value":       40.58078 
},
{
 "TIME": "1999-10-01",
"LOCATION": "EA19",
"Value":       40.78627 
},
{
 "TIME": "1999-11-01",
"LOCATION": "EA19",
"Value":       41.06926 
},
{
 "TIME": "1999-12-01",
"LOCATION": "EA19",
"Value":       41.32917 
},
{
 "TIME": "2000-01-01",
"LOCATION": "EA19",
"Value":       42.15271 
},
{
 "TIME": "2000-02-01",
"LOCATION": "EA19",
"Value":       42.86397 
},
{
 "TIME": "2000-03-01",
"LOCATION": "EA19",
"Value":       43.01661 
},
{
 "TIME": "2000-04-01",
"LOCATION": "EA19",
"Value":       43.37188 
},
{
 "TIME": "2000-05-01",
"LOCATION": "EA19",
"Value":       43.40423 
},
{
 "TIME": "2000-06-01",
"LOCATION": "EA19",
"Value":       43.16895 
},
{
 "TIME": "2000-07-01",
"LOCATION": "EA19",
"Value":        43.2471 
},
{
 "TIME": "2000-08-01",
"LOCATION": "EA19",
"Value":       43.48307 
},
{
 "TIME": "2000-09-01",
"LOCATION": "EA19",
"Value":        43.5089 
},
{
 "TIME": "2000-10-01",
"LOCATION": "EA19",
"Value":       43.49262 
},
{
 "TIME": "2000-11-01",
"LOCATION": "EA19",
"Value":       43.52377 
},
{
 "TIME": "2000-12-01",
"LOCATION": "EA19",
"Value":       43.56802 
},
{
 "TIME": "2001-01-01",
"LOCATION": "EA19",
"Value":       44.41429 
},
{
 "TIME": "2001-02-01",
"LOCATION": "EA19",
"Value":       45.29337 
},
{
 "TIME": "2001-03-01",
"LOCATION": "EA19",
"Value":       45.40415 
},
{
 "TIME": "2001-04-01",
"LOCATION": "EA19",
"Value":       45.60655 
},
{
 "TIME": "2001-05-01",
"LOCATION": "EA19",
"Value":       45.98041 
},
{
 "TIME": "2001-06-01",
"LOCATION": "EA19",
"Value":       46.35096 
},
{
 "TIME": "2001-07-01",
"LOCATION": "EA19",
"Value":       46.52467 
},
{
 "TIME": "2001-08-01",
"LOCATION": "EA19",
"Value":       46.65725 
},
{
 "TIME": "2001-09-01",
"LOCATION": "EA19",
"Value":        47.0158 
},
{
 "TIME": "2001-10-01",
"LOCATION": "EA19",
"Value":        47.3329 
},
{
 "TIME": "2001-11-01",
"LOCATION": "EA19",
"Value":       47.62493 
},
{
 "TIME": "2001-12-01",
"LOCATION": "EA19",
"Value":       47.84648 
},
{
 "TIME": "2002-01-01",
"LOCATION": "EA19",
"Value":       48.17631 
},
{
 "TIME": "2002-02-01",
"LOCATION": "EA19",
"Value":       48.46411 
},
{
 "TIME": "2002-03-01",
"LOCATION": "EA19",
"Value":       48.37552 
},
{
 "TIME": "2002-04-01",
"LOCATION": "EA19",
"Value":       48.64307 
},
{
 "TIME": "2002-05-01",
"LOCATION": "EA19",
"Value":       49.19064 
},
{
 "TIME": "2002-06-01",
"LOCATION": "EA19",
"Value":       49.53513 
},
{
 "TIME": "2002-07-01",
"LOCATION": "EA19",
"Value":       49.87602 
},
{
 "TIME": "2002-08-01",
"LOCATION": "EA19",
"Value":       50.26094 
},
{
 "TIME": "2002-09-01",
"LOCATION": "EA19",
"Value":       50.76221 
},
{
 "TIME": "2002-10-01",
"LOCATION": "EA19",
"Value":       51.28067 
},
{
 "TIME": "2002-11-01",
"LOCATION": "EA19",
"Value":       51.79407 
},
{
 "TIME": "2002-12-01",
"LOCATION": "EA19",
"Value":       52.36625 
},
{
 "TIME": "2003-01-01",
"LOCATION": "EA19",
"Value":       52.77074 
},
{
 "TIME": "2003-02-01",
"LOCATION": "EA19",
"Value":       53.16687 
},
{
 "TIME": "2003-03-01",
"LOCATION": "EA19",
"Value":       53.68685 
},
{
 "TIME": "2003-04-01",
"LOCATION": "EA19",
"Value":       54.25433 
},
{
 "TIME": "2003-05-01",
"LOCATION": "EA19",
"Value":       54.74343 
},
{
 "TIME": "2003-06-01",
"LOCATION": "EA19",
"Value":       55.04864 
},
{
 "TIME": "2003-07-01",
"LOCATION": "EA19",
"Value":       55.35843 
},
{
 "TIME": "2003-08-01",
"LOCATION": "EA19",
"Value":       55.88484 
},
{
 "TIME": "2003-09-01",
"LOCATION": "EA19",
"Value":       56.38338 
},
{
 "TIME": "2003-10-01",
"LOCATION": "EA19",
"Value":       56.84136 
},
{
 "TIME": "2003-11-01",
"LOCATION": "EA19",
"Value":       57.27751 
},
{
 "TIME": "2003-12-01",
"LOCATION": "EA19",
"Value":       57.60481 
},
{
 "TIME": "2004-01-01",
"LOCATION": "EA19",
"Value":       58.05453 
},
{
 "TIME": "2004-02-01",
"LOCATION": "EA19",
"Value":       58.51064 
},
{
 "TIME": "2004-03-01",
"LOCATION": "EA19",
"Value":       59.12405 
},
{
 "TIME": "2004-04-01",
"LOCATION": "EA19",
"Value":       59.66764 
},
{
 "TIME": "2004-05-01",
"LOCATION": "EA19",
"Value":       59.80914 
},
{
 "TIME": "2004-06-01",
"LOCATION": "EA19",
"Value":       60.04566 
},
{
 "TIME": "2004-07-01",
"LOCATION": "EA19",
"Value":       60.50856 
},
{
 "TIME": "2004-08-01",
"LOCATION": "EA19",
"Value":       60.93562 
},
{
 "TIME": "2004-09-01",
"LOCATION": "EA19",
"Value":       61.46324 
},
{
 "TIME": "2004-10-01",
"LOCATION": "EA19",
"Value":       62.02033 
},
{
 "TIME": "2004-11-01",
"LOCATION": "EA19",
"Value":       62.50608 
},
{
 "TIME": "2004-12-01",
"LOCATION": "EA19",
"Value":       62.68278 
},
{
 "TIME": "2005-01-01",
"LOCATION": "EA19",
"Value":         63.259 
},
{
 "TIME": "2005-02-01",
"LOCATION": "EA19",
"Value":        64.2085 
},
{
 "TIME": "2005-03-01",
"LOCATION": "EA19",
"Value":       64.68111 
},
{
 "TIME": "2005-04-01",
"LOCATION": "EA19",
"Value":       65.02052 
},
{
 "TIME": "2005-05-01",
"LOCATION": "EA19",
"Value":       65.50085 
},
{
 "TIME": "2005-06-01",
"LOCATION": "EA19",
"Value":       68.02912 
},
{
 "TIME": "2005-07-01",
"LOCATION": "EA19",
"Value":       70.69855 
},
{
 "TIME": "2005-08-01",
"LOCATION": "EA19",
"Value":       71.40264 
},
{
 "TIME": "2005-09-01",
"LOCATION": "EA19",
"Value":       71.79672 
},
{
 "TIME": "2005-10-01",
"LOCATION": "EA19",
"Value":       72.30898 
},
{
 "TIME": "2005-11-01",
"LOCATION": "EA19",
"Value":       72.85094 
},
{
 "TIME": "2005-12-01",
"LOCATION": "EA19",
"Value":       73.40022 
},
{
 "TIME": "2006-01-01",
"LOCATION": "EA19",
"Value":       74.01407 
},
{
 "TIME": "2006-02-01",
"LOCATION": "EA19",
"Value":       74.55083 
},
{
 "TIME": "2006-03-01",
"LOCATION": "EA19",
"Value":       75.00636 
},
{
 "TIME": "2006-04-01",
"LOCATION": "EA19",
"Value":       75.58829 
},
{
 "TIME": "2006-05-01",
"LOCATION": "EA19",
"Value":       76.28357 
},
{
 "TIME": "2006-06-01",
"LOCATION": "EA19",
"Value":       76.62312 
},
{
 "TIME": "2006-07-01",
"LOCATION": "EA19",
"Value":        76.6317 
},
{
 "TIME": "2006-08-01",
"LOCATION": "EA19",
"Value":       76.74159 
},
{
 "TIME": "2006-09-01",
"LOCATION": "EA19",
"Value":       77.09966 
},
{
 "TIME": "2006-10-01",
"LOCATION": "EA19",
"Value":       77.34509 
},
{
 "TIME": "2006-11-01",
"LOCATION": "EA19",
"Value":       77.68481 
},
{
 "TIME": "2006-12-01",
"LOCATION": "EA19",
"Value":       78.84289 
},
{
 "TIME": "2007-01-01",
"LOCATION": "EA19",
"Value":       79.67982 
},
{
 "TIME": "2007-02-01",
"LOCATION": "EA19",
"Value":        79.9219 
},
{
 "TIME": "2007-03-01",
"LOCATION": "EA19",
"Value":       80.47432 
},
{
 "TIME": "2007-04-01",
"LOCATION": "EA19",
"Value":       80.77096 
},
{
 "TIME": "2007-05-01",
"LOCATION": "EA19",
"Value":       81.06934 
},
{
 "TIME": "2007-06-01",
"LOCATION": "EA19",
"Value":       81.55901 
},
{
 "TIME": "2007-07-01",
"LOCATION": "EA19",
"Value":       82.03972 
},
{
 "TIME": "2007-08-01",
"LOCATION": "EA19",
"Value":       82.18539 
},
{
 "TIME": "2007-09-01",
"LOCATION": "EA19",
"Value":       82.30947 
},
{
 "TIME": "2007-10-01",
"LOCATION": "EA19",
"Value":       82.54807 
},
{
 "TIME": "2007-11-01",
"LOCATION": "EA19",
"Value":       82.72794 
},
{
 "TIME": "2007-12-01",
"LOCATION": "EA19",
"Value":       82.85064 
},
{
 "TIME": "2008-01-01",
"LOCATION": "EA19",
"Value":       82.92692 
},
{
 "TIME": "2008-02-01",
"LOCATION": "EA19",
"Value":       82.95743 
},
{
 "TIME": "2008-03-01",
"LOCATION": "EA19",
"Value":       83.04108 
},
{
 "TIME": "2008-04-01",
"LOCATION": "EA19",
"Value":       83.02673 
},
{
 "TIME": "2008-05-01",
"LOCATION": "EA19",
"Value":       82.94035 
},
{
 "TIME": "2008-06-01",
"LOCATION": "EA19",
"Value":       83.14603 
},
{
 "TIME": "2008-07-01",
"LOCATION": "EA19",
"Value":       82.86255 
},
{
 "TIME": "2008-08-01",
"LOCATION": "EA19",
"Value":       82.47297 
},
{
 "TIME": "2008-09-01",
"LOCATION": "EA19",
"Value":       83.06293 
},
{
 "TIME": "2008-10-01",
"LOCATION": "EA19",
"Value":       84.66315 
},
{
 "TIME": "2008-11-01",
"LOCATION": "EA19",
"Value":       85.57481 
},
{
 "TIME": "2008-12-01",
"LOCATION": "EA19",
"Value":       85.77071 
},
{
 "TIME": "2009-01-01",
"LOCATION": "EA19",
"Value":       87.08936 
},
{
 "TIME": "2009-02-01",
"LOCATION": "EA19",
"Value":       88.61129 
},
{
 "TIME": "2009-03-01",
"LOCATION": "EA19",
"Value":       89.24678 
},
{
 "TIME": "2009-04-01",
"LOCATION": "EA19",
"Value":       89.91353 
},
{
 "TIME": "2009-05-01",
"LOCATION": "EA19",
"Value":       90.55128 
},
{
 "TIME": "2009-06-01",
"LOCATION": "EA19",
"Value":       91.27214 
},
{
 "TIME": "2009-07-01",
"LOCATION": "EA19",
"Value":       92.33842 
},
{
 "TIME": "2009-08-01",
"LOCATION": "EA19",
"Value":       93.27842 
},
{
 "TIME": "2009-09-01",
"LOCATION": "EA19",
"Value":       94.25706 
},
{
 "TIME": "2009-10-01",
"LOCATION": "EA19",
"Value":       95.30753 
},
{
 "TIME": "2009-11-01",
"LOCATION": "EA19",
"Value":       96.05846 
},
{
 "TIME": "2009-12-01",
"LOCATION": "EA19",
"Value":         96.662 
},
{
 "TIME": "2010-01-01",
"LOCATION": "EA19",
"Value":       97.54897 
},
{
 "TIME": "2010-02-01",
"LOCATION": "EA19",
"Value":       98.31366 
},
{
 "TIME": "2010-03-01",
"LOCATION": "EA19",
"Value":       98.63911 
},
{
 "TIME": "2010-04-01",
"LOCATION": "EA19",
"Value":       99.23502 
},
{
 "TIME": "2010-05-01",
"LOCATION": "EA19",
"Value":       99.97299 
},
{
 "TIME": "2010-06-01",
"LOCATION": "EA19",
"Value":       100.4933 
},
{
 "TIME": "2010-07-01",
"LOCATION": "EA19",
"Value":       100.7884 
},
{
 "TIME": "2010-08-01",
"LOCATION": "EA19",
"Value":       100.9891 
},
{
 "TIME": "2010-09-01",
"LOCATION": "EA19",
"Value":       100.9876 
},
{
 "TIME": "2010-10-01",
"LOCATION": "EA19",
"Value":       100.8263 
},
{
 "TIME": "2010-11-01",
"LOCATION": "EA19",
"Value":       100.9576 
},
{
 "TIME": "2010-12-01",
"LOCATION": "EA19",
"Value":        101.248 
},
{
 "TIME": "2011-01-01",
"LOCATION": "EA19",
"Value":        101.465 
},
{
 "TIME": "2011-02-01",
"LOCATION": "EA19",
"Value":       101.4914 
},
{
 "TIME": "2011-03-01",
"LOCATION": "EA19",
"Value":       101.6778 
},
{
 "TIME": "2011-04-01",
"LOCATION": "EA19",
"Value":       101.7034 
},
{
 "TIME": "2011-05-01",
"LOCATION": "EA19",
"Value":       101.4663 
},
{
 "TIME": "2011-06-01",
"LOCATION": "EA19",
"Value":       101.6489 
},
{
 "TIME": "2011-07-01",
"LOCATION": "EA19",
"Value":       101.9684 
},
{
 "TIME": "2011-08-01",
"LOCATION": "EA19",
"Value":       102.4359 
},
{
 "TIME": "2011-09-01",
"LOCATION": "EA19",
"Value":       102.8938 
},
{
 "TIME": "2011-10-01",
"LOCATION": "EA19",
"Value":       102.8473 
},
{
 "TIME": "2011-11-01",
"LOCATION": "EA19",
"Value":       103.0727 
},
{
 "TIME": "2011-12-01",
"LOCATION": "EA19",
"Value":       103.4961 
},
{
 "TIME": "2012-01-01",
"LOCATION": "EA19",
"Value":       103.7507 
},
{
 "TIME": "2012-02-01",
"LOCATION": "EA19",
"Value":       104.0126 
},
{
 "TIME": "2012-03-01",
"LOCATION": "EA19",
"Value":       104.3917 
},
{
 "TIME": "2012-04-01",
"LOCATION": "EA19",
"Value":       104.2829 
},
{
 "TIME": "2012-05-01",
"LOCATION": "EA19",
"Value":       104.4968 
},
{
 "TIME": "2012-06-01",
"LOCATION": "EA19",
"Value":       105.4526 
},
{
 "TIME": "2012-07-01",
"LOCATION": "EA19",
"Value":       106.4347 
},
{
 "TIME": "2012-08-01",
"LOCATION": "EA19",
"Value":       107.5349 
},
{
 "TIME": "2012-09-01",
"LOCATION": "EA19",
"Value":       108.1583 
},
{
 "TIME": "2012-10-01",
"LOCATION": "EA19",
"Value":        108.848 
},
{
 "TIME": "2012-11-01",
"LOCATION": "EA19",
"Value":       109.7129 
},
{
 "TIME": "2012-12-01",
"LOCATION": "EA19",
"Value":       109.9425 
},
{
 "TIME": "2013-01-01",
"LOCATION": "EA19",
"Value":       109.9458 
},
{
 "TIME": "2013-02-01",
"LOCATION": "EA19",
"Value":        110.441 
},
{
 "TIME": "2013-03-01",
"LOCATION": "EA19",
"Value":       111.2357 
},
{
 "TIME": "2013-04-01",
"LOCATION": "EA19",
"Value":       111.9644 
},
{
 "TIME": "2013-05-01",
"LOCATION": "EA19",
"Value":       112.6621 
},
{
 "TIME": "2013-06-01",
"LOCATION": "EA19",
"Value":       113.0374 
},
{
 "TIME": "2013-07-01",
"LOCATION": "EA19",
"Value":       113.3991 
},
{
 "TIME": "2013-08-01",
"LOCATION": "EA19",
"Value":        114.171 
},
{
 "TIME": "2013-09-01",
"LOCATION": "EA19",
"Value":       114.7283 
},
{
 "TIME": "2013-10-01",
"LOCATION": "EA19",
"Value":       115.3526 
},
{
 "TIME": "2013-11-01",
"LOCATION": "EA19",
"Value":       116.1904 
},
{
 "TIME": "2013-12-01",
"LOCATION": "EA19",
"Value":       116.3057 
},
{
 "TIME": "2014-01-01",
"LOCATION": "EA19",
"Value":       116.4739 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

========================================================

Rationale and Algorithm  

The two charts' gradient difference bespeaks a more expansionary policy, hence a more aggressive increase in money supply on Turkey’s part, both **before** and **after** the 2010 index year – starting, as I pointed out above, around 2001, which confirms Alp’s and Elekdag’s remark that in 2001 the CBRT’s monetary policy departed radically from that of previous years.  
As to the value computed by the cost function, it is expressed by the following formula:  
$$COST = [(MT_{t} – MT_{2010})/MT_{2010}]/[(ME_{t} – ME_{2010})/ME_{2010}]$$
where:  
MT = Turkish money supply.  
ME = Euro Area money supply.  
COST = ratio of Turkish increase rate in money supply over Euro Area’s increase rate in money supply. 

========================================================

**This “cost” is a leverage multiplier: a typical cost over our time series, equal, say, to 4 or 5, indicates that on a certain time interval Turkey’s money supply was increasing four or five times faster that of the Euro Area – indicating thereby, by implication, the extent to which Turkey would have been penalized in its expansionary monetary policies by a hypothetical Euro Area membership.**  

## Caveat  
The cost function misfires for 2010-05-01 and 2010-06-01 because of the following incongruence in the OECD time series: they equate the 2010 money supply with the index 100, but being monthly data, they do not reach the value of 100 at the same time: the Turkish money supply touches 100 between June 2010 (98.63) and July 2010 (100.53), while the Euro Area money supply touches 100 one month earlier, between May 2010 (99.97) and June 2010 (100.79).  

========================================================

## References
IMFworkingPaper2011: Alp, Harun and Elekdag, Selim. "The Role of Monetary Policy in Turkey during the Global Financial Crisis." IMF Working Papers, 2011. URL: (https://www.imf.org/external/pubs/ft/wp/2011/wp11150.pdf)  
OECD2015: "Narrow Money (M1) Indicator." OECD. doi: 10.1787/7a23d68b-en. URL: (https://data.oecd.org/money/narrow-money-m1.htm)  


