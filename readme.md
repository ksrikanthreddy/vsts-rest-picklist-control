This a fork of the [multi value extension](https://github.com/Microsoft/vsts-extension-multivalue-control) that draws its values from an admin specified rest endpoint rather than a hard coded list.

## To Build
```cmd
npm i -g typescript tslint gulp tfx-cli
git clone https://github.com/ksrikanthreddy/vsts-rest-picklist-control.git
cd vsts-rest-picklist-control
npm i
npm run package:dev
```



## Structure
All build tasks are contained in [package.json](https://github.com/ostreifel/vsts-rest-multivalue/blob/master/package.json)

Inputs are specified in [vss-extension.json](https://github.com/ostreifel/vsts-rest-multivalue/blob/master/vss-extension.json)

All extension logic, markup and styling is in [src](https://github.com/ostreifel/vsts-rest-multivalue/tree/master/src)
