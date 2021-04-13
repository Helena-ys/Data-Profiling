# Data-Profiling
The project involves profiling a largish data set and then analyzing the profile with a possibly fictitious subject matter expert.
- Data Source: https://opendata.vancouver.ca/explore/dataset/business-licences/
- Software: Ataccama Data Quality Analyzer https://www.ataccama.com/product/data-discovery-and-profiling/dqa

### Contents
- Overview of Project	1
- Initial Assessment	2
  - LicenceRSN : Duplicates	2
  - BusinessName: NULL values	3
  - UnitType: Various values for a type	4
  - PostalCode: NULL values	5
  - PostalCode: Various formats	6
  - Province: Invalid values	6
- SME Review of Initial Assessment	7
  - LicenceRSN : Duplicates (High Priority)	7
  - PostalCode: Invalid Values (Medium Priority)	7
  - UnitType: Various values for a type (Medium Priority)	7
  - BusinessName: NULL values (Low Priority)	7
  - Province: Invalid values (Low Priority)	7
- Further Research for the SME	8
  - The volume of issued licences per month	8
  - Invalid IssuedDate	8
- SME Review of Further Research	10
- SME Suggests Some DQ Rules	10
  - LicenceRSN	10
  - BusinessName	10
  - UnitType	10
  - PostalCode	10
  - Province	10
  - IssuedDate	10
