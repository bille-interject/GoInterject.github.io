---
title: jAcct()
layout: custom
keywords: [jacct, function, chart of accounts]
description: A helper function that specifies filters for up to six segments of a Chart of Accounts  
---
##  Function Summary 

A helper function that specifies filters for up to six segments of a Chart of Accounts. 

###  Function Arguments   
  
| Parameter Name | Description                              | Default | Optional |
|----------------|------------------------------------------|---------|----------|
| Segment1       | The first segment of a chart of accounts |         | YES*     |
| ...            | ...                                      |         | YES*     |
| Segment6       | The last segment of a chart of accounts  |         | YES*     |

* Note that segments are optional and defined by each organization's needs. 


```Excel
=jAcct( Segment1 , Segment2 , Segment3 , Segment4 , Segment5 , Segment6 )
```

