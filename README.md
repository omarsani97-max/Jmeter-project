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
- Test executed for the below mentioned scenario in ```Server```(https://www.saucedemo.com/v1/) 
- 5000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 49.98 And Total Concurrent API requested: 5000.
- 8000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 76.89 And Total Concurrent API requested: 8000.
- 10000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 99.84 And Total Concurrent API requested: 10000.
- Gradually increase user request till 28000 then found error.
- 28000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 108.54 And Total Concurrent API requested: 28000.
- While executed 28000 concurrent request, found 4 request got " Non HTTP response code: java.net.SocketException" and error rate is 0.01%.
- Then 29000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 138.87 And Total Concurrent API requested: 29000.
- While executed 29000 concurrent request, found 4676 request got " Non HTTP response code: java.net.SocketException" and error rate is 16.12%
- Then error rate increased with concurrent request number.
- <img width="1629" height="484" alt="image" src="https://github.com/user-attachments/assets/b5b9ddf7-2e2c-4b64-8e42-239c3c0f5c7d" />
- Summary: Server can handle almost concurrent 28000 API call with almost zero (0) error rate.
Please find the details report from the attachment and let me know if you have any further queries

