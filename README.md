# performance-testing-project-using-jmeter
I’ve completed performance test on frequently used API for a test App https://thetestingworldapi.com.
Test executed for the below mentioned scenario in server https://thetestingworldapi.com.  
<ul>
<li>100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 90 And Total Concurrent API requested: 6000.</li>
<li>500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 146 And Total Concurrent API requested: 30000.</li>
  <li>700 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 166 And Total Concurrent API requested: 42000.</li>
</ul>
100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 90 And Total Concurrent API requested: 6000.
500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 146 And Total Concurrent API requested: 30000.
700 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 166 And Total Concurrent API requested: 42000.

While executed 500 concurrent request, found  12 request got connection timeout and error rate is 0.08%. 

Summary: Server can handle almost concurrent 20000 API call with almost zero (0) error rate.
