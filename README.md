# openssl-ca-tool
Support one-level CA
## Usage
1. Set ```CATOP``` to a directory where CA hierarchy will be generated
2. Use ```CA -newca``` to setup the right stuff
3. Use ```ALTNAMES="DNS:example.com,DNS:example.net" CA -newreq-nodes-alt``` to generate a certificate request with SubjectAltNames
4. Use ```CA -sign``` to sign the generated request and output certificate
