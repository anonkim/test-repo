header
======

header
------

### header

#### header

**x** **x**

| column1 |  column2| colume3 |
|:--------|--------:|:-------:|
| left    |    right|  center |
| row2    |     row2|   row2  |

![Boxplot of Diamond etc](markdownfile_files/figure-markdown_github/unnamed-chunk-1-1.png)

one explanation for this unexpected finding is that ideal cut diamonds also tend to be **smaller**.
the mean is \(E(carat | cut=Ideal) = 0.7979397\), and size is related to price.

    ## 
    ## Call:
    ## lm(formula = price ~ carat, data = diamonds)
    ## 
    ## Residuals:
    ##      Min       1Q   Median       3Q      Max 
    ## -18585.3   -804.8    -18.9    537.4  12731.7 
    ## 
    ## Coefficients:
    ##             Estimate Std. Error t value Pr(>|t|)    
    ## (Intercept) -2256.36      13.06  -172.8   <2e-16 ***
    ## carat        7756.43      14.07   551.4   <2e-16 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## Residual standard error: 1549 on 53938 degrees of freedom
    ## Multiple R-squared:  0.8493, Adjusted R-squared:  0.8493 
    ## F-statistic: 3.041e+05 on 1 and 53938 DF,  p-value: < 2.2e-16

|           |     D|     E|     F|     G|     H|     I|    J|
|:----------|-----:|-----:|-----:|-----:|-----:|-----:|----:|
| Fair      |   163|   224|   312|   314|   303|   175|  119|
| Good      |   662|   933|   909|   871|   702|   522|  307|
| Very Good |  1513|  2400|  2164|  2299|  1824|  1204|  678|
| Premium   |  1603|  2337|  2331|  2924|  2360|  1428|  808|
| Ideal     |  2834|  3903|  3826|  4884|  3115|  2093|  896|

> \`\`\`Call: lm(formula = price ~ carat, data = diamonds)

Residuals: Min 1Q Median 3Q Max -18585.3 -804.8 -18.9 537.4 12731.7

Coefficients: Estimate Std. Error t value Pr(\>|t|)
(Intercept) -2256.36 13.06 -172.8 \<2e-16 *** carat 7756.43 14.07 551.4 \<2e-16 *** --- Signif. codes: 0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1549 on 53938 degrees of freedom Multiple R-squared: 0.8493, Adjusted R-squared: 0.8493 F-statistic: 3.041e+05 on 1 and 53938 DF, p-value: \< 2.2e-16
