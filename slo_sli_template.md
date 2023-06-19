# API Service

| Category     | SLI                                       | SLO                                                                                                         |
|--------------|-------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Availability | successful HTTP requests per minute       | Application up 99% of the time over the last 5 days                                                         |
| Latency      | latency of a backend web server response  | 90% of web requests completed successfully below 100ms                                                      |
| Error Budget | correctness probe                         | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   | the total number of requests              | 5 RPS over the last 10 minutes indicates the application is functioning                                     |
