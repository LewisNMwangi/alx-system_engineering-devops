<img src=./image.png width=50%>

## Issue Summary:
On March 2, 2022, from 2:00 PM to 4:30 PM EAT, users were unable to access our website due to a web server outage. The outage affected all users and caused 100% downtime for our website.

## Timeline:
2:00 PM EST: The web server outage was detected by our monitoring system, which alerted the on-call engineer.
2:05 PM EST: The engineer attempted to restart the web server, but the restart failed.
2:10 PM EST: The engineer investigated the web server logs for any errors or abnormalities.
2:30 PM EST: The engineer suspected that the issue might be due to a misconfiguration in the web server software.
2:45 PM EST: The engineer reached out to the software development team for assistance in debugging the issue.
3:00 PM EST: The software development team joined the investigation and examined the web server configuration files.
3:30 PM EST: The software development team discovered that the web server software was misconfigured, causing it to use an outdated SSL certificate that had expired.
4:00 PM EST: The software development team updated the SSL certificate and restarted the web server, resolving the issue.
4:30 PM EST: The website was fully functional again.

## Root Cause and Resolution:
The root cause of the web server outage was a misconfigured SSL certificate. The web server software was using an outdated SSL certificate that had expired, causing the server to fail to start properly. The issue was fixed by updating the SSL certificate and restarting the web server.

## Corrective and Preventative Measures:
To prevent similar issues from occurring in the future, the following measures will be taken:
Regular monitoring and maintenance of SSL certificates to ensure they are up-to-date and not expired.
Implement an automated monitoring system to check SSL certificate expiration dates and alert us when they are approaching expiration.
Improve documentation for configuring SSL certificates in the web server software.
Conduct regular training sessions for the engineering team on best practices for maintaining web server software and SSL certificates.

## Tasks to address the issue:
-Update the SSL certificate for the web server and configure it properly.
-Add automated monitoring for SSL certificate expiration dates.
-Document the SSL certificate configuration process in the web server software.
-Conduct training sessions for the engineering team on web server maintenance and SSL certificate best practices.

