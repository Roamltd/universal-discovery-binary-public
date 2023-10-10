User has to be logged in as Root user into the Machine before performing the below steps.

1. copy the folder manualscanlinux dir to the server which has to be scanned
2. chmod 744  scanlinux-x64
3. Commandlines for execution based on Environment

* Linux 64bit architecture

./scanlinux-x64 -cfg:scan.cxz -l:`hostname`.xsf

4. Output file will be created and location will be visible where its saved .xsf format. Share output file with UD team.
5. manualscanlinux dir can be deleted from the server to be scanned once the activity is completed.

