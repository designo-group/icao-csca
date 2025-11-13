# icao-csca
This repository contains public CSCA (Country Signing Certificate Authority) certificates used to validate the authenticity of electronic passports (eMRTDs) according to ICAO Doc 9303.


Notes
```
openssl x509 -inform DER -in CSCA.cer -out CSCA.pem
cat *.pem > masterList.pem
```


https://www.icao.int/icao-pkd/epassport-validation-roadmap-tool-access
