# Data-Profiling
The project involves profiling a largish data set and then analyzing the profile with a possibly fictitious subject matter expert.
- Data Source: https://opendata.vancouver.ca/explore/dataset/business-licences/
- Software: Ataccama Data Quality Analyzer https://www.ataccama.com/product/data-discovery-and-profiling/dqa

### Contents
- Overview of Project
- Initial Assessment
  - LicenceRSN : Duplicates
  - BusinessName: NULL values
  - UnitType: Various values for a type
  - PostalCode: NULL values
  - PostalCode: Various formats
  - Province: Invalid values
- SME Review of Initial Assessment
  - LicenceRSN : Duplicates (High Priority)
  - PostalCode: Invalid Values (Medium Priority)
  - UnitType: Various values for a type (Medium Priority)
  - BusinessName: NULL values (Low Priority)
  - Province: Invalid values (Low Priority)
- Further Research for the SME
  - The volume of issued licences per month
  - Invalid IssuedDate
- SME Review of Further Research
- SME Suggests Some DQ Rules
  - LicenceRSN
  - BusinessName
  - UnitType
  - PostalCode
  - Province
  - IssuedDate
