# r-data-analysis
Data aggregation for multiple columns using `tidyverse` and `lubridate`.

Something I came across while working on a data extract and thought it would nice to have this done in a much easier way within R using `tidyverse` (`dplyr` specifically) and `lubridate` libraries.


Raw data looks like this:

date\_time**|**unique\_id**|**value\_strg
:-----:|:-----:|:-----:
01APR2019:00:40:59.143344|6bac10fc9dbf4930bbac9221e431f491|AB\_XX\_TC\_01
01APR2019:00:44:26.633913|dc06372e007c46faa3417e9e0191653b|AB\_XX\_TC\_01
01APR2019:01:16:24.893093|de96c2c4f6d04cf2a3d88a193831c61d|AB\_XX\_TC\_01
01APR2019:01:45:58.980530|a24724c7c8ce40f1b2a5131a759a74e0|AB\_XX\_TC\_01
01APR2019:02:00:38.768965|8d757b6cfd904504a5407b568aa38601|AB\_XX\_TC\_01


