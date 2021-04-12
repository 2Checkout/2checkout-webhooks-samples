# 2checkout-webhooks-samples

This project contains webhook samples in multiple languages.


If you want to use the C# sample:
To run the project use the following command:

dotnet run

To run the tests use the following command:

dotnet tests

To use the sample you should follow the below steps:

Copy the class IpnSignatureHandler
Initialize it as in the example from Program.cs
Generate the  tag containing the HMAC MD5 key using the method "generateTag" with the first argument being the IPN request body and the second argument being the secret key.
