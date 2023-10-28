## Baltimore City Employee Salaries Dataset

**Description**:
This dataset includes Baltimore City employee salaries and gross pay from fiscal year 2011 through last fiscal year and includes employees who were employed on June 30 of the last fiscal year


**Data Dictionary**:

| Field Name    | Description   | Data Type | Range | Example Values |
|---------------|---------------|----------|-------|----------------|
| firstName    | First name of the employee. | Text | N/A | N/A |
| middleInitial| Middle initial of the employee. | Text | N/A | N/A |
| lastName     | Last name of the employee. | Text | N/A | N/A |
| jobClass     | The job classification. | Category | 1,898 unique job classifications. | "911 OPERATOR", "LABORER" |
| agencyID     | Identifier for the agency. | Text | 73 unique values. | "A01", "A54" |
| agencyName   | Name of the agency. | Text | 73 unique values. | "Police Department", "Public Works" |
| hireDate     | Hiring date. | Date | 6/23/1951 to 6/30/2021 | 4/3/1979 |
| annualSalary | Base annual salary for the fiscal year. | Number | 0 to 276375 | N/A |
| grossPay     | Total compensation for the fiscal year. | Number | 1.71 to 373111.20 | N/A |
| fiscalYear   | The fiscal year of employment. | Category | FY2011 to FY2021 | "FY2021" |

**Data Sources**:
- [ArcGIS Hub Dataset](https://data.baltimorecity.gov/maps/baltimore::baltimore-city-employee-salaries)
- [ArcGIS GeoService](https://services1.arcgis.com/UWYHeuuJISiGmgXx/arcgis/rest/services/Baltimore_CIty_Employee_Salary_Table/FeatureServer/0)
- [GeoJSON](https://data.baltimorecity.gov/datasets/baltimore::baltimore-city-employee-salaries.geojson)
- [CSV](https://data.baltimorecity.gov/datasets/baltimore::baltimore-city-employee-salaries.csv)

**Publisher**: Baltimore City
**Last Modified**: 2021-10-29
