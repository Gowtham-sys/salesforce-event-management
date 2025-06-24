# Salesforce Event Management Project

## Deployment Instructions

1. Authenticate to your Salesforce Org:
```bash
sfdx force:auth:web:login -a YourOrgAlias
```

2. Push the project to your scratch org or sandbox:
```bash
sfdx force:source:push
```

3. Verify all custom objects, fields, and triggers in Salesforce Setup.
