###**[Revising the Select Query-1](https://www.hackerrank.com/challenges/revising-the-select-query)**


Query all columns for all American cities in CITY with populations larger than 100,000. The CountryCode for America is USA.

Input Format

The CITY table is described as follows:

|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |

**Solution**
```sql
SELECT * FROM CITY WHERE COUNTRYCODE = 'USA' AND POPULATION > 100000;
```


###**[Revising the Select Query-2](https://www.hackerrank.com/challenges/revising-the-select-query-2)**

Query the names of all American cities in CITY with populations larger than 120,000. The CountryCode for America is USA.

Input Format

The CITY table is described as follows:

|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |


**Solution**
```sql
SELECT NAME FROM CITY WHERE COUNTRYCODE = 'USA' AND POPULATION > 120000;
```

###**[Select All](https://www.hackerrank.com/challenges/select-all-sql)**

Query all columns for every row in the CITY table.

Input Format

The CITY table is described as follows:

|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |


**Solution**
```sql
SELECT * FROM CITY;
```

###**[Select by ID](https://www.hackerrank.com/challenges/select-by-id)**

Query all columns for a city in CITY with the ID 1661.

Input Format

The CITY table is described as follows:

|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |


**Solution**
```sql
SELECT * FROM CITY WHERE ID = 1661; 
```

###**[Japanese Cities' Detail](https://www.hackerrank.com/challenges/japanese-cities-detail)**

Query the details for all the Japanese cities in CITY. The COUNTRYCODE for Japan is JPN.

Input Format

The CITY table is described as follows:

|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |


**Solution**
```sql
SELECT * FROM CITY WHERE COUNTRYCODE = 'JPN';        
```

###**[Japanese Cities' Name](https://www.hackerrank.com/challenges/japanese-cities-name)**

Query the the names of all the Japanese cities in CITY. The COUNTRYCODE for Japan is JPN.

Input Format

The CITY table is described as follows:

|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |


**Solution**
```sql
SELECT NAME FROM CITY WHERE COUNTRYCODE = 'JPN';        
```
