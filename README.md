# Insurance statistics

This repository contains data on Austrian insurance statistics from 2002 to 2019. The data with was obtained from the website of the Austrian Financial Market Authority ([Link](https://www.fma.gv.at/en/insurance/queries/insurance-statistics/)) using a simple script and may therefore still contain errors. Structural breaks in the data, historical trends of various variables, possible data errors and many other interesting aspects can be explored using this data set. 

The data contains 6 columns:

**Column 1: (VU- Nr. / No.):** Unique insurance number.

**Column 2: (Versicherungsunternehmen / Insurance undertaking):** Name of the insurance company. One unique insurance number can be associated with several names of insurance companies.

**Column 3: (Kategorie / category):** Identifying field for a table element. In case the header of a table consists of several lines, the header elements are concatenated by "!". 


**Column 4: (value / value):** Cell content of the table identified by column 3.

**Column 5: (Tabelle / Tabelle):** Information from which of the 54 insurance statistics tables the value comes.

**Column 6: (year / year):** Year to which the statistic refers.
