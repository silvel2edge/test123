# test123

The goal of this project is to take a list of domains or IP’s and determine what provider is hosting the domain as well if the domain is flagged as suspicious utilizing Virustotal’s API.  A list of domains/IP's in a separate file will be provided to use as the input for this project.

Acceptance Criteria:
-Be able to read in a text file that contains a list of domains/IP's to test
-Take the list of domains/ip’s and use virustotal.com api and other tools to determine the following:
   -Real Domain: Yes/No
   -Suspicious Site: Yes/No
   -Scanners Reporting: INT or NA
   -Suspicious Type: String or NA
   -ISP/Organization: String or NA
-Write to a file called output.txt


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
