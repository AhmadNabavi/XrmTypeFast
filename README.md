# XrmTypeFast
XrmTypeFast is a tool to easily work with Dynamics CRM API Odata service. With the help of TypeScript language, the developer can write his JS code with a syntax so close to C# style and away from all the complexities of the API Odata service such as odatabinding, _xyz_values, etc.

XrmTypeFast is composed of two main components: XrmTypeExtraction & XrmClientService:
	1) XrmTypeExtraction is a C# class library by running which, Object Types such as Entity Types, or Action Types are extracted
	2) XrmClientService is a TypeScript Class file which acts similare to IOrganizationServiceProxy in the XrmSDK so that it handles all CRUD operations in the C# style

Main benefit of using XrmTypeFast:
1- Type Safety: What is missing in JS is type saftey. By using Typescript language, XrmTypeFast will ensure type safety of variables
2- Fast typing: Types creatd can enable early-binding. Also, the C# style of coding the JS is very handy
3- Releive you from the pain of dealing with @odata.bind and _xyz_value stuf
4- Easy Async Await operation: No more chaining multiple server requests! Just await the first, then await the second, ...
5- More compatible with modern tools: FluentUI, PCF Controls

By the way, the tool is COMPLETELY FREE!

# How to use the tool?
A complete tutorial of using XrmTypeFast is available on my youtube channel
