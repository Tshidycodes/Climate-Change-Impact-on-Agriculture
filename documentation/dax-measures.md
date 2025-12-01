## Avg Crop Yield
**Description:** Calculates the average crop yield.
```DAX
Avg Crop Yield = AVERAGE(climate_impact_data[Crop_Yield_MT_per_HA])
```
## Total Economic Impact
**Description:** Calculates the total economic impact. 
```DAX
Total Economic Impact = SUM(climate_impact_data[Economic_Impact_Million_USD])
```
## Extreme Weather Events Count
**Description:** Calculates the count of extreme weather events.  
```DAX
Extreme Weather Events Count = COUNTROWS(climate_impact_data)
```
## Avg Temperature
**Description:** Calculates the average temperature.
```DAX
Avg Temperature = AVERAGE(climate_impact_data[Average_Temperature_C])
```
## Avg Temperature C
**Description:** Converts the Avg Temperature into degree Celsius.
```DAX
Avg Temperature C = FORMAT([Avg Temperature],"0.0° C")
```
