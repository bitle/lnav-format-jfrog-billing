# JFrog Billing Report format for Lnav
Lnav format for reading JFrog Billing Report files

## Usage
To start using this format, download format definition to your formats directory:
```
mkdir -p ~/.lnav/formats/installed
curl -o ~/.lnav/formats/installed/jfrog_billing.json https://raw.githubusercontent.com/bitle/lnav-format-jfrog-billing/main/jfrog_billing.json
```

Then run lnav on your artifactory billing files:
```
lnav artifactory-traffic-2023-11-10-4a3d4e4a.log.gz
```

# Links
(Lnav)[https://github.com/tstack/lnav]
[Data Transfer Logs](https://jfrog.com/help/r/jfrog-hosting-models-documentation/view-data-transfer-logs)
