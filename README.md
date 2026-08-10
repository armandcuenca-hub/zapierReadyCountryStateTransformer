# zapierReadyJStools
Zapier node Javascript to perform specific tasks:

1. **isoTransformer** = Transforms detected ISO country and state inputs into full name. 
   - Array lookup only involves common countries and states - needs to reference lookup to a more complete and extensive ISO country and state table, preferrably external
   
   Use Case: Stop gap to perform data normalization on State/Country when importing data to Salesforce which only accepts full data
  
2. **leadScorer** = references initial lead information like Job Title, Company, Company Size
   - Base only, can be modified to add additional fields to the score weighting
   - S&P 500 array is in the code, needs to reference lookup to an external table
   - Score values can be modified easily
  
   Use Case: Automate calculation of lead scoring for Sales team lead prioritization
