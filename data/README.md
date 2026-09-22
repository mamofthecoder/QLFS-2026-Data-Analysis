# Data

The project uses the Statistics South Africa Quarterly Labour Force Survey (QLFS) 2026 Q1 unit-record dataset.

The raw dataset is intentionally **not included** in this public portfolio repository. The official source should be used to obtain the data and accompanying metadata.

Official QLFS 2026 portal:
https://isibaloweb.statssa.gov.za/pages/surveys/pss/qlfs/2026/qlfs2026.php

The analysis uses the survey `Weight` variable for weighted descriptive comparisons. Survey-specific missing/not-applicable values were handled during cleaning, including the very large floating-point sentinel used in fields such as `Hrswrk` and `Unempl_Status`.
