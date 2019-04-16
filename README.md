# IE11-XXE
XML External Entity for Internet Explorer11

POC to exfil  Windows "system.ini" file.
Note: Edit attacker server IP in the script to suit your needs.

1) Use below script to create the "datatears.xml" XML and XXE embedded "msie-xxe-0day.mht" MHT file.

2) python -m SimpleHTTPServer

3) Place the generated "datatears.xml" in Python server web-root.

4) Open the generated "msie-xxe-0day.mht" file, watch your files be exfiltrated.

poc from http://hyp3rlinx.altervista.org/advisories/MICROSOFT-INTERNET-EXPLORER-v11-XML-EXTERNAL-ENTITY-INJECTION-0DAY.txt
