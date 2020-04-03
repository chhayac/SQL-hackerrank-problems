###**[Weather Observation Station 13](https://www.hackerrank.com/challenges/weather-observation-station-13/problem)

Query the sum of Northern Latitudes (LAT_N) from STATION having values greater than 38.7880 and less than 137.2345 . Truncate your answer to 4 decimal places.

Input Format

The STATION table is described as follows:


|  Field | Type |
|---|---|
| ID  | NUMBER |
| CITY | VARCHAR2(21)   |
| STATE  | VARCHAR2(2)  |
| LAT_N |  NUMBER |
| LONG_W | NUMBER |

where LAT_N is the northern latitude and LONG_W is the western longitude.

**Solution**
```sql
select truncate(sum(lat_n),4) from station where lat_n between 38.7880 and 137.2345;
```

###**[Weather Observation Station 14](https://www.hackerrank.com/challenges/weather-observation-station-14/problem)

Query the greatest value of the Northern Latitudes (LAT_N) from STATION that is less than 137.2345. Truncate your answer to 4 decimal places.

Input Format

The STATION table is described as follows:


|  Field | Type |
|---|---|
| ID  | NUMBER |
| CITY | VARCHAR2(21)   |
| STATE  | VARCHAR2(2)  |
| LAT_N |  NUMBER |
| LONG_W | NUMBER |

where LAT_N is the northern latitude and LONG_W is the western longitude.

**Solution**
```sql
select truncate(max(lat_n),4) from station where lat_n< 137.2345;
```
