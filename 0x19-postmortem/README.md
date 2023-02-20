# Postmortem: Website Outage on February 15, 2023
# Issue Summary

On February 15, 2023, our website experienced an outage from 2:30 PM to 3:15 PM EST. During this time, all services on the website were unavailable, causing a complete loss of access for users. Approximately 80% of our users were affected by this outage.



# Timeline
* 2:30 PM EST: Issue detected when monitoring alerts indicated a drop in traffic.

* 2:31 PM EST: The engineering team was notified, and investigations began.

* 2:32 PM EST: Initial assumptions were that the outage was caused by a DDoS attack.

* 2:35 PM EST: Further investigations revealed that the outage was not caused by a DDoS attack, but rather a configuration issue in the server.

* 2:40 PM EST: The engineering team started a service restart to fix the issue.

* 3:15 PM EST: The service was restored, and the website was fully operational again. 

# Root Cause and Resolution

The root cause of the outage was a misconfiguration in the server settings, which led to a sudden crash in the server. The server's configuration settings were not set up correctly, leading to a bottleneck in the system and causing the server to become unresponsive. Once this was identified, the engineering team was able to make necessary changes to the configuration settings, which resolved the issue.

# Corrective and Preventative Measures

To prevent similar issues from happening in the future, the following measures will be implemented:

* A full review of server configuration settings to ensure they are set up correctly.

* Additional monitoring alerts will be implemented to better detect any potential issues before they cause an outage.

* Regular system testing and maintenance to ensure the website's infrastructure is up to date and functioning properly.

# Conclusion

We apologize for the inconvenience caused by the website outage on February 15, 2023. Our engineering team worked diligently to identify and resolve the issue quickly, and we will take steps to prevent similar incidents from occurring in the future.