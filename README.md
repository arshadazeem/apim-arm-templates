# apim-arm-templates

ARM templates to create APIM Infrastructure
Also contains output from the 'extractor' tool of the apim devops resource kit

**Importing Certificates into Azure Key Vault using ARM Template**
**Note:** Importing an existing cert through ARM template isn't supported in AKV yet (documented at:https://docs.microsoft.com/en-us/azure/key-vault/certificates/import-cert-faqs#can-i-import-a-certificate-by-using-an-arm-template). 

So, used the Azure CLI to import cert: az keyvault certificate import --file ${CERT_FILE} --name ${KV_CERT_NAME} --vault-name ${VAULT_NAME} --password ${CERT_PASSWORD}

