# Police Cadet Evaluation Dataset
A dataset with real-world data about police cadet evaluation useful for training in people analytics.
 
### Source: 
Original owners/Donors: Korps landelijke politiediensten and Ministerie van Justitiem the Netherlands.

### Past usage:
Colijn, van Pienhoven. Using bayesian statistics in forecasting police performance. 8th International Conference on IT security and law enforcement, 2000. 
The objective of the investigation is to see if requirements for passing the standard 5-year evaluation can be predicted based on data collected at the time of graduation of police cadets. The primary reason for the study is to find key indicators for the current 20% fail rate, which is considered unacceptable.

### Relevant information:
One of the main reasons for the analysis was to study the effects of lowering admission standards (accepting cadets with past criminal records and lowering the minimum grade from 5.5 to 4.0).

### Size of the dataset: 
2000 observations

### Number of attributes: 
9 attributes (including one class, and one help attribute)
1. Age: the age at which the cadet started studying to become a police officer
2. AvG: average grade at the time of graduation (scale 1-10)
3. Chdn: number of children at the time of graduation
4. ExEd: extra university-level or equivalent education (years)
5. CR: criminal record (0=No, 1=Yes)
6. Sex: sex of the cadet (0 = Male, 1 = Female)
7. SecE: other experience in the security sector (0 = No, 1 = Yes)
8. AvgE: average yearly evaluation score (The average of five years. The evaluation is performed by a committee of 10 senior police officers. Scale 1-5). This is a help attribute and not for use as input.
9. FinalE: final evaluation. Fail if average yearly evaluation score (Avg) < 2.0 otherwise pass. (�Pass�/�Fail�). This is the target attribute.

### Missing attribute values:
None

### Class distribution: 
PASS: 1610
FAIL: 390
