# OPENSSL-Commands

Convert the .cer file to .pem file 
openssl x509 -inform PEM -in Root.cer -out Root.pem
openssl x509 -inform PEM -in Intermediate.cer -out Intermediate.pem

