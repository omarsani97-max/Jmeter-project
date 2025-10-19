## API Performance Test with Jmeter
## Prerequisite
- API Test site
- Jmeter
- Windows command tool
## About This project
This project is reflecting performance of this project server.How the server is behaving while facing high level of user hit at a time.
we will find this server throughput,when the server started to show low performance and till how many user can handle easily at a time.
## Summery of report
- I’ve completed performance test on frequently used API for test Server. 
- Test executed for the below mentioned scenario in server ```Server```(https://www.saucedemo.com/v1/) 
- 200 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 234 And Total 
Concurrent API requested: 1400.
- 300 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 350 And Total 
Concurrent API requested: 2100.
- 400 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 424 And Total 
Concurrent API requested: 2800.
- 500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 443 And Total 
Concurrent API requested: 3500.
- While executed 500 concurrent request, found 82 request got connection timeout and error rate 
is 0.23%. 
- Summary: Server can handle almost concurrent 3200 API call with almost zero (0) error rate.
Please find the details report from the attachment and let me know if you have any further 
queries

