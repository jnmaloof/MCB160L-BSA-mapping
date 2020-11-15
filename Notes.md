2020-11-14

Trying different outcross parameters
| ---- | min-cov. | qual. | min-AF | max-Cov | Comments           |
|:-----|:---------|:------|:-------|:--------|:-------------------|
| V1   | 10       | 25    | 0.98   | 0.02    |                    |
| V2   | 10       | 25    | 0.99   | 0.01    |                    |
| V3   | 5        | 15    | 0.98   | 0.02    |                    |
| V4   | 1        | 15    | 0.975  | 0.03    | most getting worse |
| V5   | 5        | 20    | 0.976  | 0.04    | Hequan for EMS01   |


### EMS01 
V1: peak visible but no defined interval
V2: peak visible but no defined interval
V3: peak visible but no defined interval
V4: peak visible but no defined interval
V5: Chrom1 0 ~ 429999


### EMS02
V1: Chrom4 11370000 ~ 11754999  
V2: Chrom4 11400000 ~ 11629999
V3: Chrom4 11370000 ~ 11759999
V4: Chrom4 10975000 ~ 12509999
V5: Chrom4 10925000 ~ 12904999

### EMS05
V1: Chrom1 2850000 ~ 4044999 (a little messy)  
V2: Chrom1 no interval
V3: Chrom1 2845000 ~ 4044999
V4: Chrom1 2205000 ~ 4329999
V5: Chrom1 1490000 ~ 4624999

### EMS07
V1: Chrom4 11370000 ~ 11984999  
V2: Chrom4 11370000 ~ 11834999
V3: Chrom4 11370000 ~ 12044999
V4: Chrom4 10940000 ~ 12124999
V5: Chrom4 10940000 ~ 14009999

### EMS10
V1: Bad, few markers
V2: Bad, few markers
V3: Somewhat better but messy. Chrom1: 815000 ~ 1039999
V4: Chrom1: 815000 ~ 1059999 but still high AF throughout

### EMS12

V1: BAD; very few markers
V2: BAD; very few markers
V3: Somewaht better Chrom4 10680000 ~ 11784999
V4: Somewhat better Chrom4 11005000 ~ 11744999

min coverage: 5, quality: 15, min AF 0.98, min covariance 0.02
EMS01: still no region

## Bottom line

No single best setting.  Here are the settings for each mutant:

| ---- | min-cov. | qual. | min-AF | max-Cov | Comments     |
|:-----|:---------|:------|:-------|:--------|:-------------|
| V1   | 10       | 25    | 0.98   | 0.02    | EMS05        |
| V2   | 10       | 25    | 0.99   | 0.01    | EMS02, EMS07 |
| V3   | 5        | 15    | 0.98   | 0.02    | EMS10        |
| V4   | 1        | 15    | 0.975  | 0.03    | EMS12        |
| V5   | 5        | 20    | 0.976  | 0.04    | EMS01        |
