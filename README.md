This package will be useful to read data from properties file placed in test/resources folder.
Create property file "/properties/AutoWorld.properties" under resource folder.
Use ConfigProvider.getAsString(key) and ConfigProvider.getAsInt(key) methods to get property values.

Even we can access property value of any custom properties files using ConfigProvider.getAsString(fileName,key) and ConfigProvider.getAsInt(fileName,key)