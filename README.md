# OYM Indoor SDK for Android

## Introduction

The indoor module is split in three different packages:
- Indoor SDK (com.oym.indoor)
- Indoor Location SDK (com.oym.indoor.location)
- Indoor Routing SDK (com.oym.indoor.routing)

## Preparing the environment
### AndroidManifest.xml

```xml
<uses-sdk




### Importing libraries
In order to work properly, the app shall include the following libraries:



/** Floor number */

The following step is to create a new instance of the indoor location library:
lib = new IndoorLocationLib(context, oymWebservicesUrl, oymUser, oymPassword);
In order to stop properly the library, it is necessary to call the `stopLocate()` method when the library is no longer needed and the location service should be stopped

## Creating a route

```java


```java


```java

In order to show the indoor maps overlap in Google Map, this guide assumes that the app already have an initialized GoogleMap object called map. Further information in how to include a map in your app can be found [here](https://developers.google.com/maps/documentation/android/).

```
```


