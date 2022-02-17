pa_1
================

``` r
dur_hablo_stressed = 466.524
dur_hablo_unstressed = 431.445 
dur_o_stressed = 206.571 
dur_o_unstressed = 112.002 
int_o_stressed = 89.12363657574684 
int_o_unstressed = 81.35578152786863 
f0_o_stressed = 213.50404026286904 
f0_o_unstressed = 79.6648661980173  
```

# step 10: calculations

The difference in ms between “hablo” and “habló”

``` r
dur_hablo_unstressed - dur_hablo_stressed
```

    ## [1] -35.079

The difference in ms between the stressed and unstressed \[o\]

``` r
dur_o_stressed - dur_o_unstressed 
```

    ## [1] 94.569

The difference in intensity between the stressed and unstressed \[o\]

``` r
int_o_stressed - int_o_unstressed
```

    ## [1] 7.767855
