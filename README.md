# Call Performance Demo Application (C# using RestSharp)

This is a simple C# application that uses RestSharp library to demonstrate how to use RingCentral's Analytics Call Performance APIs.

More information about RingCentral Analytics API and how to get access to the same can be found in the [developer guide.](https://developers.ringcentral.com/guide/analytics)

## PreRequisite:

1. .Net SDK (.Net or .Net Core)
2. RestSharp Library - we will use this to make HTTP Rest API Calls
3. RingCentral [.NET SDK] (https://github.com/ringcentral/RingCentral.Net)
4. Have a RingCentral Application with 'Analytics Permission'. If you don't have a RingCentral App, you can easily create one from the [Developer Portal] (https://developers.ringcentral.com/login.html#/)
5. Get the RingCentral Application ID & Secret Key from Developer Dashboard - "Production" credentials as that will be used for authentication purpose

## Steps to run the program

1. Clone/Download this GitHub Repository
2. Navigate to the WebAPIClient folder
2. Edit the "Program.cs" file by adding authentication support. For more information regarding the same refer to this [guide](https://developers.ringcentral.com/guide/authentication).
3. Compile and Run the program by executing the following commands
```
dotnet add package RingCentral.Net --version 5.8.0
dotnet add package RestSharp
dotnet run                  
```
4. Open Console to see the JSON Response of the Call Performance APIs (Aggregate & Timeline Data)

