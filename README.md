# Specmatic REST POC

**Specmatic Set Up**
___

1. Install specmatic npm
```
npm install -g specmatic
```
3. Run specmatic without installing the package
```
npx specmatic
```

**Technology Stack**
___

-Specmatic
-OpenAPI
-Visual Studio

**Open API files**
___

-employees.yaml
-service.yaml

**How To Execute Contract Test To Validate Provider**
___

```
npx specmatic test service.yaml --testBaseURL=https://my-json-server.typicode.com/specmatic/specmatic-documentation-examples
```


