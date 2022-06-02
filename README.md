# ESI integration

## Client app
- Download app: https://esi.uz/index/help/eimzo 

## Frontend project
-  install packages : ```npm i```
-  run app : ```npm run start```

## Backend side
- Install E-IMZO soap: ```http://{host}:{port}/dsvs/pkcs7/v1?wsdl```
- Use ```Pkcs7Client``` interface
- Verify signing data with ```verifyPkcs7``` method
- Demo C# source in the ```demo/dotnet.zip``` file

