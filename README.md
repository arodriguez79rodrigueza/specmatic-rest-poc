# Specmatic REST POC

# Specmatic Set Up


1. Install Specmatic npm
```
npm install -g specmatic
```
3. Run specmatic without installing the package
```
npx specmatic
```

# Technology Stack
- Specmatic
- OpenAPI
- Visual Studio

# Open API files
- employees.yaml
- service.yaml

# How To Execute Contract Test To Validate the Provider
1. Execute the following code on Visual Studio for service.yaml by using a CMD window.
```
npx specmatic test service.yaml --testBaseURL=https://my-json-server.typicode.com/specmatic/specmatic-documentation-examples
```
2. Execute the following code on Visual Studio for employees.yaml by using a CMD window
```
npx specmatic test employees.yaml --testBaseURL https://my-json-server.typicode.com
```


