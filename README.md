# dmoney-jmeter-performance-test


## Files Included
- dmoney.jmx
- deposit.csv
- sendMoney.csv
- payment.csv

## Test Scenario
- 5 agents perform deposits for 10 customers
- 5 customers send money to another 10 customers
- 5 customers make payments to 2 merchants

## Thread Group Configuration
| Thread Group | Threads | Loop | Ramp-up |
|---|---|---|---|
| Deposit | 5 | 2 | 120s |
| Send Money | 5 | 2 | 120s |
| Payment | 5 | 2 | 120s |

## Report Screenshots

### Request Summary
<img width="1751" height="589" alt="Screenshot 2026-05-23 210228" src="https://github.com/user-attachments/assets/d0fe9060-c687-485b-9298-2017c83c3a64" />


### Statistics
<img width="1684" height="584" alt="Screenshot 2026-05-23 210248" src="https://github.com/user-attachments/assets/7fd2eb61-ad76-466b-8789-f6246800377f" />


## Tools Used
- Apache JMeter
- CSV Data Set Config
- HTML Report

