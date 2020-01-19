# r-data-analysis
Data aggregation for multiple columns using `tidyverse` and `lubridate`.

Something I came across while working on a data extract and thought it would nice to have this done in a much easier way within R using `tidyverse` (`dplyr` specifically) and `lubridate` libraries.


Raw data looks like this:

**date\_time**|**unique\_id**|**value\_strg**
:-----:|:-----:|:-----:
01APR2019:00:40:59.143344|6bac10fc9dbf4930bbac9221e431f491|AB\_XX\_TC\_01
01APR2019:00:44:26.633913|dc06372e007c46faa3417e9e0191653b|AB\_XX\_TC\_01
01APR2019:01:16:24.893093|de96c2c4f6d04cf2a3d88a193831c61d|AB\_XX\_TC\_01
01APR2019:01:45:58.980530|a24724c7c8ce40f1b2a5131a759a74e0|AB\_XX\_TC\_01
01APR2019:02:00:38.768965|8d757b6cfd904504a5407b568aa38601|AB\_XX\_TC\_01
….| | 
….| | 
01APR2019:02:35:49.101547|38d933a7efde48a69f8574f9bbcd70e5|AB\_XY\_TD\_01
25APR2019:02:53:24.641941|0a9970b18346400a8d0de94c85397075|AB\_XY\_TD\_01
27APR2019:13:28:17.376849|e71461c4b8944a31af18d2dd14106f48|AB\_XY\_TD\_01
27APR2019:15:55:27.305589|1130ec2912ee48c4be25f27b8ae661a6|AB\_XY\_TD\_01



