# MACS3.Connected Cloud-Services

The MACS3.Connected Cloud-Services enable users to perform stability, lashing and dangerous cargo calculations for vessels.

You can easily integrate the services into your solutions by calling the RESTful APIs, so your application will make HTTP requests and parse the response. By default, the response format is JSON

## Requirements

* A MACS3.Connected account for your company
* A company related API-Key
* A company/vessel assignment (by IMO-Number)

## Quick Start: Explore the services through RESTful APIs

The service documentations are based on the OpenAPI specification (aka Swagger) and can best be explored by using a REST Client like Swagger or Postman.

* Swagger is has got the benefit of being a combination of REST Client and built-in documentation right at your fingertips - so it's a good point to start.
* Postman is the most-used REST Client worldwide and gives you maximum flexibility and unlimited options. More experienced users may prefer to use Postman as REST Client and use the Swagger documentation just for reference.

Have your API-Key ready and follow our [Swagger](swagger.md) or [Postman](postman.md) guide (Stability) for a quick start.

## Advanced: Integrate the services into your solution

When it comes to integration, you should use Client SDKs to take the RESTful API complexity out of coding as the SDKs provide models and endpoints for each service as reusable packages. 
 
* If your coding platform is C#, you may use the SDKs published by Navis NCVS at nuget.org:  

  MACS3.Connected.SDK.Stability  
  MACS3.Connected.SDK.Lashing  
  MACS3.Connected.SDK.DangerousCargo  
  
  Have your API-Key ready and see how to call the services in the [C# Stability Sample](csharp_stability.md) and [C# Lashing Sample](csharp_lashing.md).

* If you are coding on another platform e.g. JavaScript, Java, Objective C, Swift or C++, consider auto-generating the Client SDKs. The service documentations can be used as input by a variety of popular code-generators like [Swagger Codegen](https://swagger.io/tools/swagger-codegen) or [SwaggerHub](https://swagger.io/tools/swaggerhub) to generate Client SDKs. Please check out the documentation of your preferred code-generator for details. 

  The following service documentations are available:
  * https://api.stability.macs3.com
  * https://api.lashing.macs3.com
  * https://api.dago.macs3.com

  Even when coding on another platform, see how to call the stablity service in the [C# Stability Sample](csharp_stability.md) and  [C# Lashing Sample](csharp_lashing.md).
