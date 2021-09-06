Analysis Result
====

## Applications with hard-coded IPv4 addresses

The smali files extracted from the APK files were subjected to string matching and exclusion of specific information using regular expressions. As a result, 184,354 applications were identified as containing IPv4 addresses. This is the number of applications that were identified as having at least one IPv4 address in one application.
Of the total number of applications surveyed, 37.40% were found to be hard-coded with IPv4 addresses.
In addition, a total of 24,980 different IP address occurrences were observed.

### Number of strings identified as IPv4 addresses with the highest number of occurrences

| Address | Num of appearances | IP Address Type |
----|---:|----
| 127.0.0.1 | 217,494 | Local Loopback |
| 0.0.0.0 | 127,043 | Entire Internet |
| 1.4.8.32 | 38,534 | Global |
| 10.0.2.2 | 31,233 | Private |
| 1,2.10.27 | 26,903 | Global |
| 1.4.7.32 | 19,377 | Global |
| 117.97.87.6 | 17,553 | Global  |
| 10.0.1.1 | 15,761 | Private  |
| 2.7.0.33 | 15,516 | Global  |
| 1.4.1.19 | 14,541 | Global |

### Number of hardcoded applications per address type

| Address Type | Num of Apps ||
----|---:|---:
| Entire Internet (0.0.0.0) | 45,412 | 24.63%  |
| Global | 120,394 | 65.31%  |
| Private | 42,567 | 23.09%  |
| Local Loopback | 87,006 | 47.20%  |
| Link-local | 120 | 0.07%  |
| Class D | 1,311 | 0.71% |
| Class E | 653 | 0.35%  |

### Number of hardcoded applications per address type (not including other address types)

| Address Type | Num of Apps ||
----|---:|---:
| Entire Internet (0.0.0.0) | 3,514 | 1.91%  |
| Global | 63.068 | 32.21%  |
| Private | 14.081 | 7.64%  |
| Local Loopback | 26,303 | 14.27%  |
| Link-local | 7 | 0.00%  |
| Class D | 72 | 0.04% |
| Class E | 15 | 0.01%  |

## Applications with hard-coded IPv6 addresses
*These evaluations should be made with caution: the notation of IPv6 addresses is highly flexible, and there is a higher possibility than for IPv4 addresses that entries that are not originally IPv6 addresses will be detected as IPv6 addresses in string matching searches using regular expressions.*
*In fact, the IPv6 address that was identified as appearing the most is ''::'', and since there is a large possibility that this expression appears in other codes, it is unlikely that this number of occurrences is the actual number of IPv6 addresses. It is highly possible that this number of occurrences is incorrectly recorded, as the top 10 addresses in the number of occurrences all contain this ''::'''. In fact, the number of occurrences of '::' is 726,834, which is 1.47 times the number of applications surveyed, and there is a large difference with IPv6 addresses, which have the second largest number of occurrences.*

*Therefore, in this study, we decided to treat the number of occurrences as a reference and not analyze or discuss the situation based on the size of the value.*

### Number of strings identified as IPv4 addresses with the highest number of occurrences

| Address | Num of appearances |
----|---:
| :: | 726,834  |
| e:: | 16,532  |
| ed:: | 4,170  |
| 2:: | 3,247  |
| d:: | 2,839  |
| ce:: | 2,674  |
| E:: | 1,053  |
| a:: | 1,001  |
| de:: | 761  |
| aded:: | 565  |
 