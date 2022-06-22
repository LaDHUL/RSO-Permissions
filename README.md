# setting permissions

## wanted result

The wanted result is to be seen in the file RDF/rome-siecles-permissions.ttl

## the rest api way

The rest api way is to be found in REST/permissions.rest .

It uses the VS Code REST extension: https://code.visualstudio.com/api/references/vscode-api .

The two missing features are:
- the addition of classes to the `ProjectResourceCreateRestrictedPermission` administrative permission
- the setting of `projectRestrictedViewSize` property

## the RDF way

The three files by-pass the API and talk directly to the triple store.

The ways to talk to the triple store are discribed in the files headers.