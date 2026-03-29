# Prevalence and recognition of obesity in SwissPedGrowth.

This GitHub repository shares the analysis code used for the manuscript "Prevalence and recognition of obesity in Swiss children’s hospitals: A cross-sectional study of the SwissPedGrowth project".

# Analysis scripts

Scripts from another repository [LorenzLeuenberger/Availability-Quality-SwissPedGrowth](https://github.com/LorenzLeuenberger/Availability-Quality-SwissPedGrowth) were used to clean the data. Prior to this, RDF graph data was received from the SwissPedHealth National Data Stream ([www.swisspedhealth.com](https://www.swisspedhealth.com/)) and was flattened into tabular .csv format using SPARQL queries. SwissPedHealth used a standard operating procedure to link the Swiss-SEP to the NDS: [LorenzLeuenberger/Transforming-addresses-to-Swiss-SEP_Standard-operating-procedure](https://github.com/LorenzLeuenberger/Transforming-addresses-to-Swiss-SEP_Standard-operating-procedure)

00_data-analysis.Rmd was used to analyze the data and create the figures and tables for the manuscript.
