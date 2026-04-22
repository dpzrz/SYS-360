Before NACLs:
- Take Screenshots (2) showing Public Instance webpage from workstation browser on port 80 and 8080
- Curl from Private instance to Public Instance webpage on port 80 and 8080 cosmosweb FTP banner from Private Instance

After NACLs
- Blocked port 8080 to Public Instance Web from your workstation
- Successful port 8080 curl from Private Instance
- Blocked/Timed out nc on port 21 from Private Instance to cosmosweb.champlain.edu
- Public NACL rules
- Private NACL rules

