# RedHat-Advisory-Checker
Script that automatically checks the RedHat security advisories to see if a CVE applies

Made for Python 2.7 and 3.4<br />
Runs on Linux (tested on Ubuntu 14.04) <br />
Requires an internet connection (queries https://access.redhat.com/security/cve/)

Install instructions:
 * Download and unpack the project (either download the zip or do a git clone)
 * Run `python setup.py install` as a super user

Accepted input formates (as stdin or parameter):
 * CVE-YYYY-XXXX
 * YYYY-XXXX
 * XXXX (will automatically add the current year)
