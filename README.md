# test123

The goal of this project is to take a list of domains or IP’s and determine what provider is hosting the domain as well if the domain is flagged as suspicious utilizing Virustotal’s API.  A list of domains/IP's in a separate file will be provided to use as the input for this project.

Acceptance Criteria:
Take the list of domains/ip’s and use virustotal.com api to scan the URL or review previous results as well as utilizing other tools to determine who hosts the site.
Be able to read in a text file that contains a list of domains/IP's to test for
Write to a file called output.txt

Output for each domain should include:
Does the site/domain exist? ex. Yes/No
Suspicious or Not : ex. Yes/No
How many Scanners reported as Malicious: ex. 5
The type of suspicious site: ex. “Malicious site”
List ISP/Organization that hosts the domain: ex. Affinity Internet, Inc


Please create the code to do this work and provide a link to the code in a public github



Sample entries in output.txt file:


domain.com
Real domain: Yes
Suspicious Site: No
Scanners Reporting: 5
Suspicious Type: Malicious Site
ISP/Organization: Affinity Internet, Inc.

notarealdomain12345.com
Real domain: No
Suspicious Site: No
Scanners Reporting: 0
Suspicious Type: NA
ISP/Organization: NA
